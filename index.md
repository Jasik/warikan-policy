
---
title: Privacy Policy
---

# Privacy Policy for WariKan

**Effective date:** July 6, 2026

WariKan ("the App," "we," "us") is developed by Vladimir Rogozhkin, an independent developer. This Privacy Policy explains what information the App collects, how it is used, and the choices you have. By using WariKan, you agree to the practices described here.

## 1. Information We Collect

### Account information
When you sign in, we (via our backend provider, Supabase) receive an identifier and, depending on the sign-in method you choose, limited profile information:

- **Sign in with Apple** — a unique user identifier, and your name/email only if you choose to share them (Apple lets you hide your email).
- **Sign in with Google** — a unique user identifier and basic profile info (name, email) provided by Google.
- **Guest mode** — an anonymous account with no personal identifiers, tied only to your device.

You also choose a **display name** shown to people you share trips with.

### Trip and expense data
To provide the core functionality of the App, we store the trips, expenses, splits, and settlements you create. This data is visible to the other members of a trip you invite or who invite you — that is the intended purpose of a shared expense-splitting app.

### Payment/settlement details (optional)
You may optionally add payment information (e.g., a bank transfer note or a link to a payment app) so trip-mates know how to reimburse you. This text is encrypted at rest on our servers. WariKan does not process payments itself — it only stores the reference information you type in, and the actual money transfer happens outside the App, directly between trip members.

### Purchases and subscriptions
If you support development or subscribe to Pro features, the purchase is processed by the Apple App Store or Google Play. We receive purchase/entitlement status (via RevenueCat) to unlock the relevant features — we do not receive or store your payment card details.

### Device and push notification data
If you enable notifications, we store a device push token (via Firebase Cloud Messaging) so we can notify you about activity on your trips (e.g., a new expense or settlement).

### Usage analytics
We use Firebase Analytics to understand aggregate feature usage (e.g., which screens or actions are used) so we can improve the App. This is limited to in-app event names and coarse usage/device data. We do not use this data for advertising, and WariKan does not use third-party advertising or cross-app tracking networks.

### Data stored on your device
WariKan is local-first: your trips and expenses are also stored on your device so the App works offline, and sync to our servers when you're connected.

## 2. How We Use Information

We use the information above to:

- provide and operate the core trip/expense-splitting functionality;
- sync your data across your devices and share it with the trip members you invite;
- send notifications you've enabled;
- unlock features you've purchased or unlocked as a supporter;
- diagnose problems and improve the App through aggregate usage analytics;
- maintain the security and integrity of the service.

We do not sell your personal information, and we do not share it with third parties for their own marketing purposes.

## 3. Who We Share Data With

- **Other trip members** — trip, expense, and settlement data is visible to the people you share a trip with, by design.
- **Supabase** — our backend provider, hosting the database, authentication, and file storage.
- **Google Firebase** — analytics and push notification delivery.
- **Apple / Google** — sign-in authentication providers.
- **RevenueCat, Apple App Store, Google Play** — purchase and subscription processing.

These providers act as service processors on our behalf and are only given the data needed to perform their function.

## 4. Data Retention

- Trip and expense data is retained while your account and trips are active.
- For free-tier accounts, detailed expense records for older, settled trips may be compressed/archived automatically after a grace period (currently 30 days) to reduce storage costs. Summary information is retained. You can keep a trip's full detail on-device via the app's "keep on device" option, or reopen an archived trip to restore full detail.
- Supporter/paid accounts are not subject to this automatic server-side archival and retain full detail.
- If you delete your account, we delete or anonymize your personal data, except where retention is required for legal, security, or fraud-prevention purposes, or where data has already become part of another user's shared trip records.

## 5. Data Security

We use industry-standard measures to protect your data, including encryption in transit (TLS) and at-rest encryption for sensitive fields such as your payment/settlement details. No method of transmission or storage is 100% secure, and we cannot guarantee absolute security.

## 6. Your Rights and Choices

Depending on where you live, you may have rights to access, correct, export, or delete your personal data, or to object to or restrict certain processing. You can manage most of this directly in the App (editing your profile, leaving or deleting trips, deleting your account) or by contacting us at the address below.

## 7. Children's Privacy

WariKan is not directed to children under 13 (or the relevant minimum age in your jurisdiction), and we do not knowingly collect personal information from them. If you believe a child has provided us with personal information, please contact us so we can remove it.

## 8. International Data Transfers

Our service providers (Supabase, Google Firebase, Apple, Google, RevenueCat) may process and store data in countries other than your own. Where required, we rely on appropriate safeguards for such transfers.

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be reflected by updating the "Effective date" above, and, where appropriate, through an in-app notice.

## 10. Contact Us

If you have questions about this Privacy Policy or how your data is handled, contact us at:

**appwarikan@gmail.com**
