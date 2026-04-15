# Privacy Policy for Summit Up

**Last updated: April 15, 2026** · **Version: 3**

## Overview

Summit Up ("we", "our", or "the app") is a Philippine mountains hiking journal developed by Ericson Balladares. This privacy policy explains how we collect, use, and protect your information when you use the Summit Up mobile application.

## Information We Collect

### Account Information
- **Email address** — used for account creation, authentication, and password recovery
- **Username** — required during registration, used for identification and login
- **Display name** — optional, set by you in your profile
- **Home region** — optional, set by you in your profile
- **Home province** — optional, set by you in your profile
- **Mother mountain** — optional, your first mountain climbed (auto-detected from earliest hike or manually set)
- **Profile bio** — optional, up to 150 characters, set by you in your profile
- **Profile photo** — optional, uploaded by you
- **Public profile setting** — your choice to make your profile visible to other users (off by default)

### Hiking Activity Data
- **Hike logs** — date, duration, weather, companions (including tagged friends' usernames), privacy setting (Only Me, Friends, or Public), photos (up to 3, auto-compressed), notes, optional difficulty rating (1-9), optional conditions vote (good/not ideal), optional hike type (DIY/Tour/Hybrid), and optional cost (₱) you enter when logging a hike, including chain hikes (twin, trilogy, traverse). For chain hikes, each mountain can have its own difficulty rating and conditions vote.
- **Companion photos** — when you are tagged as a companion on another user's hike, you can add up to 3 photos to your companion record. If the hike owner removes you as a companion, your companion hike is converted to a standalone hike log (preserving your photos). If you untag yourself, your companion hikes record is deleted (including your photos)
- **Planned hikes** — future hike dates, notes, privacy setting, and mountain selections you create
- **Packing checklists** — items you add to planned hike checklists, and reusable checklist templates you create (up to 3)
- **Companion hike invites** — when another user tags your @username as a companion, we store a link between their hike and your account. You can accept (adds to your hike history) or reject (removes the link). You can untag yourself at any time.
- **Trail reports** — mountain information you submit for review (name, location, coordinates, difficulty, trail class, classification, description, days required, trails, notes)
- **Trail suggestions** — new trail or trail edit suggestions you submit for existing mountains
- **Corrections** — suggestions you submit to correct existing mountain data
- **Feedback** — feature requests and bug reports you submit (title, description)
- **Bucket list** — mountains you save to your bucket list (mountain ID and date added). Your bucket list is private and not visible to other users
- **Mountain tag votes** — when you vote for a community tag on a mountain (e.g., "Day Hike Friendly", "Has Ropes"), we store your user ID, the mountain, and the tag. Your votes contribute to public aggregate counts shown on mountain detail. You can remove your vote at any time by tapping the tag again.
- **Conditions vote** — when logging or editing a hike, you can optionally vote whether conditions were good for that month. This is stored as a boolean on your hike log (per mountain for chain hikes). Your vote contributes to the community "Best Months" heatmap shown on the mountain detail page. Individual votes are not attributed — only aggregate counts are displayed.
- **Hike reactions** — you can react to hike detail posts with emoji reactions (fire, heart, strong, mountain). Your user ID is stored with the reaction. Reactions are visible to anyone who can view the hike. You can remove your reaction at any time.
- **Hike cost** — optional expense amount (₱) stored on your hike log. Individual cost is visible only to you on your hike detail. Anonymous aggregate average cost per hike type (DIY/Tour/Hybrid) is shown on the mountain detail page.
- **Hike type** — optional classification (DIY/Tour/Hybrid) stored on your hike log. Anonymous aggregate type distribution is shown on the mountain detail page.

### Social Data
- **Friend connections** — when you send or accept a friend request, we store the connection between your account and the other user's account
- **Friend request status** — pending, accepted, or declined
- **Activity status** — a timestamp of when you last opened the app is stored to show "Online" or "Last seen X ago" to your friends and public profile viewers. This is reciprocal: you only see activity status for friends who have also enabled it. You can disable this in Settings. No location or device information is collected — only the timestamp.

### Push Notification Data
- **FCM push tokens** — Firebase Cloud Messaging tokens stored per device to deliver notifications
- **Notification preferences** — whether you have push notifications enabled (toggleable in Settings)
- **Notification records** — notification history including type (friend request, companion invite, feedback, submission review), timestamp, and read status. Automatically deleted after 30 days
- Push tokens are refreshed on every app launch and deleted when you sign out or disable push notifications in Settings
- Notifications are sent via Expo Push API and Firebase Cloud Messaging — no personal data is sent with the push delivery itself beyond the notification ID and deep-link

### Automatically Collected Data
- We do **not** collect device identifiers (except FCM tokens, which are cryptographic device tokens for delivery only), location data, analytics, or crash reports
- We do **not** use third-party tracking or advertising SDKs

## How We Use Your Information

Your data is used solely to provide the app's functionality:
- **Authentication** — to sign you in (via email or username) and secure your account
- **Hike logging** — to store and display your hiking history and statistics (hikes, mountains, provinces, regions)
- **Planning** — to save and show your planned hikes with countdowns
- **Trail reports, trail suggestions, and corrections** — to allow you to contribute mountain and trail data for community review
- **Profile** — to personalize your experience within the app, including theme preferences
- **Public profiles** — if you opt in, to display your username, display name, avatar, bio, hiking stats (hike count, mountains, provinces, regions), most visited mountains, and a province heatmap to other users. Your email, home region, and home province are **never** shown to other users.
- **User search** — to allow other users to find your profile by username or display name, only if you have enabled your public profile
- **Friend system** — to allow you to connect with other hikers. Friends can view each other's profiles even if not set to public. Friend connections are visible only to the two users involved.
- **Friend tagging** — you can only tag accepted friends as companions in a hike log. Their @username is stored as part of your hike data. A companion hike invite is sent to the tagged user. Non-friends cannot be tagged.
- **Companion photos** — when you are tagged as a companion, you can add up to 3 photos to your companion record of that hike. These photos are auto-resized and compressed before storage. Companion photos are visible to the hike owner and to you (the companion) on the hike detail screen. If you untag yourself, your companion hikes record and all associated photos are permanently deleted. If the hike owner removes you, your companion record is converted to a standalone hike log so you retain your record and photos of that hike with privacy set to Friends.
- **Per-hike privacy** — each hike and planned hike has a privacy setting (Only Me, Friends, Public). This controls who can see the hike when viewing your profile. Default is Friends.
- **Companion access exception** — when you tag a friend as a companion on a hike log, that friend can read the hike's content (mountain, date, photos, notes) regardless of your privacy setting, including "Only Me." This is necessary so your companions can see the hike they were on. Removing the companion (or having them untag themselves) revokes that access immediately.
- **Planned hike visibility** — your upcoming planned hikes may be visible to friends or the public based on each plan's privacy setting, so friends or other hikers can see where you're headed next
- **Hike photos** — photos you attach to hike logs are stored in Supabase Storage. Photos are auto-resized and compressed (1200px, 50% JPEG quality) before upload. Photos are publicly viewable if the hike's privacy is set to Public or Friends. Deleting a hike or removing a photo permanently removes the file from storage.
- **Packing checklists** — to help you prepare for planned hikes with a checklist of items to bring. Checklists are transferred to your completed hike record for reference.
- **Feedback** — feature requests and bug reports you submit are stored with your user ID, title, description, and submission date. Only you and the app administrator can view your submissions. The administrator may add response notes visible to you.
- **Fingerprint login** — if you enable fingerprint login, your biometric data is processed **entirely on your device** by the operating system. We never receive, transmit, or store your fingerprint or biometric data. A lock preference flag is stored securely on your device using the operating system's secure keychain (Android Keystore / iOS Keychain). If multiple accounts are used on the same device, each account's fingerprint preference is stored independently — enabling fingerprint on one account does not affect another.
- **Account suspension** — if an administrator determines that your account violates our terms, your account may be suspended. When suspended, you will see a notification upon opening the app and be signed out. You may contact us to appeal.
- **Email changes** — when you change your email, a one-time verification code is sent to the new email address to confirm the change.
- **Map sharing** — you can save or share your Summit Map as an image. Before saving or sharing, you can choose whether to display your display name or @username on the image. The image is generated locally on your device. If you choose to save it, the app requests access to your device's photo gallery. No data is sent to our servers during this process.
- **Bucket list** — to save mountains you want to climb. Your bucket list is private and only visible to you.
- **Community Stats** — the app displays aggregated, anonymous hiking statistics (most hiked mountains, popular provinces, monthly activity). No individual usernames or personal data are shown. All data is computed from aggregate hike counts.
- **Network status** — the app detects whether your device is online or offline to display a notification. No data is sent or collected during this check.
- **Push notifications** — when you have push notifications enabled, your FCM device token is stored and used to deliver notifications about friend requests, companion hikes, feedback responses, and submission reviews. Notifications are managed through Expo Push and Firebase Cloud Messaging services. The notification service only receives the notification type, content, and deep-link destination — your personal data is not transmitted in the push delivery itself.
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
| Profile bio | Yes | Yes | Never |
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
| Hikes set to "Only Me" | **Never** | **Never** | Tagged companions only |
| Planned hikes set to "Public" | Yes | Yes | Never |
| Planned hikes set to "Friends" | Never | Yes | Never |
| Planned hikes set to "Only Me" | **Never** | **Never** | **Never** |
| Submissions (reports, corrections, trails) | **Never** | **Never** | **Never** |
| Mountain tag votes | Public (aggregate counts) | Public (aggregate counts) | Public (aggregate counts) |
| Difficulty rating (on hike logs) | Follows hike privacy | Follows hike privacy | Follows hike privacy |
| Conditions vote (on hike logs) | Public (aggregate only) | Public (aggregate only) | Public (aggregate only) |
| Hike reactions | Follows hike privacy | Follows hike privacy | Follows hike privacy |
| Hike cost | **Only you** | **Only you** | **Only you** |
| Hike cost (aggregate per mountain) | Public (anonymous avg) | Public (anonymous avg) | Public (anonymous avg) |
| Hike type (DIY/Tour/Hybrid) | Public (aggregate only) | Public (aggregate only) | Public (aggregate only) |

You can toggle your public profile on or off at any time from the Profile edit screen. You can unfriend any user at any time.

## Data Storage and Security

- All data is stored on **Supabase** (hosted on AWS), a cloud database platform
- Data is transmitted over **HTTPS** (encrypted in transit)
- Data is stored in a **password-protected database** with Row Level Security (RLS) policies on all tables, ensuring users can only access their own data (unless they opt into a public profile or have an accepted friendship, in which case only the data described above is visible)
- Friend connections are protected by RLS — only the two users in a friendship can view, modify, or delete it
- Hike privacy is enforced at the database level — hikes set to "Only Me" or "Friends" are not accessible to unauthorized users even via direct database queries
- Role changes (e.g., user to admin) are protected by a database trigger — only administrators can modify user roles
- Profile photos are stored in **Supabase Storage** with access controls restricting uploads to the photo owner
- Usernames are validated for format (lowercase, 3-20 characters, alphanumeric and underscores) and uniqueness
- Search input is sanitized to prevent injection attacks (allowlist filtering and wildcard escaping)
- **Fuzzy search** — mountain names and usernames are indexed for typo-tolerant search using standard PostgreSQL trigram similarity. No additional data is collected for this; only the normalized text of the same fields you already provide (name, username) is indexed
- **Admin audit log** — every administrative action (role changes, bans, content-flag resolutions) is automatically recorded with actor, action, target, and timestamp, visible only to administrators. This is a safeguard against misuse of admin tools and is not used for any other purpose
- Public profile stats (hike counts, province/region counts) are computed server-side via secure database functions — other users cannot access your individual hike logs
- Theme preferences, welcome modal state, and fingerprint login preference are stored locally on your device via AsyncStorage and SecureStore
- **Biometric data** (fingerprint) is processed entirely by the device operating system and **never** transmitted to our servers
- The app contacts **Expo's update servers** (u.expo.dev) on launch to check for app updates. Only the app version and update channel are sent — no personal data, device identifiers, or location data is transmitted

## Third-Party Services

The app contacts the following third-party services during normal operation. None of these services receive your email, username, hike data, or any other personal information unless explicitly noted.

- **Supabase** (AWS-hosted) — primary database and file storage. All personal data is stored here under Row Level Security policies.
- **Expo Push + Firebase Cloud Messaging (FCM)** — push notification delivery. Receives your device's cryptographic push token and the notification payload (type, title, body, deep-link). No personal data is transmitted in the push payload.
- **Expo Updates (u.expo.dev)** — over-the-air update server, contacted on app launch. Receives only the app version and update channel.
- **Resend (summit-up.com domain)** — transactional email provider (email confirmation, password reset, email change OTP). Receives the recipient email address and template content only.
- **Open-Meteo (open-meteo.com)** — free weather API, contacted when you view a mountain's detail screen to fetch a 7-day forecast. Receives the mountain's latitude and longitude (the mountain's coordinates, not your device location). No account, user identifier, or personal data is sent. No API key required.
- **Ko-fi and GCash** — optional donation links under Settings. Tapping these opens the external app or browser. No user data is transmitted to Ko-fi or GCash by Summit Up; any data collected by those services is governed by their own privacy policies.
- **Sentry (sentry.io)** — automated error and crash monitoring. Receives the JavaScript error message, stack trace, breadcrumbs (last ~50 actions such as screen transitions, taps, and network calls), your user ID, app version, update ID, and OS/device class. Used only to detect and diagnose bugs. Sensitive strings (passwords, tokens, authorization headers) are scrubbed from breadcrumbs before sending. No hike data, photos, or personal messages are transmitted. Sentry retains events for 30 days on the free tier.

We do **not** use any analytics, advertising, crash reporting, fingerprinting, or tracking SDKs.

## Content Moderation

To keep the community safe and the app free from spam, certain free-text fields you write are automatically scanned at the database for patterns that commonly indicate solicitation or spam. The scanned fields are:

- **Profile bio** (up to 150 characters)
- **Hike notes** (up to 1000 characters)
- **Trail report name + description** (your submitted mountain proposals)

The scan looks for: URLs and naked domains, phone numbers (Philippine mobile format + common groupings), known spam keywords (e.g. "click here", "telegram", "whatsapp", "crypto", "bitcoin", "forex", "onlyfans", "buy now"), 5+ repeated characters, and 20+ character text that is ≥70% uppercase. The scan runs **on our database, not on our servers or on third parties** — no content leaves the database for moderation purposes.

**What happens when content is flagged:**

- The content is still saved; flagging does not block you from posting.
- A flag record is created containing: your user ID, the flagged text, the detected signals, and a timestamp. Duplicate flags (same text already pending for the same user) are skipped.
- The administrator (and any appointed reviewers) can see the flag in the admin Content Flags queue and take one of three actions:
  - **Dismiss** — no further action, flag marked resolved
  - **Clear content** — the flagged text is cleared (bio → null, notes → null, trail report description → null; the trail report name is preserved because admin still needs to review the submission). The original content is not retained after clearing.
  - **Ban** — sets your account as banned (same as a user-reported ban; you can contact us to appeal)
- You can see the flags on your own content via Supabase RLS — the admin UI for user-facing flag visibility is planned but not yet built.

**Admin audit trail.** Every administrator action on your account (role change, ban, flag resolution) is recorded in an admin audit log visible only to administrators. This provides accountability and allows us to investigate any misuse of administrative tools.

**Bypass note.** The client app warns you in advance when your input trips a signal, so legitimate content (e.g., a casual mention of Instagram or Telegram) can be reviewed by you before saving. The database-level scan is authoritative and cannot be bypassed by using a modified client or direct API calls.

## Data Sharing

We do **not** sell, rent, trade, or share your personal data with any third parties.

Your data is only accessible to:
- **You** — through the app
- **Your friends** — accepted friends can view your profile information as described in the Profile Visibility section, even if your profile is not set to public
- **Other users** — only if you enable your public profile, and only the information listed in the Profile Visibility section above
- **The developer and appointed reviewers** — for technical support, trail report review, trail suggestion review, and correction review only. Reviewers are trusted users appointed by the administrator who can view and act on submissions but cannot access your email, personal settings, or private data beyond what is included in the submission itself
- **Administrator visibility** — the app administrator can view all profiles (including private ones) and all hike/plan data regardless of privacy settings, for moderation purposes (e.g. investigating reports, verifying ban reasons). The administrator can also remove mountain entries when necessary (e.g. duplicate or invalid data), which permanently deletes the mountain and all associated hike logs, planned hikes, and trails

## Your Rights

You have the right to:
- **Access** your data through the app at any time
- **Edit** your profile, hike logs, planned hikes, username, and pending submissions (trail reports, corrections, trail suggestions)
- **Control visibility** — toggle your public profile on or off at any time
- **Manage friends** — send, accept, decline, or cancel friend requests; unfriend users at any time
- **Manage companion invites** — accept or reject companion hike invites; untag yourself from any companion hike at any time
- **Delete** individual hike logs and planned hikes
- **Change your password** at any time from Settings
- **Change your email** with OTP verification from Settings
- **Enable/disable fingerprint login** from Settings
- **Delete your entire account** — available in Settings > Delete Account, which permanently removes all your data including hike logs, planned hikes, checklists, trail reports, trail suggestions, corrections, friend connections, profile information, uploaded photos (avatars and hike photos), and your authentication credentials
- **Export your data** — available in Settings > Privacy > Export My Data. Downloads a JSON file containing your profile, hike logs, planned hikes, companion hikes, submissions, checklists, bucket list, feedback, friendships, reactions, tag votes, and trail condition updates. The file is generated on-demand and shared via your device's share sheet; it is not stored on our servers after generation. Rate-limited to once per 24 hours per account to prevent abuse

## Data Retention

- Your data is retained as long as your account exists and the app remains operational
- **Submission retention** — approved and rejected submissions (trail reports, corrections, trail suggestions) are automatically deleted 30 days after review. Pending submissions are automatically deleted after 90 days. Aggregate submission counts (approved/rejected totals) are preserved on your profile even after the original submissions are deleted
- If the app is discontinued, all user data will be permanently deleted from our servers within 90 days of shutdown, and users will be notified in advance
- When you delete your account (or if your account is permanently suspended), all associated data is permanently removed from our servers, including hike logs, photos, friend connections, checklists, and feedback
- We do not retain backups of deleted accounts
- Theme preferences and local state stored on your device are cleared when you uninstall the app

## Children's Privacy

Summit Up is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal data, please contact us so we can delete it.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected by the "Last updated" date at the top of this page. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact

If you have questions about this privacy policy or your data, contact:

**Ericson Balladares**
Email: ericsonballadares@gmail.com

## Summary

| What we collect | How we use it | Shared with other users? |
|---|---|---|
| Email address | Authentication, password recovery, login | Never |
| Username | Account identification, login | Public or friends |
| Display name | Profile display, avatar initials | Public or friends |
| Bio | Profile display | Public or friends |
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
| Activity status | Show online/last seen to friends | Friends and public viewers (if enabled) |
| Companion hike invites | Link tagged hikes to your account | Only between hike owner and tagged user |
| Companion photos | Photos you add to companion hikes (max 3, compressed) | Only between hike owner and tagged user |
| Hike privacy setting | Control per-hike visibility | N/A |
| Hike photos | Visual record of hikes (max 3, compressed) | Based on per-hike privacy setting |
| Packing checklists | Prepare for hikes, transferred to hike log | Never |
| Feedback submissions | Feature requests and bug reports | Never (only admin can view) |
| Fingerprint biometric | Processed on device only, never transmitted | Never |
| Theme preference | Stored locally on device only | Never |
| Bucket list | Save mountains to climb later | Never (private to you) |
| Public profile setting | Control your visibility to other users | N/A |
| FCM push tokens | Enable push notifications for friend requests, companion invites, and feedback | Stored on device and server (deleted on sign out or notification disable) |
| Conditions vote | Community best months heatmap (aggregate only) | Public (aggregate counts, not attributed) |
| Hike reactions | Social signal on hike detail | Visible to anyone who can view the hike |
| Hike cost | Personal expense tracking | Only visible to you (anonymous aggregate on mountain detail) |
| Hike type (DIY/Tour/Hybrid) | Context for cost data | Anonymous aggregate on mountain detail |
| Push notification records | Track notifications you receive, mark as read | Only visible to you, auto-deleted after 30 days |
| Mountain coordinates (for weather) | Fetch 7-day forecast from Open-Meteo when you view a mountain detail | Only mountain's lat/lng sent — never your device location |
| Content flags (auto-generated) | Flag bios, hike notes, and trail reports that match spam patterns for admin review | Visible only to you, admin, and reviewers; content cleared or dismissed — not retained after resolution |
| Admin audit log | Record admin actions (role changes, bans, flag resolutions) for accountability | Visible only to administrators |
| Device location (optional) | Compute distance to nearby mountains ("Mountains Near Me"). Only used when you open that screen; permission is requested in-context | Never sent to our servers — used locally on your device only |
| Error/crash reports (Sentry) | Diagnose bugs: JS stack traces, breadcrumbs, user ID, app version | Sent to Sentry.io only; sensitive fields are scrubbed |
