# Privacy Policy

**Nudge — Smart Watch Alarm**
Last updated: March 2, 2026

---

## Overview

Nudge is an alarm clock app for Wear OS smartwatches and Android phones. Your privacy matters — Nudge stores all personal data locally on your devices and does not operate any external servers. This policy explains what data is collected, how it is used, and what third-party services are involved.

---

## Data We Collect

### Alarm Data

Nudge stores your alarm configurations (times, days, vibration settings, ringtone preferences, dismiss challenge settings) locally on your device. This data is never sent to external servers.

### Sleep & Sensor Data

When you use the smart alarm feature, the watch app collects sensor data during sleep to determine the optimal wake-up moment:

- **Accelerometer** — movement and posture changes are processed in real time to estimate sleep phases. Raw sensor data is not stored; only aggregated metrics (movement intensity, immobility ratio) are saved per 30-second interval.
- **Heart rate** — heart rate samples (beats per minute) are collected to improve sleep quality scoring. Only the processed heart rate score and last measured value are stored per interval.

Sleep data is stored locally and automatically deleted after **30 days**. No location data, step counts, or other biometric data is collected.

### Subscription Data

If you purchase a supporter subscription, your purchase is processed through Google Play Billing. Nudge uses RevenueCat (see below) to verify your subscription status. No payment details (credit card numbers, billing address) are accessible to us.

---

## Device Synchronization

Nudge syncs data between your phone and watch using the **Google Play Services Data Layer API**. This is a direct, encrypted connection between your own paired devices — data does not pass through our servers.

Synced data includes: alarm settings, sleep tracking sessions, default preferences, custom alarm sounds, and supporter status.

---

## Third-Party Services

### Google AdMob (Advertising)

The phone app displays ads to non-supporters. Ads are served by Google AdMob, which may collect anonymous device identifiers and ad interaction data according to [Google's Privacy Policy](https://policies.google.com/privacy).

Ads are **not shown**:
- To supporters (ad-free)
- During your first app session
- On the watch app (never)
- During alarm configuration or dismiss screens

### Google User Messaging Platform (Consent)

For users in the EU/EEA, Nudge uses Google's User Messaging Platform (UMP) to request consent before showing personalized ads, in compliance with GDPR. You can change your consent choice at any time through the app settings.

### RevenueCat (Subscription Management)

Nudge uses [RevenueCat](https://www.revenuecat.com/privacy/) to manage supporter subscriptions. RevenueCat receives your anonymized app user ID and subscription status from Google Play to verify entitlements. No personal information beyond your subscription status is shared.

### Firebase / Google Analytics

The app includes Firebase as a technical dependency for AdMob. No custom analytics events are tracked. Standard Firebase data collection may include crash reports and basic app performance metrics according to [Firebase's Privacy Policy](https://firebase.google.com/support/privacy).

---

## Data Storage & Retention

| Data | Stored | Retention |
|---|---|---|
| Alarms | Locally on device | Until you delete them |
| Sleep tracking data | Locally on device | Automatically deleted after 30 days |
| Custom alarm sounds | Locally on device | Until you delete them |
| Subscription status | Locally on device + RevenueCat | Duration of subscription |
| Ad consent choice | Locally on device | Until you change it |

---

## Data We Do NOT Collect

- Location or GPS data
- Contacts, calendar, or messages
- Browsing history
- Account credentials or passwords
- Photos or media
- Step count data
- Biometric data beyond heart rate during sleep tracking

---

## Permissions

Nudge requests only permissions necessary for its core features:

- **Alarms & notifications** — to wake you up reliably
- **Body sensors** (watch only) — accelerometer and heart rate for smart alarm sleep tracking
- **Activity recognition** (watch only) — required by Android for body sensor access
- **Battery optimization exemption** — to ensure alarms fire on time
- **Do Not Disturb access** (watch only) — to sound alarms even in DND mode

All permissions are optional and requested in context. The app functions without granting sensor permissions (smart alarm features will be unavailable).

---

## Children's Privacy

Nudge is not directed at children under 13. We do not knowingly collect data from children.

---

## Changes to This Policy

We may update this policy from time to time. Changes will be posted on this page with an updated "Last updated" date.

---

## Contact

If you have questions about this privacy policy or your data, contact us at:

**nudge@hidi.rocks**

---

## Your Rights

Under GDPR and similar regulations, you have the right to access, correct, or delete your personal data. Since Nudge stores all data locally on your device, you can:

- View your data directly in the app
- Delete alarms, sleep data, and custom sounds through the app
- Uninstall the app to remove all locally stored data
- Manage your subscription through Google Play
- Change your ad consent preference through the app
