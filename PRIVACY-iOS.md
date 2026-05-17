# Privacy Policy

**Effective date:** May 17, 2026  **Last updated:** May 17, 2026

This privacy policy describes how Porte Du Luxe LLC ("we", "us", "our") collects, uses, and protects information when you use the **Paniero** iOS app (the "App"). A separate policy covers the Android version of Paniero.

## 1. Information we collect

We only collect information you provide directly through the App:

- **Account information.** When you create an account, we collect your email address and a password. Passwords are stored only as cryptographic hashes by Firebase Authentication; we cannot read them.
- **Grocery content.** The names of the stores and grocery items you create in the App.
- **Photos.** If you attach a photo to a grocery item, the photo is scaled and stored as part of that item.

We do **not** collect:

- Your location, contacts, phone number, or device identifiers
- Audio recordings (see "Voice input" below)
- Advertising identifiers, analytics, or any kind of usage telemetry

## 2. Permissions the App requests

| Permission | Why we request it |
|---|---|
| Camera | Only when you tap the camera button while adding or editing an item, to capture a photo. |
| Photo Library | Only when you tap the gallery button while adding or editing an item, to select an existing photo. We request read-only access; we do not save anything to your photo library. |
| Microphone | Only when you tap the microphone button to add items by voice. See "Voice input" below. |
| Speech Recognition | Required by iOS so that the audio captured by the microphone can be transcribed into text by Apple's Speech Recognition framework. See "Voice input" below. |

The App does not request your location, contacts, calendar, reminders, Bluetooth, local network, motion, or tracking permission, and does not include the App Tracking Transparency prompt.

### Voice input

When you tap the microphone button, the App hands the request off to Apple's Speech Recognition framework (`SFSpeechRecognizer`), which is part of iOS. That framework captures the audio and returns text to the App. Depending on your device and language, this transcription happens either entirely on-device or by sending the audio to Apple's servers for processing.

- The audio itself is **never received, retained, or transmitted by the App** — only the transcribed text is returned to us, and we only keep the resulting grocery item names you choose to save.
- How Apple handles any audio sent to its servers for transcription is governed by the Apple Privacy Policy at <https://www.apple.com/legal/privacy/>.

## 3. How we use your information

We use the information you provide solely to:

- Authenticate you when you sign in.
- Store and synchronize your grocery lists across devices signed into your account, including any Android devices running the Android version of Paniero.
- Display your stores, items, and photos back to you.

We do **not** use your information for advertising, profiling, behavioural analytics, or any other purpose. We do not sell, rent, or trade your information.

## 4. Where your data is stored

Your data is stored in:

- **Firebase Authentication** (operated by Google LLC) — your email address and a hash of your password.
- **Cloud Firestore** (operated by Google LLC) — your store names, item names, and base64-encoded photos, stored under a private path keyed to your unique user ID. Lists you share with another account are additionally readable by that account's user ID.

Google acts as our data processor for these services. Google's handling of this data is governed by the Google Cloud Platform Privacy Notice at <https://cloud.google.com/terms/cloud-privacy-notice>.

When you use voice input, Apple Inc. acts as a processor for the audio-to-text transcription described in Section 2 above.

We do not run our own servers and we do not share your data with any other third party.

## 5. Data retention and deletion

We retain your account and content for as long as your account exists. You can permanently delete your account and all of its data at any time from within the App: open the menu in the top-right corner of the Stores screen and choose **Delete Account**. This action:

- Removes every store, item, and photo you own from Cloud Firestore.
- Removes you from any lists that were shared with you.
- Deletes your Firebase Authentication record.

This deletion is immediate and cannot be reversed.

If for any reason you cannot use the in-app option, you can also email us at the address in Section 9 and we will delete your account on your behalf within 30 days.

## 6. Children's privacy

The App is not directed at children under 13, and we do not knowingly collect personal information from children. If you believe a child has created an account, please contact us and we will delete it.

## 7. Security

Data in transit between the App and Firebase is encrypted with TLS. Firebase stores your data in Google's data centers under the security controls described in Google's documentation. Passwords are never stored in plain text; Firebase Authentication stores cryptographic hashes only.

No system is perfectly secure. If we become aware of a breach affecting your data, we will notify you using the email address on your account.

## 8. Your rights

Depending on where you live, you may have specific legal rights regarding your data, including the right to access, correct, delete, or port it. You can exercise the deletion right at any time using the in-app **Delete Account** option (see Section 5). For other requests, contact us at the address below.

## 9. Contact

Porte Du Luxe LLC  <info@porteduluxe.com>

## 10. Changes to this policy

We may update this policy from time to time. When we do, we will update the "Last updated" date at the top of this document. Material changes will also be highlighted within the App.
