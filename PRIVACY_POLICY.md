# Privacy Policy — Fake GPS Nell

**Last updated:** March 19, 2026

## Introduction

Fake GPS Nell ("the App") is developed by EgeaINC. This Privacy Policy explains how we handle information when you use our App.

## Data Collection

**We do not collect, store, or transmit any personal data.** The App operates entirely on your device.

### What the App does NOT do:
- Does not collect personal information (name, email, phone, etc.)
- Does not track your real location
- Does not use analytics or tracking services
- Does not display advertisements
- Does not share any data with third parties
- Does not use cookies or similar technologies

### Local Storage Only

The App stores the following data **locally on your device only**:
- **Favorites:** Saved locations you create (stored in local SQLite database)
- **Session history:** Records of your mock location sessions (stored in local SQLite database)
- **Preferences:** App settings like language, theme, and display options (stored in SharedPreferences)
- **Schedule profiles:** Auto-start configurations (stored locally)

This data never leaves your device and is deleted when you uninstall the App.

### Internet Usage

The App connects to the internet solely for:

1. **Geocoding (address search):** Queries are sent to [Nominatim/OpenStreetMap](https://nominatim.openstreetmap.org/) to convert addresses to coordinates. Nominatim's privacy policy applies to these requests.
2. **Route calculation:** Route data is fetched from [OSRM (Open Source Routing Machine)](https://router.project-osrm.org/) for trip simulation. No personal data is sent.
3. **In-app purchases:** Processed entirely through Google Play Billing. We do not have access to your payment information. Google's privacy policy applies.

### Permissions

The App requests the following Android permissions:
- **Location:** Required to set mock locations via Android's Developer Options. Your real location is never stored or transmitted.
- **Internet:** Required for address search, route calculation, and in-app purchases.
- **Foreground service:** Required to maintain mock location while the App runs in the background.

## Children's Privacy

The App does not knowingly collect any information from children under 13 years of age.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Privacy Policy, please open an issue at:
https://github.com/gabriel600r/fake-gps-nell-feedback/issues

---

*Fake GPS Nell is supervised by Nell, a 19-year-old Siamese cat.* 🐱
