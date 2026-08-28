# Privacy Policy — myLawha

**Last updated: 28/08/26**

myLawha ("the app", "we", "us") helps you memorize the Quran by writing it by
hand. We collect only what the app needs to work. This policy explains what we
process, why, who we share it with, and the control you have.

- **App:** myLawha
- **Provider:** Demko Corp
- **Contact:** demk0@proton.me

## The short version

- The app works **fully offline**. Your memorization data lives on your device.
- You can use myLawha **anonymously, forever** — no email, no name. If you stay
  anonymous, your data **never leaves your device**.
- We **never** sell your data, never show ads, and do **no** cross-app or
  cross-site tracking. The app triggers no App Tracking Transparency prompt.
- Your handwriting stays yours. We don't read it, analyse it, or train anything on it.
- You can delete your account and all server data from inside the app, at any time.

## What we process, and why

| Category | What | Why | Legal basis (GDPR) |
|---|---|---|---|
| Account | An account identifier; and, only if you create an account, your email address or the identifier Apple/Google returns | To sign you in and sync your progress across devices | Contract |
| Memorization data | Sessions (surah, page, verse range, completion %, error counts, quality score), your handwriting on the lawha, per-page and per-verse progress, review schedule, badges | The core function of the app; synced so a lost phone doesn't cost you your progress | Contract |
| Preferences | Language, notification setting, pen and background choice, memorization pace | To remember your settings across devices | Contract |
| Subscription | Trial start date, plan status, and a purchase identifier from RevenueCat | To run your free trial and unlock premium | Contract |
| Diagnostics | Crash reports: error details, device model, OS and app version | To find and fix crashes | Legitimate interest |
| Product analytics | A small set of anonymous usage events (e.g. onboarding finished, session completed, paywall shown), tied only to a random identifier | To understand which parts of the app work and which don't | Legitimate interest |

### What we never collect

Location · contacts · photos or camera · microphone · health data · advertising
identifiers · your address book · any biometric data. We do not build advertising
profiles and we do not track you across other apps or websites.

### A note on your handwriting

What you write on the lawha is stored as **vector stroke data** — the pen
movements — not as an image, and it is stored so that *you* can review your own
past sessions. It is transmitted only as part of your own account sync, and only
if you have created an account. No one at myLawha reviews it, and it is never
used to train machine-learning models.

### Notifications

Review reminders are scheduled **locally on your device**. We do not operate a
push server and we do not collect a push notification token. Turning reminders
off in Preferences (or in iOS Settings) stops them entirely.

### Using the app anonymously

On first launch the app creates an anonymous account so your data has somewhere
to live. An anonymous account has no email and no name — just a random
identifier — and **anonymous data is never synced to our servers**. It stays on
your device. If you later create an account, the same identifier is kept and
your existing progress is preserved and begins syncing.

Because anonymous data is local only, deleting the app deletes that data
permanently. We cannot recover it.

## Who we share data with

We do not sell your data or share it for advertising. We use these service
providers ("sub-processors"), each handling only what its function requires:

| Provider | What it handles | Where |
|---|---|---|
| Supabase | Authentication only (sign-in, account identity). No memorization data. | EU |
| Vetzner | Our API and database — your synced memorization data | EU |
| PostHog | Anonymous product analytics | United States |
| Sentry | Crash reports (configured to send no personal data) | EU |
| RevenueCat | Subscription status and purchase validation | United States |
| Apple | Payment processing for subscriptions; we never see your card details | Per Apple's policy |
| Quran audio CDN (`audio.qurancdn.com`) | Streams recitation audio; receives your IP address as any web request does | Per provider |

We may also disclose data if legally required, or to protect our rights or a
user's safety.

## International transfers

Some providers above are in the United States. Where personal data leaves the
EEA/UK, transfers rely on Standard Contractual Clauses or an equivalent
safeguard offered by that provider.

## How long we keep data

- **Account and memorization data:** until you delete your account. Progress is
  meant to last for years — we don't expire it.
- **Crash reports:** [90 days].
- **Analytics events:** [12 months].
- **Deleted records:** sync uses deletion markers, which are purged within
  [30 days].

## Your rights

You can access, correct, export, restrict, object to, or delete your data. Most
of this is immediate and in your hands:

- **Delete everything:** Preferences → Delete account. This erases your server
  data and your sign-in identity, then returns the app to a fresh anonymous
  state. It cannot be undone.
- **Turn off reminders:** Preferences, or iOS Settings.
- **Anything else** — including a copy of your data — write to demk0@proton.me
  and we'll respond within 30 days.

If you're in the EEA or UK you may also complain to your local data protection
authority.

## Children's privacy

myLawha is not directed at children under 16. We do not knowingly collect
data from them. If you believe a child has given us data, contact
demk0@proton.me and we'll delete it.

## Security

Traffic is encrypted in transit (HTTPS/TLS). Sign-in tokens are held in the iOS
Keychain. Our API authenticates every request, and access to production data is
limited to Demko Corp. No system is perfectly secure, but we treat
your data as if it were our own.

## Changes

If we materially change this policy we'll update the date above and, where the
change is significant, tell you in the app.

## Contact

Questions about this policy or your data: **demk0@proton.me**
