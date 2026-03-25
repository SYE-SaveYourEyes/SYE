# SYE Support Guide

**Version 1.0**
**Last updated: 25/03/26**

---

## Frequently Asked Questions

### Getting Started

**Why does SYE ask for Screen Time permission?**
SYE uses Apple’s Screen Time framework to block and pause apps. Without this permission, the app cannot shield apps or display interruption screens. The permission is granted through Apple’s system prompt and can be revoked anytime in:
Settings → Screen Time

**Does SYE work on all iPhones?**
SYE requires iOS 16 or later. Some Screen Time features may behave differently on older devices. For best performance, use the latest iOS version.

**Does SYE work on iPad?**
SYE is designed and tested for iPhone. iPad may work but is not officially supported in version 1.0.

**I granted Screen Time permission but still see the permission screen.**

* Fully close and reopen the app
* Check Settings → Screen Time to confirm permission is active
* If using Family Sharing, a parent/guardian may need to approve access

---

## Quick App Blocks (Function 2)

**Why do I need to select an app when I first tap a preset?**
Each preset slot must be linked manually due to Apple’s privacy requirements. This is a one-time setup per slot.

**I tapped a preset and got a blank screen.**
This is a known first-tap issue after app restart. Tap again and it will load correctly.

**My block isn’t working.**
Check:

* Screen Time permission is active
* The selected app is installed
* The block shows as active in the SYE card

If needed, reassign the preset using the customise (⊞) button.

**The block ended at the wrong time.**
Timers may vary by 1–5 minutes due to system limitations in Apple’s DeviceActivity framework.

**My presets disappeared after reinstalling.**
This is expected. Apple does not allow Screen Time tokens to be backed up. You must reassign presets.

**Can I block multiple apps?**
Yes. All five preset slots work independently.

**Can I cancel a block early?**
Yes. Tap **Cancel** next to the active block.

---

## Soft Interruptions (Function 3)

**What’s the difference from Quick App Blocks?**

* Quick App Blocks = hard block
* Soft Interruptions = optional pause screen

**I enabled it but nothing happens.**
Check:

* Toggle is ON
* At least one app is added
* Screen Time permission is active

Try toggling off/on and reopening the app.

**“Yes I need it” doesn’t open the app.**
Return to home screen and tap the app again.

**“Go back” does nothing.**
It returns you to home. The app remains blocked — this is intended.

**App feels slow with many tracked apps.**
Limit is 10 apps for performance. Remove extras if needed.

**Can I rename apps?**
Yes. Tap the app name to edit.

---

## Expected Phone Use

**Automatic mode is empty.**
Data may take up to 24 hours to populate. Use Manual mode meanwhile.

**Manual mode keyboard is slow.**
Tap directly into the field. Restart the app if needed.

**Projection seems too high.**
It reflects actual usage over a 61-year span. High usage = higher projection.

**Why 73 years?**
This is the global average life expectancy used for consistency.

---

## Notifications

**I didn’t receive a notification.**
Check:

* Notifications enabled in Settings → Notifications → SYE
* Threshold is set correctly
* Device was in use

Note: Alerts may be delayed up to 5 minutes.

**Notifications are greyed out.**
Permission has not been granted. Enable notifications in Settings.

---

## General

**Does SYE work after restart?**
Yes. Blocks and settings persist.

**Does SYE use data or battery?**
No internet usage. Battery impact is minimal.

**Found a bug or have a feature request?**
Contact: syecontact.app@gmail.com
Include device, iOS version, and issue details.
