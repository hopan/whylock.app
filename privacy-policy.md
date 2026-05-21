# Privacy Policy — Whylock

**Effective date:** 2026-05-21

---

## Overview

Whylock is a mindfulness app that helps you unlock your phone with intention. We take your privacy seriously: **all data stays on your device**. We do not collect, transmit, or sell any personal information.

---

## Data We Collect

Whylock stores the following data **locally on your device only**:

| Data | Purpose |
|---|---|
| Unlock timestamp | Track when you unlock your phone |
| Unlock reason | The text you type after breathing |
| Unlock outcome | Whether you completed, skipped, or were blocked |
| Breathing duration preference | Your chosen breathing timer setting |
| Reminders | Personal notes you add in Settings |
| Trial install date | Determine your 30-day free trial period |
| Purchase status | Know whether you've unlocked the full app |

This data is stored in Room (SQLite) and SharedPreferences on your device. It is never uploaded to any server.

---

## Data We Do Not Collect

- We do not collect your name, email, or any account information
- We do not collect device identifiers or advertising IDs
- We do not use analytics or crash reporting services
- We do not use third-party SDKs that track you (except Google Play Billing — see below)
- We do not access your contacts, camera, microphone, or location

---

## Google Play Billing

Whylock offers a one-time $0.99 in-app purchase processed by Google Play. When you make a purchase:

- Payment is handled entirely by Google Play
- We receive only a confirmation that the purchase was successful
- We do not receive your payment details, name, or billing address
- Google's privacy policy applies to the payment transaction: [policies.google.com/privacy](https://policies.google.com/privacy)

---

## Permissions

| Permission | Why |
|---|---|
| `SYSTEM_ALERT_WINDOW` | Display the overlay on top of other apps |
| `FOREGROUND_SERVICE` | Keep the service running to detect unlocks |
| `RECEIVE_BOOT_COMPLETED` | Restart the service after device reboot |
| `READ_PHONE_STATE` | Auto-dismiss overlay during incoming calls |
| `POST_NOTIFICATIONS` | Show the persistent notification (required for foreground service) |
| `REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` | Prevent the system from killing the service |

None of these permissions are used to collect or transmit data.

---

## Data Retention

Your data lives in your app's private storage. It is automatically deleted when you uninstall Whylock. We have no access to it at any point.

---

## Children

Whylock is not directed at children under 13. We do not knowingly collect any information from children.

---

## Changes to This Policy

If we update this policy, we will update the effective date above. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## Contact

Questions or concerns? Reach us at:

**GitHub:** [github.com/hopan/whylock.app/issues](https://github.com/hopan/whylock.app/issues)
