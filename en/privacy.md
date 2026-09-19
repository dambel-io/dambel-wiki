# Privacy Policy

This page says what Dambel holds about you, who else touches it, and how long it stays. It describes what the app actually does today — where something is not yet built, it says so rather than promising it.

---

## What we collect

- **What you tell us when you sign up.** Your name, phone number, email and the profile details you fill in.
- **What you log.** Workouts, meals, water, sleep, weight and wake-ups — everything in [Tracker](tracker.md) — and the workout and diet plans you write or are given.
- **What you upload.** Your profile photo, gym photos, and trainer or gym licence documents.
- **Messages.** What you send in [Chat](chat.md), and what you send to the [AI assistant](ai-assistant.md).
- **Your location, only while you use the map.** The gym map asks for location when you open it. Refuse it and the map still works; you just search by area instead.
- **A notification token,** so [Notifications](notifications.md) can reach your device, along with the language you have chosen so they arrive in it.

## What we do not collect

Dambel carries no advertising identifier and no advertising or ad-network code. Nothing in the app builds a profile of you to sell, and nothing about you is shared with an advertiser. There is no crash-reporting SDK.

The app does measure how it is used, and the next section says exactly what that means and what it deliberately leaves out.

Dambel never asks for your bank card details. Payments happen on the gateway's own page, not inside the app. The bank account number you can save in the [Wallet](wallet.md) is for paying money out to you, and is only ever used for that.

## Usage analytics

To know which parts of Dambel are actually used, the app records what you do in it — not what you write in it.

What is recorded: which screen you opened, which button you tapped, and whether an action finished or failed. So: that you logged a weight, that a Premium purchase completed and which way you paid for it, that a deposit was started, that you subscribed to a gym. Each of these is tied to your account id, so we can tell one person's week from another's without knowing who either of them is.

What is not recorded, deliberately: the numbers you log about yourself. A weight entry records that you weighed yourself, never the kilograms; the same goes for what you eat, drink and how you sleep. A deposit does record how much it was for, because that is what tells us whether the payment step works — but never your bank account number, and never your card details, which the app never sees at all. Message text from [Chat](chat.md) and anything you send the [AI assistant](ai-assistant.md) are never part of this, and neither are your name, phone number or email address.

Some sessions are also recorded as a replay of the screen, so we can see where a screen is confusing rather than guessing. These recordings are masked: text and images are hidden by default, and [Chat](chat.md), everything in [Tracker](tracker.md), the [Wallet](wallet.md), your saved bank account, licence uploads and every sign-in form are covered on top of that, so what plays back in those places is a blank shape rather than your content. The recording captures where you tapped and how the layout moved, not what you read or wrote.

Both the events and the recordings are processed by PostHog on our behalf, and by nobody else.

## How we use it

To run the app, and for nothing else: to show you your data, to deliver a plan from your trainer to you, to place a gym on a map, to send you a notification you asked for, and to answer what you ask the assistant. Your health and fitness data is not used for advertising and is not sold.

## Who else processes it

Dambel uses these services, and each one sees only the part it needs:

| Service | What it is for | What it sees |
|---|---|---|
| **Zibal** | Payments and deposits | The payment itself |
| **SMS.ir** | Verification and account messages | Your phone number and the message |
| **Google Maps** | The gym map | Map requests, and your location while the map is open |
| **Firebase** | Push notifications | Your device's notification token |
| **OpenAI** | The AI assistant | What you send the assistant, and the context of the screen you asked from |
| **PostHog** | Usage analytics and masked session recordings | Which screens and actions you use, and a masked replay of the screen, tied to your account id |

Beyond these we share nothing, except where the law requires it.

## Chat is not end-to-end encrypted

Messages travel over an encrypted connection and are stored on Dambel's servers, which is what lets a conversation be delivered to a device that was offline and lets a reported message be reviewed. It also means Dambel is technically able to read them. Nothing in the app performs end-to-end encryption, and this page will not claim otherwise unless that changes.

## Your tracker, and what the assistant can reach

Nobody sees your tracker unless you share it. You create the share, you choose who and between which dates, and deleting it removes their access immediately — [Tracker](tracker.md) covers the mechanics.

The assistant is bound by exactly the same rule. It acts as you, so it can read your own tracker and any tracker that has been shared with you, and it cannot reach one that has not. There is no path by which asking the assistant gets at data you could not open yourself.

## How long we keep it

Your data is kept for as long as your account exists.

Dambel does not currently offer a way to delete an account — there is no control in the app and no process behind one. This is a gap rather than a policy, and when it is built this page will say how it works. In the meantime you can see and correct most of what we hold yourself, from [Profile](profile.md) and [Settings](settings.md), and you can write to support@dambel.io with a question about your data.

## Security

Dambel talks to its servers over HTTPS only; the app refuses plain-text connections outright. Your session token is held in the device's encrypted storage on Android. Licence documents are private to you and the review team.

## Changes and questions

This page can change. When it does, the updated version replaces it and the change is announced in the app. You can also read it inside the app, from the link on the registration screen.

Questions go to **support@dambel.io** — see [Contact Us](contact.md).

---

[← Previous: Terms and Conditions](terms.md) | [Next: Contact Us →](contact.md)
