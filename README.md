# Milestones Support

Last updated: June 11, 2026

Milestones is a local-first iPhone app for tracking personal challenges, habits, streaks, daily checklist tasks, progress notes, optional Health-backed metrics, exports, encrypted iCloud backup, widgets, and privacy controls.

## Get Support

For help with Milestones, open a support request in the GitHub repository:

https://github.com/lukaluka/Milestones-App-Repo/issues

When reporting a problem, include:

- Device model.
- iOS version.
- Milestones app version and build number, if available.
- What you expected to happen.
- What actually happened.
- Steps that reproduce the issue.
- Whether the issue involves notifications, Health access, iCloud backup, widgets, exports, Privacy Lock, or challenge logging.

Please do not include private Health data, challenge notes, backup files, export files, screenshots with sensitive information, or other personal information in a public support request. If a screenshot is useful, hide or crop private details first.

## Quick Troubleshooting

### Challenge Logging

If today's challenge status looks wrong, open the challenge detail screen and check the daily log for the affected date. Milestones keeps each challenge independent, so schedule rules, skipped days, vacation pauses, weekly targets, and success targets can change whether a day is open, paused, logged, missed, or complete.

### Notifications

Milestones uses opt-in local notifications. If reminders are not appearing:

- Open Milestones and tap the bell button.
- Confirm reminders are enabled.
- Confirm the reminder time and notification style.
- Tap the iOS Notification Settings action and confirm notifications are allowed for Milestones.
- Reopen the app after changing notification settings so reminders can be recalculated.

Milestones does not use server push notifications.

### Health Access

Health-backed metrics and automations require iOS Health permission. If Health data is missing:

- Open the related metric or automation in Milestones and use the connect or refresh action.
- Open the iOS Health app settings and confirm Milestones has permission for the relevant data type.
- Confirm the Health data exists in Apple Health for the date range you expect.

Milestones reads selected Health data only after permission is granted. It does not write Health data.

### iCloud Backup

iCloud backup requires the device to be signed into iCloud with iCloud Drive available for the app. If backup is unavailable:

- Confirm iCloud Drive is enabled on the device.
- Confirm Milestones is allowed to use iCloud.
- Reopen Milestones and check the backup status again.

Milestones does not silently create a local fallback when iCloud backup is unavailable. Health-derived logs and Health-backed custom metric data are excluded from iCloud backups.

### Widgets

Milestones widgets use a minimal shared snapshot and may require opening the app to refresh after queued complete or missed actions. If widget content is hidden, check Privacy & Data settings and Privacy Lock settings in the app.

### Privacy Lock

Privacy Lock uses Face ID or device owner authentication as a screen lock. If unlock fails, use the on-screen Unlock button to retry, then check the device Face ID, passcode, or app permission settings.

## Privacy And Data

Milestones is designed to be local-first. The current app has no account system, no app-owned server sync, no public social feed, and no external analytics telemetry.

The Privacy & Data screen includes controls for widget visibility, private notification text, export redaction, iCloud backup scope, backup deletion, recovery payload deletion, notes and evidence deletion, full local data deletion, data export, and the in-app privacy policy.

Exports and share summaries are user initiated. Review export redaction settings before sharing files outside your device.

## Feature Availability

Some capabilities depend on device settings and Apple services:

- Notifications depend on iOS notification permission.
- Health features depend on Health permission and available Health records.
- iCloud backup depends on iCloud Drive and the app's iCloud container availability.
- Widgets depend on iOS widget support and the app's shared snapshot state.
- Face ID Privacy Lock depends on device authentication availability.

## App Store And Billing

For App Store purchase, refund, download, or family sharing issues, use Apple's App Store support and purchase history tools. App Store billing is handled by Apple, not by the Milestones support page.

## Paid Content, Subscriptions, And Feature Access

The current Milestones submission does not include a production paid subscription, paid content catalog, paid service account, external purchase flow, StoreKit purchase flow, receipt validation, restore-purchases flow, or subscription entitlement system.

### 1. Who will use paid content, subscriptions, features, and services in the app?

No public user uses paid content, subscriptions, paid features, or paid services in the current app submission because paid access is not active.

Milestones does include an administrator Free/Premium preview switch for development, review, and product validation. That switch simulates future Free and Premium behavior, but it is not a paid entitlement and is not connected to payment.

If production paid access is added in a later release, the intended users would be individual Milestones users who choose optional Premium challenge-tracking features for their own personal habits, routines, and streak-based commitments.

### 2. Where can users purchase content, subscriptions, features, and services that can be accessed in the app?

Nowhere in the current app submission. Milestones does not currently sell digital content, subscriptions, feature unlocks, or services in the app, on the web, or on another platform.

Milestones is not currently a reader app, multiplatform subscription service, enterprise service, person-to-person service marketplace, physical-goods app, or companion app to a paid web product. There is no external account purchase that unlocks app functionality.

If production paid digital features are added later, they should be sold through Apple's In-App Purchase system unless a future approved App Store entitlement or guideline-supported exception applies and is explicitly implemented.

### 3. What previously purchased content, subscriptions, features, and services can a user access in the app?

None in the current app submission. Milestones does not currently let users sign in to access previously purchased content, subscriptions, feature unlocks, service plans, web purchases, enterprise purchases, or purchases made on another platform.

There is no user account system and no server-side entitlement lookup in this release.

### 4. What paid content, subscriptions, or features are unlocked within the app that do not use In-App Purchase?

No paid content, paid subscriptions, or paid features are unlocked without In-App Purchase in the current app submission.

The in-app Free/Premium preview switch is an administrator preview tool, not a payment path. It is currently used to preview future tier behavior such as unlimited active challenges, premium templates, advanced schedules, advanced insights, Apple HealthKit automations, iCloud backup, CSV/PDF reports, Privacy Lock, and widget/watch companion surfaces. These previewed capabilities are not connected to any external purchase, account, subscription, license key, QR code, cryptocurrency wallet, or other non-In-App Purchase unlock mechanism.

## Support Request Template

Use this format when opening a support request:

```text
Issue summary:

Expected behavior:

Actual behavior:

Steps to reproduce:
1.
2.
3.

Device model:
iOS version:
App version/build:

Affected area:

Privacy notes:
Do not include private Health data, challenge notes, backup files, export files, or unredacted screenshots.
```
