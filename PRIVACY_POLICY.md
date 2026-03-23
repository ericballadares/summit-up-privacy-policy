# Privacy Policy for Summit Up

**Last updated: March 23, 2026**

## Overview

Summit Up ("we", "our", or "the app") is a Philippine mountains hiking journal developed by Eric Balladares. This privacy policy explains how we collect, use, and protect your information when you use the Summit Up mobile application.

## Information We Collect

### Account Information
- **Email address** — used for account creation, authentication, and password recovery
- **Username** — required during registration, used for identification and login
- **Display name** — optional, set by you in your profile
- **Home region** — optional, set by you in your profile
- **Mother mountain** — optional, your first mountain climbed (auto-detected from earliest hike or manually set)
- **Profile photo** — optional, uploaded by you

### Hiking Activity Data
- **Hike logs** — date, duration, weather, companions, and notes you enter when logging a hike, including chain hikes (twin, trilogy, traverse)
- **Planned hikes** — future hike dates, notes, and mountain selections you create
- **Trail reports** — mountain information you submit for review (name, location, difficulty, trail class, classification, notes)
- **Corrections** — suggestions you submit to correct existing mountain data

### Automatically Collected Data
- We do **not** collect device identifiers, location data, analytics, or crash reports
- We do **not** use third-party tracking or advertising SDKs

## How We Use Your Information

Your data is used solely to provide the app's functionality:
- **Authentication** — to sign you in (via email or username) and secure your account
- **Hike logging** — to store and display your hiking history and statistics (hikes, mountains, provinces, regions)
- **Planning** — to save and show your planned hikes with countdowns
- **Trail reports and corrections** — to allow you to contribute mountain data and corrections for community review
- **Profile** — to personalize your experience within the app, including theme preferences

We do **not** use your data for advertising, marketing, profiling, or any purpose other than operating the app.

## Data Storage and Security

- All data is stored on **Supabase** (hosted on AWS), a cloud database platform
- Data is transmitted over **HTTPS** (encrypted in transit)
- Data is stored in a **password-protected database** with Row Level Security (RLS) policies on all tables, ensuring users can only access their own data
- Profile photos are stored in **Supabase Storage** with access controls restricting uploads to the photo owner
- Usernames are validated for format (lowercase, 3-20 characters, alphanumeric and underscores) and uniqueness
- Theme preferences are stored locally on your device via AsyncStorage

## Data Sharing

We do **not** sell, rent, trade, or share your personal data with any third parties.

Your data is only accessible to:
- **You** — through the app
- **The developer** — for technical support, trail report review, and correction review only

## Your Rights

You have the right to:
- **Access** your data through the app at any time
- **Edit** your profile, hike logs, planned hikes, and username
- **Delete** individual hike logs and planned hikes
- **Change your password** at any time from the Profile screen
- **Delete your entire account** — available in Profile > Delete Account, which permanently removes all your data including hike logs, planned hikes, trail reports, corrections, profile information, and your authentication credentials

## Data Retention

- Your data is retained as long as your account exists
- When you delete your account, all associated data is permanently removed from our servers
- We do not retain backups of deleted accounts
- Theme preferences stored on your device are cleared when you uninstall the app

## Children's Privacy

Summit Up is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal data, please contact us so we can delete it.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected by the "Last updated" date at the top of this page. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact

If you have questions about this privacy policy or your data, contact:

**Eric Balladares**
Email: ericsonballadares@gmail.com

## Summary

| What we collect | How we use it | Shared? |
|---|---|---|
| Email address | Authentication, password recovery, login | No |
| Username | Account identification, login | No |
| Display name | Profile display, avatar initials | No |
| Home region | Profile personalization | No |
| Mother mountain | Profile display (first mountain climbed) | No |
| Profile photo | Profile display | No |
| Hike logs | Store your hiking history and stats | No |
| Planned hikes | Store your future plans | No |
| Trail reports | Community mountain data (reviewed before publishing) | No |
| Corrections | Improve mountain data accuracy (reviewed before applying) | No |
| Theme preference | Stored locally on device only | No |
