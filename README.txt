ThankYou Admin — Simple Email Management System

Included files:
- index.html: Formal admin login, dashboard, recipient management, CSV import, campaign composer, campaign history, email logs
- style.css: Simple, responsive dark-sidebar dashboard design
- script.js: Demo login, 22 preloaded recipients, duplicate email checks, CSV import, subscription controls, campaign drafts/queue, preview, and browser storage
- recipients.csv: Recipient list for importing

Demo login:
Email: admin@example.com
Password: admin123

Login features: show/hide password, remember me (demo only), friendly invalid-login message, and password-recovery guidance.

Run:
1. Extract the ZIP.
2. Open index.html in a browser.
3. Sign in with the demo credentials above.

Features follow the provided requirements:
1. Recipient management (add, edit, delete, search, subscribed/unsubscribed)
2. CSV recipient import
3. Compose thank-you messages with {{name}} personalization in preview
4. Queue campaign records in the demo
5. Email log view for queued activity
6. Admin sign-in and prevention of selecting unsubscribed contacts

Important:
This is a front-end prototype. Queueing a campaign does not send real email. Delivery states (sent, delivered, failed), controlled batch sending, secure server-side authentication, and shared database storage require a PHP/MySQL backend and an authorised email service. Confirm consent before sending.

Security note: This is a front-end demo. Credentials are checked in browser JavaScript and are not secure for production. Use PHP server-side authentication, password_hash/password_verify, HTTPS, and secure sessions before deployment.
