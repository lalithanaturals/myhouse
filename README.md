# My House — Household Accounts

A household accounts and home management app for a joint family:
ledger, bills and dues, chits and loans, payroll, family transfers,
procurement, housekeeping schedule, meal plan, tasks, maintenance,
reminders, reports, and a Liquid Glass design.

## Logins and access (Firebase)

The website uses Google sign-in and a Firebase Firestore database.

- **Admins** (full access): kanthirava.b@gmail.com, bhargavmail93@gmail.com,
  lalithanaturals@gmail.com. The list lives in `fb.js` and `firestore.rules`.
- **Family**: an admin adds their Google email on **Users & Access**, then sets
  modules, limits and approval. Family members can only submit entries.
- **Security**: `firestore.rules` is enforced by Google. Paste it into
  Firebase console → Firestore Database → Rules → Publish.

Until the Firebase settings are added to `index.html`, the site runs in
device-only mode (saved in the browser, no logins).

## Files

- `index.html` — the whole app (HTML, CSS and JavaScript in one file).
- `firestore.rules` — database security rules to paste into Firebase.

## Editing with GitHub Copilot

Open the folder in VS Code and ask Copilot about `index.html`.
The app's logic is in the `<script id="appjs">` block near the end of the file.
