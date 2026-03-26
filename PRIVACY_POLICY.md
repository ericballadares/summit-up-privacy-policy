# Privacy Policy for Summit Up

**Last updated: March 27, 2026**

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
- **Hike logs** — date, duration, weather, companions (including tagged friends' usernames), privacy setting (Only Me, Friends, or Public), and notes you enter when logging a hike, including chain hikes (twin, trilogy, traverse)
- **Planned hikes** — future hike dates, notes, privacy setting, and mountain selections you create
- **Companion hike invites** — when another user tags your @username as a companion, we store a link between their hike and your account. You can accept (adds to your hike history) or reject (removes the link). You can untag yourself at any time.
- **Trail reports** — mountain information you submit for review (name, location, difficulty, trail class, classification, trails, notes)
- **Trail suggestions** — new trail or trail edit suggestions you submit for existing mountains
- **Corrections** — suggestions you submit to correct existing mountain data

### Social Data
- **Friend connections** — when you send or accept a friend request, we store the connection between your account and the other user's account
- **Friend request status** — pending, accepted, or declined

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
- **Friend system** — to allow you to connect with other hikers. Friends can view each other's profiles even if not set to public. Friend connections are visible only to the two users involved.
- **Friend tagging** — when you tag a friend in the companions field of a hike log, their @username is stored as part of your hike data. A companion hike invite is sent to the tagged user.
- **Per-hike privacy** — each hike and planned hike has a privacy setting (Only Me, Friends, Public). This controls who can see the hike when viewing your profile. Default is Friends.
- **Planned hike visibility** — your upcoming planned hikes may be visible to friends or the public based on each plan's privacy setting, so friends or other hikers can see where you're headed next
- **App updates** — the app checks for over-the-air updates on launch by contacting Expo's update servers (u.expo.dev). No personal data is sent in this request.

We do **not** use your data for advertising, marketing, profiling, or any purpose other than operating the app.

## Profile Visibility

Your profile is **private by default**. There are three levels of visibility:

### Public (opt-in)
Anyone can find and view your profile.

### Friends Only
If your profile is private, only accepted friends can view it.

### Private (default)
Only you can see your profile. Others see a "This profile is private" message with an option to send a friend request.

| Information | Public | Friends | Private |
|---|---|---|---|
| Username | Yes | Yes | Never |
| Display name | Yes | Yes | Never |
| Profile photo | Yes | Yes | Never |
| Hike count, mountains, provinces, regions | Yes | Yes | Never |
| Most visited mountains | Yes | Yes | Never |
| Province heatmap | Yes | Yes | Never |
| Mother mountain | Yes | Yes | Never |
| Email address | **Never** | **Never** | **Never** |
| Home region | **Never** | **Never** | **Never** |
| Home province | **Never** | **Never** | **Never** |
| Hikes set to "Public" | Yes | Yes | Never |
| Hikes set to "Friends" | Never | Yes | Never |
| Hikes set to "Only Me" | **Never** | **Never** | **Never** |
| Planned hikes set to "Public" | Yes | Yes | Never |
| Planned hikes set to "Friends" | Never | Yes | Never |
| Planned hikes set to "Only Me" | **Never** | **Never** | **Never** |
| Submissions (reports, corrections, trails) | **Never** | **Never** | **Never** |

You can toggle your public profile on or off at any time from the Profile edit screen. You can unfriend any user at any time.

## Data Storage and Security

- All data is stored on **Supabase** (hosted on AWS), a cloud database platform
- Data is transmitted over **HTTPS** (encrypted in transit)
- Data is stored in a **password-protected database** with Row Level Security (RLS) policies on all tables, ensuring users can only access their own data (unless they opt into a public profile or have an accepted friendship, in which case only the data described above is visible)
- Friend connections are protected by RLS — only the two users in a friendship can view, modify, or delete it
- Profile photos are stored in **Supabase Storage** with access controls restricting uploads to the photo owner
- Usernames are validated for format (lowercase, 3-20 characters, alphanumeric and underscores) and uniqueness
- Search input is sanitized to prevent injection attacks
- Public profile stats (hike counts, province/region counts) are computed server-side via secure database functions — other users cannot access your individual hike logs
- Theme preferences and welcome modal state are stored locally on your device via AsyncStorage
- The app contacts **Expo's update servers** (u.expo.dev) on launch to check for app updates. Only the app version and update channel are sent — no personal data, device identifiers, or location data is transmitted

## Data Sharing

We do **not** sell, rent, trade, or share your personal data with any third parties.

Your data is only accessible to:
- **You** — through the app
- **Your friends** — accepted friends can view your profile information as described in the Profile Visibility section, even if your profile is not set to public
- **Other users** — only if you enable your public profile, and only the information listed in the Profile Visibility section above
- **The developer** — for technical support, trail report review, trail suggestion review, and correction review only

## Your Rights

You have the right to:
- **Access** your data through the app at any time
- **Edit** your profile, hike logs, planned hikes, username, and pending submissions (trail reports, corrections, trail suggestions)
- **Control visibility** — toggle your public profile on or off at any time
- **Manage friends** — send, accept, decline, or cancel friend requests; unfriend users at any time
- **Manage companion invites** — accept or reject companion hike invites; untag yourself from any companion hike at any time
- **Delete** individual hike logs and planned hikes
- **Change your password** at any time from the Profile screen
- **Delete your entire account** — available in Profile > Delete Account, which permanently removes all your data including hike logs, planned hikes, trail reports, trail suggestions, corrections, friend connections, profile information, and your authentication credentials

## Data Retention

- Your data is retained as long as your account exists
- When you delete your account, all associated data is permanently removed from our servers, including friend connections
- We do not retain backups of deleted accounts
- Theme preferences and local state stored on your device are cleared when you uninstall the app

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
| Username | Account identification, login | Public or friends |
| Display name | Profile display, avatar initials | Public or friends |
| Home region | Profile personalization | Never |
| Home province | Profile personalization | Never |
| Mother mountain | Profile display (first mountain climbed) | Public or friends |
| Profile photo | Profile display | Public or friends |
| Hike logs | Store your hiking history and stats | Never (only aggregate stats if public/friends) |
| Planned hikes | Store your future plans | Based on per-plan privacy setting (friends/public) |
| Trail reports | Community mountain data (reviewed before publishing) | Never |
| Trail suggestions | Community trail data (reviewed before publishing) | Never |
| Corrections | Improve mountain data accuracy (reviewed before applying) | Never |
| Friend connections | Connect with other hikers | Only between the two friends |
| Companion hike invites | Link tagged hikes to your account | Only between hike owner and tagged user |
| Hike privacy setting | Control per-hike visibility | N/A |
| Theme preference | Stored locally on device only | Never |
| Public profile setting | Control your visibility to other users | N/A |
