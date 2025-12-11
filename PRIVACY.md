# Privacy Policy for TTTM Table Tennis Events Extension

**Last Updated:** December 11, 2025

## Overview
TTTM Table Tennis Events is a Chrome extension that enhances the browsing experience on tttm.co.il by displaying today's table tennis games in an organized view and allowing users to contribute video links for matches.

## Data Collection and Usage

### Information We Collect

When you choose to sign in with Google to add video links, we collect:

1. **Google Account Information** (collected only if you sign in):
   - Email address
   - Display name
   - Profile picture URL
   - Google user ID

2. **User-Generated Content**:
   - Video URLs you add for matches
   - Match identifiers associated with videos
   - Timestamps of when videos were added/updated

3. **Authentication Data**:
   - OAuth access tokens (stored locally in your browser)
   - Firebase authentication tokens (stored locally in your browser)

### How We Use Your Information

- **Authentication**: To verify your identity and manage your session
- **Authorization**: To determine if you're approved to add video links
- **Attribution**: To track which user added which video links
- **Display**: To show your name and photo in the video manager interface

### Where Your Data Is Stored

- **Google Firestore**: User profiles and video links are stored in Google's secure cloud database
- **Chrome Local Storage**: Authentication tokens are stored locally in your browser
- **Firebase Authentication**: Anonymous authentication sessions are created for database access

### Data Sharing and Access

- **No Third-Party Sharing**: We do not share your data with any third parties
- **Public Video Links**: Video URLs you add are visible to all users of this extension
- **User Profiles**: Your email and name are stored but not publicly displayed to other users
- **Internal Use Only**: Your Google account information is used solely for authentication and authorization

## Permissions Explained

### Required Permissions:

1. **Identity Permission**
   - Purpose: To enable Google Sign-In authentication
   - Data Access: Your Google account email, name, and profile picture
   - When Used: Only when you click "Sign in with Google"

2. **Storage Permission**
   - Purpose: To remember your login session
   - Data Stored: OAuth tokens, user ID, email, name, profile picture
   - Security: Data encrypted by Chrome's storage API

3. **Host Permissions (*.googleapis.com)**
   - Purpose: To communicate with Google Firestore database and authentication services
   - Data Transmitted: User authentication tokens and video link data
   - Security: All connections use HTTPS

4. **Host Permissions (www.tttm.co.il)**
   - Purpose: To display game information and video links on the TTTM website
   - Data Access: Publicly available match data from TTTM API
   - Modification: Adds video column to player pages

## Data Retention

- **User Accounts**: Retained as long as you remain an active user
- **Video Links**: Retained indefinitely unless you delete them
- **Authentication Tokens**: Automatically cleared when you sign out
- **Anonymous Firebase Users**: Created temporarily for database access

## Your Privacy Rights

### You Can:
- **View**: See all video links you've added in the video manager
- **Edit**: Modify video links you've created
- **Delete**: Remove video links you've added
- **Sign Out**: Clear all authentication data from your browser
- **Request Deletion**: Contact us to request full account deletion

### We Do NOT:
- Track your browsing history
- Monitor which pages you visit on TTTM
- Use analytics or tracking pixels
- Sell or share your data
- Store passwords (authentication handled by Google)
- Access your Google account beyond the requested scopes

## Data Security

- **Encryption**: All data transmission uses HTTPS/TLS encryption
- **Authentication**: Secure OAuth 2.0 protocol via Google
- **Authorization**: Admin approval required before users can add videos
- **Storage**: User data stored in Google Firestore with security rules
- **Local Storage**: Authentication tokens encrypted by Chrome

## Optional Features

**Signing in is OPTIONAL.** You can use the extension to:
- View today's games in organized layout
- See video links on player pages

**Signing in is REQUIRED only if you want to:**
- Add new video links for matches
- Edit your existing video links

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected with a new "Last Updated" date.

## Compliance

This extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Google API Services User Data Policy

## Google API Services Disclosure

This extension uses Google API Services and is subject to Google's Privacy Policy.

The extension's use and transfer of information received from Google APIs adheres to Google API Services User Data Policy, including the Limited Use requirements.
