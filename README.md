# Dictate

Dictate is a small Mac app for dictating. Hold a key, say what you want to write, let go, and your words are typed wherever your cursor is. It uses Apple's speech engine, supports English and Spanish, and keeps your audio on your Mac by default.

This page only holds the downloads. It's a personal project, shared with friends.

## Download

**[Download the latest Dictate.dmg](https://github.com/ben-hagman/dictate-releases/releases/latest/download/Dictate.dmg)**

That link always points to the newest version. Older versions and release notes are under [Releases](https://github.com/ben-hagman/dictate-releases/releases).

## Needs

- A Mac with Apple silicon (M1 or newer).
- macOS 14 or newer. It works best on macOS 26, which has Apple's newest speech engine.

## Install

1. Open the downloaded `Dictate.dmg` and drag **Dictate** onto **Applications**.
2. Open Dictate from Applications. macOS will say it can't verify the app is free of malware, because it isn't notarized by Apple. That's expected for a hobby app. To allow it:
   1. Click **Done** on the warning (not Move to Trash).
   2. Open **System Settings → Privacy & Security**.
   3. Scroll to the **Security** section, find the line about Dictate being blocked, and click **Open Anyway**.
   4. Enter your Mac password and click **Open**.
3. Follow the welcome tour. It asks for four permissions: Microphone, Speech Recognition, Accessibility and Input Monitoring. After turning on Accessibility or Input Monitoring, quit Dictate and open it again once.

If Open Anyway doesn't show up, try opening Dictate again and go back to Privacy & Security. The button only appears for about an hour after a blocked attempt.

## Use

Click into any text box, hold the key shown on Dictate's home screen (Fn by default), talk, and let go. Settings are under **Dictate → Settings…** (or ⌘,).

## Update

Download the newest `Dictate.dmg` from the link above, quit Dictate, and drag the new one onto Applications, choosing **Replace**. Your settings and history are kept. You may need to repeat the Open Anyway step for the new version.

## Privacy

Dictate keeps your history and settings on your Mac. Recognition happens on your Mac unless you turn on Apple's server recognition in Settings, or add a Claude API key for rewrites. There's no tracking.
