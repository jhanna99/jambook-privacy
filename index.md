# JamBook Privacy Policy

**Last updated: April 1, 2026**

## Overview

JamBook is a music song sheet viewer for iOS and Android that syncs PDF files from Google Drive. Your privacy is important to us. This policy explains what data JamBook accesses and how it is handled.

## Authentication

JamBook offers sign-in via Google, Apple, or guest mode. Authentication is handled by Firebase Authentication, a service provided by Google. When you sign in:

- Your email address and user ID are used to verify your identity and check access authorization
- Authentication tokens are managed by Firebase and stored securely on your device
- No passwords are stored by JamBook

You can delete your account at any time from within the app, which removes your authentication data from Firebase.

## Google Drive Integration

JamBook downloads song sheet PDF files and metadata from a shared Google Drive folder using a public API key. No personal Google Drive files are accessed. JamBook has read-only access to the shared song library folder and does not modify or delete any files on Google Drive.

## Firebase Services

JamBook uses the following Firebase services:

- **Firebase Authentication** — To manage sign-in with Google, Apple, or anonymous (guest) accounts
- **Cloud Firestore** — To check whether a signed-in user is authorized to access the full song library

No personal data is stored in Firestore beyond what is needed for authorization (email address).

## Local Data Storage

All user-created data is stored locally on your device and is never uploaded:

- **PDF files** downloaded from Google Drive are cached for offline access
- **User tags** you create are stored locally and not shared
- **View history** and jam session attendees are stored locally
- **App settings** and preferences are stored locally
- **PDF zoom/pan positions** are stored locally

## Data Collection

JamBook does not collect analytics, tracking data, advertising identifiers, or telemetry of any kind.

## Data Sharing

JamBook does not share any personal data with third parties. The only external communications are:

- Google Drive API (to download song files)
- Firebase Authentication (to verify sign-in)
- Firebase Firestore (to check authorization)
- YouTube (to load video thumbnails when links are present in song metadata)

## Children's Privacy

JamBook does not knowingly collect any information from children.

## Account Deletion

You can delete your account at any time from the app's menu. This permanently removes your Firebase authentication account and any associated data from Firestore.

## Changes to This Policy

Any changes to this privacy policy will be posted on this page with an updated date.

## Contact

If you have questions about this privacy policy, please contact: johnhanna99@gmail.com
