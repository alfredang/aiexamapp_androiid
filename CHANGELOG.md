# Changelog

All notable changes to the AI Exams Android app are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com).

## [1.0] — 2026-06-22 · versionCode 1

### Added
- Native Kotlin + Jetpack Compose (Material 3) client mirroring the iOS AI Exams app.
- Email/password sign-in & registration (token persisted via DataStore).
- Catalog browsing with search, and bundle detail with free teasers.
- "My Exams" library of purchased entitlements with Practice/Exam mode toggle.
- Exam runner: single/multi answers, Check (Practice) / Save (Exam), explanations,
  submit, and scored result summary.
- **About** tab (developer + version info) and **Feedback** tab that opens WhatsApp
  to +65 8866 6375 for feature requests and bug reports.
- Account management: website link, sign out, delete account.

### Play submission
- Track: **Closed testing — Alpha**. Testers: **All Testers** list. Country: **Singapore**.
- AAB signed by Google Play; targetSdk 35, minSdk 24.
- All 10 App content declarations completed; content rating Everyone; target audience 18+.
- Privacy policy: https://www.tertiaryinfotech.com/privacy
- Submitted for review on 2026-06-22.
- Notes: store-listing contact-email save required clicking the *visible* (not the
  hidden duplicate) Save button; Google's pre-check rejected the original
  `exams.tertiaryinfotech.com/privacy` URL (404) — switched to the company policy URL.
