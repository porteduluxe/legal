# Privacy Policy

**Effective date:** May 14, 2026
**Last updated:** May 14, 2026

This privacy policy describes how Porte Du Luxe LLC ("we", "us", "our") collects, uses, and protects information when you use the **My Grocery List** Android app (the "App").

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
| --- | --- |
| Internet | To sync your data with Firebase. |
| Camera | Only when you tap the camera button while adding or editing an item, to capture a photo. |
| Record audio | Only when you tap the microphone button to add items by voice. See below. |

### Voice input

When you tap the microphone button, the App hands the request off to Android's built-in speech-recognition service (typically Google Speech Services on most devices). That service captures the audio and returns text to the App. The audio itself is **never received, retained, or transmitted by the App** — only the transcribed text is. How the speech-recognition service handles the audio is governed by the provider of that service (most commonly described at https://policies.google.com/privacy).

## 3. How we use your information

We use the information you provide solely to:

- Authenticate you when you sign in.
- Store and synchronize your grocery lists across devices signed into your account.
- Display your stores, items, and photos back to you.

We do **not** use your information for advertising, profiling, behavioural analytics, or any other purpose. We do not sell, rent, or trade your information.

## 4. Where your data is stored

Your data is stored in:

- **Firebase Authentication** (operated by Google LLC) — your email address and a hash of your password.
- **Cloud Firestore** (operated by Google LLC) — your store names, item names, and base64-encoded photos, stored under a private path keyed to your unique user ID.

Google acts as our data processor for these services. Google's handling of this data is governed by the Google Cloud Platform Privacy Notice at https://cloud.google.com/terms/cloud-privacy-notice.

We do not run our own servers and we do not share your data with any other third party.

## 5. Data retention and deletion

We retain your account and content for as long as your account exists. You can permanently delete your account and all of its data at any time from within the App: open the overflow menu on the main screen and choose **Delete Account**. This action:

- Removes every store, item, and photo associated with your account from Cloud Firestore.
- Deletes your Firebase Authentication record.

This deletion is immediate and cannot be reversed.

If for any reason you cannot use the in-app option, you can also email us at the address in section 9 and we will delete your account on your behalf within 30 days.

## 6. Children's privacy

The App is not directed at children under 13, and we do not knowingly collect personal information from children. If you believe a child has created an account, please contact us and we will delete it.

## 7. Security

Data in transit between the App and Firebase is encrypted with TLS. Firebase stores your data in Google's data centers under the security controls described in Google's documentation. Passwords are never stored in plain text; Firebase Authentication stores cryptographic hashes only.

No system is perfectly secure. If we become aware of a breach affecting your data, we will notify you using the email address on your account.

## 8. Your rights

Depending on where you live, you may have specific legal rights regarding your data, including the right to access, correct, delete, or port it. You can exercise the deletion right at any time using the in-app **Delete Account** option (see section 5). For other requests, contact us at the address below.

## 9. Contact

Porte Du Luxe LLC
info@porteduluxe.com

## 10. Changes to this policy

We may update this policy from time to time. When we do, we will update the "Last updated" date at the top of this document. Material changes will also be highlighted within the App.
