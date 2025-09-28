# Barb3r

A simple website hosted on Firebase with a privacy policy.

## Setup

1. Install Firebase CLI if you haven't already:
   ```bash
   npm install -g firebase-tools
   ```

2. Login to Firebase:
   ```bash
   firebase login
   ```

3. Update the `.firebaserc` file with your actual Firebase project ID

4. Install dependencies:
   ```bash
   npm install
   ```

5. Deploy to Firebase:
   ```bash
   npm run deploy
   ```

## Local Development

To serve the site locally:
```bash
npm run serve
```

## Structure

- `/` - Home page
- `/privacy` - Privacy policy page

## Firebase Hosting Configuration

The site is configured with Firebase Hosting in `firebase.json` with rewrites to handle the `/privacy` route properly.