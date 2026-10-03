# Privacy Policy — Fake GPS Nell

**Last updated:** October 3, 2026

## Introduction

Fake GPS Nell ("the App") is developed by EgeaINC. This Privacy Policy explains how we handle information when you use our App.

## Your Data Stays on Your Device

**EgeaINC does not collect, store, or receive your data.** The App stores the following **locally on your device only**:
- **Favorites:** Saved locations you create (local SQLite database)
- **Session history:** Records of your mock location sessions (local SQLite database)
- **Schedule profiles:** Auto-start configurations (stored locally)
- **Preferences:** Settings like language and theme (SharedPreferences)

This data never leaves your device unless you export or share it yourself, and it is deleted when you uninstall the App.

## Location

The App uses your device's location to set mock locations through Android's Developer Options and to center the map. Your real location and the locations you simulate are never sent to EgeaINC and are never shared with the advertising service.

## Advertising

The free version of the App shows ads provided by **Google AdMob**. Users with Fake GPS Nell PRO do not see ads, and the App does not start the ads service for them.

To show and measure ads, Google AdMob may collect and process:
- The device's advertising ID
- Approximate location derived from the IP address
- Device and app information (model, operating system, language, app version)
- Ad interactions (impressions and taps)

This data is collected and processed by Google under its own policies, not by EgeaINC. Your favorites, history and simulated locations are never shared with AdMob.

- How Google uses information from apps that use its services: https://policies.google.com/technologies/partner-sites
- Google Privacy Policy: https://policies.google.com/privacy

**Your choices:**
- You can reset or delete your advertising ID, or opt out of personalized ads, in your device settings (Settings → Google → Ads, or Settings → Privacy → Ads, depending on the device).
- In the European Economic Area, the United Kingdom and Switzerland, the App asks for your consent before showing personalized ads, and you can change your choice at any time in Settings → Ad privacy.
- Buying Fake GPS Nell PRO (one-time purchase) removes all ads.

## Internet Usage

The App connects to the internet for:

1. **Address search:** Queries are sent to [Nominatim/OpenStreetMap](https://nominatim.openstreetmap.org/) to convert addresses to coordinates. Only the search text is sent. Nominatim's privacy policy applies.
2. **Route calculation:** Origin and destination coordinates are sent to [OSRM (Open Source Routing Machine)](https://router.project-osrm.org/) for trip simulation. No personal identifiers are sent.
3. **Map tiles:** Map images are loaded from OpenStreetMap tile servers.
4. **In-app purchases:** Processed entirely through Google Play Billing. We do not have access to your payment information. Google's privacy policy applies.
5. **Ads (free version only):** Loading ads from Google AdMob, as described above.

The App has no analytics of its own.

## Permissions

The App requests the following Android permissions:
- **Location:** Required to set mock locations via Android's Developer Options and to show where you are on the map. Your real location is never stored on our side or transmitted to us.
- **Foreground service:** Required to keep the mock location running while the App is in the background.
- **Notifications:** Shows the ongoing mock location status.
- **Exact alarms:** Used by scheduled profiles (PRO) to start at the set time.
- **Internet:** Required for address search, routes, map tiles, purchases and ads in the free version.
- **Advertising ID:** Used by Google AdMob to show ads in the free version.

## Children's Privacy

The App is not directed at children under 13. It does not knowingly collect information from children.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Privacy Policy, please open an issue at:
https://github.com/gabriel600r/fake-gps-nell-feedback/issues

---

*Fake GPS Nell is supervised by Nell, a 19-year-old Siamese cat.* 🐱
