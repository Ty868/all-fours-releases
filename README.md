# Trini All Fours — test builds

All Fours as it is played in Trinidad: four players, two partnerships, first
to fourteen. High, Low, Jack and Game.

<img width="" height="500" alt="s1" src="https://github.com/user-attachments/assets/74307847-51d3-43a6-ae94-fe829c505158" /> <br/>

**[Download the latest build from Releases →](https://github.com/Ty868/all-fours-releases/releases/latest)**

Android and Windows. This repository holds the builds only — the source lives
elsewhere.

Every file says what it is for: `-android.apk` for a phone,
`-windows-setup.exe` or `-windows-portable.exe` for a PC.

## Installing it on Android

Android will not install an APK from outside the Play Store until you let it,
so the first time takes one extra step.

1. Download the file ending `-android.apk` from the latest release.
2. Open it. Android will say it cannot install apps from this source.
3. Tap **Settings** on that prompt and allow your browser or file manager to
   install apps, then go back and open the APK again.
4. If Play Protect asks, choose **Install anyway**. It says that about every
   app it has not seen before, which includes every test build.

Android 7 or newer. If an older build is already installed, this one installs
over it and keeps your account and settings.

## Installing it on Windows

Two files, and you only need one of them.

- **`-windows-setup.exe`** installs it properly, with a Start menu entry. Pick
  this one unless you have a reason not to.
- **`-windows-portable.exe`** runs from wherever you put it and installs
  nothing. Good for a USB stick or a machine you are not allowed to install
  on.

Windows will show a blue **"Windows protected your PC"** box the first time,
because the build is not signed by a certificate it recognises. Click **More
info** and then **Run anyway**. Same warning Android gives for the APK, and
for the same reason.

64-bit Windows 10 or 11.

## What you can play

- **Play vs AI** — on your own, no account, no internet.
- **LAN Play** — four devices on the same WiFi and nothing else. One person
  opens a table, the others tap it. Works with no internet at all, and a
  Windows machine can be either the table or a player at someone else's.
- **Play Online** — needs an account and a connection. Tables, a lobby, chat,
  clans and a leaderboard.

Any seat nobody takes is played by the AI, so you can start a game with one
person or four.

Two things the Windows build does not do: push notifications, and the
microphone side of voice chat. Everything else is the same game.

## If something is wrong

Open an issue and say what you were doing when it happened, what you expected
and what you got instead. A screenshot settles most things on its own.

Worth including:

- The version from the release you installed.
- Which of the three modes you were in.
- Your phone and its Android version, or that you were on Windows.
