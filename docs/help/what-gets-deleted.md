---
title: "What happens when you delete your account"
meta_description: "What's actually removed when you delete a Cloomba account — soft delete vs GDPR erasure, what to do beforehand, and what stays."
section: null
section_position: 0
position: 36
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

A companion to [Deleting your account](/help/delete-account) with the full breakdown of what gets removed and what stays.

---

### Two deletion modes

**Soft delete** (the default from the settings button): your account is deactivated, you're signed out, and a 30-day grace window starts. Sign back in within those 30 days and the account reactivates exactly as you left it. After 30 days, it's permanently erased.

**GDPR erasure**: immediate permanent anonymisation under your Article 17 right. Available on request via [contact us](/info/contact). Requires recent sign-in for security.

---

### What's removed in GDPR erasure

- Email and phone number on your `users` row — cleared
- Display name and bio — cleared
- Push notification tokens — invalidated
- Firebase Auth credentials — deleted

---

### What stays (for now)

- **Events you organised** are NOT auto-cancelled today. **Cancel them yourself before deleting** so registered guests are notified and refunded (paid events).
- **RSVPs you made** to other people's events stay in those organisers' guest lists, with your user row now showing as a deleted account.
- **Photos, videos, comments, and reactions** you posted stay in place until automated content erasure is wired up. Until then, request specific items via [contact us](/info/contact) if you need them removed sooner.
- **Username** is retained, so it can't be silently re-registered by someone else.
- **Payment records** are kept for the 10-year legal accounting period (see [Privacy Policy](/legal/privacy)).

---

### A clean exit checklist

1. Cancel any upcoming events you organised — issue refunds for paid tickets via Stripe.
2. Cancel your own RSVPs for upcoming events (optional but tidy).
3. Delete any individual photos / videos / comments you want gone.
4. Delete the account from **Account → Settings**.

---

### Coming later

Auto-cancellation of upcoming events on account deletion, and automated erasure of all uploaded content, are tracked as platform work. This page will be updated when they ship.
