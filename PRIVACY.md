# Privacy Policy — Life is a game

**Last updated: June 25, 2026**

This privacy policy describes how the **Life is a game** mobile app ("the App", "we", "our") handles your information. Plain English, no surprises.

---

## TL;DR

- Almost everything stays on your device. Your quests, levels, achievements, streaks, and goals are stored in Apple's SwiftData on your iPhone.
- If you enable iCloud sync, that same data syncs through your private iCloud account — we never see it.
- If you opt into the social features (Friends, Feed), your username and the posts you choose to share are stored on Supabase (our backend), accessible only to you and your friends.
- We use no third-party analytics or advertising SDKs.
- Screen Time data never leaves your device.
- You can delete your account and all related data at any time, from inside the App.

---

## 1. Data we collect

### 1.1 On-device only (default)

Stored locally on your iPhone via Apple SwiftData. We never see this data unless you explicitly share it through the social features below.

- **Player profile**: name (the one you typed during onboarding), age range, gender (optional), avatar customization, hunter class.
- **Progress**: XP, gold, level, attribute levels, completed quests, achievements, streak data, milestone status.
- **Quests**: titles, descriptions, schedules, completion history.
- **Dream Wall**: photos you add to milestones (stored only on-device, never uploaded).
- **Quest Capture (private)**: photos and captions you save privately are stored only on-device.
- **Focus session history**: dungeon completions, duration, rewards earned.
- **Distraction Shield selection**: the list of apps/categories you choose to block. Stored on-device only; the underlying app tokens are scrambled by iOS and cannot identify specific apps to anyone but you.
- **Onboarding answers**: your selected struggles, change goal, self-perception, ambition. Used only to personalize in-app copy. Never transmitted.

### 1.2 iCloud (only if you sign in to iCloud on your device)

When iCloud Drive is enabled on your iPhone, SwiftData automatically syncs the categories above to your private iCloud account via Apple's CloudKit. **We never see this data.** It belongs to you and Apple, encrypted in transit and at rest by Apple.

### 1.3 Social features (only if you opt in)

The social tab is disabled by default. If you choose to sign in with Apple to use Friends and the Feed, the following is sent to our backend (Supabase):

- **Sign in with Apple identifier**: an Apple-issued unique ID. We do **not** receive your email or full name unless you grant them at sign-in.
- **Username** (which you set yourself).
- **Friend connections**: who you've added as a friend.
- **Feed posts** you explicitly publish: text caption, optional photo, the quest stats you choose to attach (XP, gold, quests completed), timestamp.
- **Photo metadata**: stripped before upload — EXIF, GPS, and device data are removed by the app before any photo touches the network.

### 1.4 Purchases

Subscriptions are handled entirely by Apple via StoreKit 2. We receive only a verified flag that your subscription is active — no payment details, no card information, no Apple ID email.

### 1.5 Notifications

We send local notifications (the daily reminder) from your device only. No remote notifications, no third-party push provider.

---

## 2. Data we do NOT collect

- We do **not** use third-party analytics SDKs (no Firebase Analytics, Mixpanel, Amplitude, etc.).
- We do **not** use third-party advertising SDKs or trackers.
- We do **not** track you across other apps or websites.
- We do **not** sell, rent, or share your data with third parties.
- We do **not** receive any data about which apps your Distraction Shield blocks. Apple's Screen Time API returns opaque tokens that are unique per-app-install; we cannot reverse them to specific apps.

---

## 3. Permissions

The App requests these iOS permissions only when you use a feature that requires them:

- **Camera** — to attach a photo when you celebrate a quest completion.
- **Photo Library** — to attach an existing photo to a quest completion or profile.
- **Notifications** — for daily reminders to complete your quests.
- **Screen Time / Family Controls** — to block apps you select during a Focus Dungeon session. The blocking is enforced by iOS itself.
- **Sign in with Apple** — only when you opt into the social features.

You can revoke any of these at any time from iOS Settings.

---

## 4. Where data lives

| Data | Location |
|------|----------|
| Quests, progress, achievements, dream wall, private captures | Your iPhone (SwiftData) |
| Same data, if iCloud enabled | Your private Apple iCloud account |
| Profile + posts (social opt-in only) | Supabase (US-East region) |
| Subscription state | Apple StoreKit |
| Distraction Shield selection | Your iPhone only |

---

## 5. How long we keep your data

- **On-device data**: kept until you delete the App or reset it.
- **iCloud data**: kept until you delete it from iCloud.
- **Social data** (if opted in): kept until you delete your social account from within the App. Account deletion is a hard cascade — your profile, posts, photos, and friend connections are permanently removed from Supabase.

---

## 6. Your rights

- **Access**: everything we have about you is visible to you inside the App. Status tab → System Console.
- **Correction**: edit any profile field at any time inside the App.
- **Deletion**:
  - Delete the App from your iPhone to remove all on-device data.
  - For iCloud data: iPhone Settings → Apple ID → iCloud → Manage Storage → Life is a game → Delete Data.
  - For social data: open the App → Status tab → System Settings → Delete Social Account. This is a hard cascade delete and cannot be undone.
- **Portability**: contact us at the email below for an export of any data we hold on Supabase.

If you live in the EU/UK, you also have rights under GDPR to lodge a complaint with your data protection authority.

---

## 7. Children

The App is intended for users 13 years and older. We do not knowingly collect data from children under 13. If you believe a child under 13 has used the App, contact us and we will delete their data.

---

## 8. Changes to this policy

If we change anything material in this policy, we'll update the "Last updated" date and notify active users via an in-app message before the change takes effect.

---

## 9. Contact

If you have questions or want to exercise any of the rights above:

**Email**: olzhasb1406@gmail.com

We aim to respond within 7 days.
