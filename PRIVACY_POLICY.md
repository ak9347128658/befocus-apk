# BeFocus Privacy Policy

**Effective date:** November 18, 2026

BeFocus ("the app", "we", "us") is a digital-wellbeing app for Android that helps you block distracting apps, short-video feeds (Reels/Shorts) and websites. This policy explains what information the app accesses, how it is used, and what is shared with third parties.

**In short:** BeFocus has no account system and no servers of its own. Your block lists, schedules, settings and usage statistics are stored **only on your device**. The only third party that receives data is **Google AdMob**, which shows ads in the app.

---

## 1. Information stored on your device only

The following data is created and stored locally on your phone (in the app's private storage). It is **never uploaded to us or anyone else**:

- The apps, websites and keywords you choose to block
- Your focus schedules, daily time limits and settings
- Per-app usage time that BeFocus tracks to enforce your limits and show your daily summary
- Unlock settings (such as the shared secret used for partner unlock codes, which are generated offline on the device)

This data is deleted when you clear the app's data or uninstall the app.

## 2. Accessibility Service

BeFocus uses Android's **Accessibility Service API** (`AccessibilityService`) to provide its core feature: blocking content you have chosen to block. With your explicit permission, the service:

- Detects which app is currently open, so it can show a focus screen when you open a blocked app
- Reads on-screen text such as the address bar of a browser, visible links, and text typed into search fields, so it can detect blocked websites, keywords, and Reels/Shorts screens
- If you turn on **Uninstall Protection**, detects the Settings screens that would uninstall or disable BeFocus and blocks them until you unlock

All of this processing happens **in real time on your device**. BeFocus does **not** record, store, log, upload or share the screen content or text it reads. The information is only compared against your own block list and then discarded. It is never used for advertising, and it is never sent to AdMob.

You can turn the Accessibility Service off at any time in **Settings → Accessibility → BeFocus**. If you do, blocking stops working.

## 3. Other permissions

| Permission | Why BeFocus uses it |
|---|---|
| Display over other apps | To show the focus/block screen on top of a blocked app |
| Device administrator (optional) | Only if you turn on Uninstall Protection, to prevent BeFocus from being uninstalled while protection is on. You can turn it off from inside BeFocus after unlocking. BeFocus does not use any other device-admin capability. |
| Notifications | To show your daily focus summary and blocking status |
| Run at startup | To restart blocking after your phone reboots |
| Close other apps' background processes | To close a blocked app when you are sent back to the home screen |
| Internet / Advertising ID | Used only by Google AdMob to load ads (see below) |

## 4. Advertising (Google AdMob)

BeFocus is free and is supported by ads from **Google AdMob**. To serve and measure ads, the Google Mobile Ads SDK may collect and process:

- Device identifiers, including the Android **Advertising ID**
- IP address and approximate location derived from it
- Ad interaction data (such as ad impressions and clicks)
- Diagnostic information (such as crash and performance data related to ads)

This data is collected and processed by Google under Google's own policies. BeFocus does not receive or store it.

- **Consent:** where required by law (for example in the EEA, UK and Switzerland), the app shows Google's consent form before loading ads. If you do not consent to personalised ads, only non-personalised ads are shown.
- **Opt out:** you can reset or delete your Advertising ID, or opt out of ad personalisation, in your device's **Settings → Google → Ads** (or **Settings → Privacy → Ads**).

Learn more:
- How Google uses information from apps that use its services: https://policies.google.com/technologies/partner-sites
- Google Privacy Policy: https://policies.google.com/privacy

## 5. Data sharing and selling

- We do **not** sell your personal data.
- We do **not** share any data with third parties, except the advertising data collected directly by Google AdMob as described above.
- Data collected by AdMob is transmitted over encrypted connections (HTTPS).

## 6. Data retention and deletion

All app data stays on your device. You can delete it at any time by clearing the app's storage (**Settings → Apps → BeFocus → Storage → Clear data**) or by uninstalling the app. Because BeFocus has no accounts or servers, we hold no data about you that could be deleted on request. For data processed by Google AdMob, see Google's privacy controls linked above.

## 7. Children

BeFocus is not directed at children under 13, and we do not knowingly collect personal information from children.

## 8. Changes to this policy

We may update this policy from time to time. Changes will be posted on this page with a new effective date.

## 9. Contact

If you have questions about this privacy policy, contact us at: **YOUR_CONTACT_EMAIL**
