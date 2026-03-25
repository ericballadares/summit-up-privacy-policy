# Privacy Policy for Summit Up

**Last updated: March 25, 2026**

## Overview

Summit Up ("we", "our", or "the app") is a Philippine mountains hiking journal developed by Eric Balladares. This privacy policy explains how we collect, use, and protect your information when you use the Summit Up mobile application.

## Information We Collect

### Account Information
- **Email address** — used for account creation, authentication, and password recovery
- **Username** — required during registration, used for identification and login
- **Display name** — optional, set by you in your profile
- **Home region** — optional, set by you in your profile
- **Home province** — optional, set by you in your profile
- **Mother mountain** — optional, your first mountain climbed (auto-detected from earliest hike or manually set)
- **Profile photo** — optional, uploaded by you
- **Public profile setting** — your choice to make your profile visible to other users (off by default)

### Hiking Activity Data
- **Hike logs** — date, duration, weather, companions, and notes you enter when logging a hike, including chain hikes (twin, trilogy, traverse)
- **Planned hikes** — future hike dates, notes, and mountain selections you create
- **Trail reports** — mountain information you submit for review (name, location, difficulty, trail class, classification, trails, notes)
- **Trail suggestions** — new trail or trail edit suggestions you submit for existing mountains
- **Corrections** — suggestions you submit to correct existing mountain data

### Automatically Collected Data
- We do **not** collect device identifiers, location data, analytics, or crash reports
- We do **not** use third-party tracking or advertising SDKs

## How We Use Your Information

Your data is used solely to provide the app's functionality:
- **Authentication** — to sign you in (via email or username) and secure your account
- **Hike logging** — to store and display your hiking history and statistics (hikes, mountains, provinces, regions)
- **Planning** — to save and show your planned hikes with countdowns
- **Trail reports, trail suggestions, and corrections** — to allow you to contribute mountain and trail data for community review
- **Profile** — to personalize your experience within the app, including theme preferences
- **Public profiles** — if you opt in, to display your username, display name, avatar, hiking stats (hike count, mountains, provinces, regions), most visited mountains, and a province heatmap to other users. Your email, home region, and home province are **never** shown to other users.
- **User search** — to allow other users to find your profile by username or display name, only if you have enabled your public profile

We do **not** use your data for advertising, marketing, profiling, or any purpose other than operating the app.

## Public Profile Visibility

Your profile is **private by default**. If you choose to make it public:

| Information | Visible to others? |
|---|---|
| Username | Yes |
| Display name | Yes |
| Profile photo | Yes |
| Hike count, mountains, provinces, regions | Yes |
| Most visited mountains | Yes |
| Province heatmap | Yes |
| Mother mountain | Yes |
| Email address | **Never** |
| Home region | **Never** |
| Home province | **Never** |
| Individual hike logs & details | **Never** |
| Planned hikes | **Never** |
| Submissions (reports, corrections, trails) | **Never** |

You can toggle your public profile on or off at any time from the Profile edit screen.

## Data Storage and Security

- All data is stored on **Supabase** (hosted on AWS), a cloud database platform
- Data is transmitted over **HTTPS** (encrypted in transit)
- Data is stored in a **password-protected database** with Row Level Security (RLS) policies on all tables, ensuring users can only access their own data (unless they opt into a public profile, in which case only the data described above is visible)
- Profile photos are stored in **Supabase Storage** with access controls restricting uploads to the photo owner
- Usernames are validated for format (lowercase, 3-20 characters, alphanumeric and underscores) and uniqueness
- Public profile stats (hike counts, province/region counts) are computed server-side via secure database functions — other users cannot access your individual hike logs
- Theme preferences are stored locally on your device via AsyncStorage

## Data Sharing

We do **not** sell, rent, trade, or share your personal data with any third parties.

Your data is only accessible to:
- **You** — through the app
- **Other users** — only if you enable your public profile, and only the information listed in the Public Profile Visibility section above
- **The developer** — for technical support, trail report review, trail suggestion review, and correction review only

## Your Rights

You have the right to:
- **Access** your data through the app at any time
- **Edit** your profile, hike logs, planned hikes, username, and pending submissions (trail reports, corrections, trail suggestions)
- **Control visibility** — toggle your public profile on or off at any time
- **Delete** individual hike logs and planned hikes
- **Change your password** at any time from the Profile screen
- **Delete your entire account** — available in Profile > Delete Account, which permanently removes all your data including hike logs, planned hikes, trail reports, trail suggestions, corrections, profile information, and your authentication credentials

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

| What we collect | How we use it | Shared with other users? |
|---|---|---|
| Email address | Authentication, password recovery, login | Never |
| Username | Account identification, login | Only if public profile enabled |
| Display name | Profile display, avatar initials | Only if public profile enabled |
| Home region | Profile personalization | Never |
| Home province | Profile personalization | Never |
| Mother mountain | Profile display (first mountain climbed) | Only if public profile enabled |
| Profile photo | Profile display | Only if public profile enabled |
| Hike logs | Store your hiking history and stats | Never (only aggregate stats if public) |
| Planned hikes | Store your future plans | Never |
| Trail reports | Community mountain data (reviewed before publishing) | Never |
| Trail suggestions | Community trail data (reviewed before publishing) | Never |
| Corrections | Improve mountain data accuracy (reviewed before applying) | Never |
| Theme preference | Stored locally on device only | Never |
| Public profile setting | Control your visibility to other users | N/A |
