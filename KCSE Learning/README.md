KCSE Learning Hub — No-Billing Deployment Build

What this is:
- A Vite React app that uses Firebase Authentication + Realtime Database (no Storage needed).
- Lessons and Past Papers use public links (YouTube / public PDFs / sample audio).
- Seed folder contains JSON you can import into Realtime Database console.

How to deploy (quick):
1. Unzip this project.
2. Create a Firebase project and enable Authentication + Realtime Database.
3. In Firebase console -> Project settings -> Register Web App and copy the config.
4. In Vercel, set environment variables (VITE_FIREBASE_API_KEY, VITE_FIREBASE_AUTH_DOMAIN, VITE_FIREBASE_PROJECT_ID, VITE_FIREBASE_MESSAGING_SENDER_ID, VITE_FIREBASE_APP_ID).
   (databaseURL is already set in src/firebase.js for your project).
5. Run locally:
   npm install
   npm run dev

Realtime DB URL used: https://kcse-learning-hub-8a30c-default-rtdb.firebaseio.com/

See /seed/README.md for instructions to populate the database with sample content.
