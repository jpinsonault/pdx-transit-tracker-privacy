# PDX Transit Tracker — Privacy Policy

_Last updated: May 31, 2026_

## 1. Introduction

PDX Transit Tracker ("the app", "we", "us", or "our") is a mobile application that displays
real-time TriMet arrival information, nearby stops, and route maps for the Portland, Oregon
metropolitan area. This Privacy Policy explains what information the app collects, how it is
used, and the choices you have. It applies to the iOS and Android versions of the app
published under the developer account **Beagle Apps**.

By installing or using PDX Transit Tracker you agree to the practices described below. If you
do not agree, please uninstall the app.

## 2. Information We Collect

### 2.1 Information stored on your device only

The following data is stored locally in an on-device SQLite database. It never leaves your
device, is never transmitted to us or any third party, and is deleted when you uninstall
the app:

- Your favorite stops
- Your stop visit history (used to sort stops by most-visited and most-recent)
- App preferences (e.g. theme/appearance mode, notification reminder thresholds)
- The route you are currently tracking, if any

### 2.2 Information sent to TriMet

To show real-time arrivals, nearby stops, route configurations, vehicle positions, and detour
notices, the app makes requests to the public TriMet developer API (`developer.trimet.org`).
These requests may include:

- Your precise location (latitude/longitude), but **only** when you use the "Find Nearby
  Stops" feature and only while the app is in the foreground
- Stop IDs and route numbers you are viewing
- Your device's IP address (as with any HTTPS request)

TriMet's handling of these requests is governed by their own privacy policy:
<https://trimet.org/privacy/>.

### 2.3 Information sent to the map tile provider (OpenFreeMap)

Map tiles are served by OpenFreeMap (`tiles.openfreemap.org`), a free, no-API-key map
provider. When the app displays a map, your device requests the tiles for the area being
viewed. These requests reveal the geographic area you are viewing and your IP address but do
not include any account or identifying information from the app. See
<https://openfreemap.org/> for more information.

### 2.4 Information collected by Google AdMob (advertising)

The app displays advertisements served by Google AdMob (Google Mobile Ads SDK). When ads are
shown, the AdMob SDK and Google's ad servers may collect:

- Your device's advertising identifier (IDFA on iOS, Android Advertising ID on Android)
- Device information (model, OS version, language, time zone)
- Coarse location derived from your IP address
- Ad interactions (impressions, clicks)
- A small set of diagnostic/analytics signals provided by the bundled `app-measurement`
  component of Google Mobile Ads

The precise location collected for "Find Nearby Stops" is **not** shared with AdMob.

Google's use of this data is governed by Google's privacy policy
(<https://policies.google.com/privacy>) and Google's advertising technologies disclosure
(<https://policies.google.com/technologies/ads>).

## 3. Information We Do NOT Collect

- We do not require or collect a name, email address, phone number, or any other contact
  information.
- There is no user account, login, or profile.
- We do not access your contacts, photos, microphone, camera, calendars, health, or files.
- We do not track your location in the background; location is requested only while the
  app is open and only when you use a feature that needs it.
- We do not sell your personal information.

## 4. How We Use Information

- **Precise location** — only to query TriMet for stops near you and to display them on
  the map.
- **Stop IDs / route numbers** — to retrieve arrival times, route details, and detour
  information from TriMet.
- **Local on-device data** — to power the favorites list, recently-visited sorting,
  theme preference, and route tracking notifications.
- **Advertising data** — used by Google AdMob to deliver and measure advertisements
  that support continued development of the app.

## 5. Third-Party Services

The app communicates with the following third parties. Each operates under its own privacy
policy.

- **TriMet** (transit data) — <https://trimet.org/privacy/>
- **OpenFreeMap** (map tiles) — <https://openfreemap.org/>
- **Google AdMob / Google Mobile Ads** (advertising) —
  <https://policies.google.com/technologies/ads>
- **Apple App Store / Google Play** (app distribution and crash diagnostics provided by the
  platform) — governed by Apple and Google's respective privacy policies.

## 6. Your Consent Choices

- **Location permission.** The app asks for location only when you tap a feature that
  needs it (e.g. "Find Nearby Stops"). If you deny or revoke the permission, the rest of
  the app continues to work; only nearby-stop discovery is disabled. You can change this
  any time in your OS settings.
- **iOS App Tracking Transparency (ATT).** On iOS, when ads are first shown, the system
  prompts you to allow or deny tracking. If you deny, you will continue to see ads, but
  they will be non-personalized.
- **EU/UK/Switzerland consent.** If you are in the European Economic Area, the United
  Kingdom, or Switzerland, the app will show a Google-provided consent form (UMP) before
  initializing ads. You can choose between personalized ads, non-personalized ads, or to
  be reminded later. You can revisit this choice from the app's About screen at any time.

## 7. Data Retention and Deletion

We do not operate any server that stores your personal information. All app data
(favorites, history, preferences, tracked route) is stored only on your device and is
deleted when you uninstall the app or use your OS's "Clear app data" function.

To reset advertising identifiers, use your device's privacy settings:

- **iOS:** Settings → Privacy & Security → Tracking, and Settings → Privacy & Security →
  Apple Advertising.
- **Android:** Settings → Privacy → Ads → Reset / Delete advertising ID.

## 8. Your Privacy Rights

### 8.1 European Economic Area, United Kingdom, and Switzerland (GDPR / UK GDPR / FADP)

If you are located in the EEA, UK, or Switzerland, you have the following rights:

- Right of access to your personal data
- Right to rectification of inaccurate data
- Right to erasure ("right to be forgotten")
- Right to restriction of processing
- Right to data portability
- Right to object to processing
- Right to withdraw consent at any time
- Right to lodge a complaint with a supervisory authority

Because we do not maintain server-side accounts, most of these rights are exercised by
uninstalling the app (which deletes all local data) and by resetting your advertising
identifier in your OS settings. To exercise any right against data held by Google AdMob,
please use Google's privacy controls at
<https://myaccount.google.com/data-and-privacy>. For other questions, contact us using the
details below.

Legal basis: we rely on _consent_ for advertising-related processing and on the performance
of the requested service (showing you transit information) for sending your location to
TriMet when you use the nearby-stops feature.

### 8.2 California (CCPA / CPRA) and other US state privacy laws

Residents of California, Colorado, Connecticut, Oregon, Texas, Utah, Virginia, Montana, and
other states with comprehensive privacy laws have rights including:

- The right to know what personal information is collected and how it is used
- The right to delete personal information
- The right to correct inaccurate personal information
- The right to opt out of the "sale" or "sharing" of personal information for
  cross-context behavioral advertising
- The right to limit use of sensitive personal information
- The right to non-discrimination for exercising these rights

We do not sell personal information for money. However, the use of Google AdMob for
personalized advertising may qualify as "sharing" under the CPRA. You can opt out by:

- Declining the ATT prompt on iOS (results in non-personalized ads), or
- Selecting non-personalized ads in the consent form (where available), or
- Enabling Global Privacy Control (GPC) at the OS or browser level — we honor GPC signals
  where technically supported by the advertising SDK.

## 9. Children's Privacy

PDX Transit Tracker is not directed to children under 13 (or under 16 in jurisdictions
where that is the relevant age). We do not knowingly collect personal information from
children. The app configures Google AdMob to comply with the Children's Online Privacy
Protection Act (COPPA) where applicable. If you believe a child has provided personal
information through the app, please contact us and we will work with Google to remove it.

## 10. International Data Transfers

The app's network requests may be processed in the United States and in other countries
where Google operates its advertising infrastructure. TriMet data is processed in Oregon,
USA. By using the app, you understand that information may be transferred to and processed
in countries other than your own.

## 11. Security

All network requests made by the app are sent over HTTPS (TLS). On-device data is stored
in the app's sandboxed storage area, protected by the operating system's app isolation.
No method of electronic transmission or storage is 100% secure; we cannot guarantee
absolute security but we use commercially reasonable safeguards.

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last
updated" date at the top of this page and, where the changes are material, surface a
notice inside the app. Continued use of the app after an update constitutes acceptance of
the revised policy.

## 13. Contact

If you have any questions about this Privacy Policy or our privacy practices, please
contact:

- Email: <joe.pinsonault@gmail.com>
- Developer: Beagle Apps (Joe Pinsonault)
- Source / contact: <https://github.com/jpinsonault>

---

_PDX Transit Tracker is an independent application and is not affiliated with, endorsed by,
or sponsored by TriMet, Apple, Google, or OpenFreeMap._
