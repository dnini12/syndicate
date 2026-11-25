# Syndicate

One window for every Claude Code session: who's working, who's done, and who needs you.

## Download

**Get it from the Releases page: [https://github.com/dnini12/syndicate/releases](https://github.com/dnini12/syndicate/releases)**

Under the newest release, click the file for your computer:

| Your computer | File |
|---|---|
| Linux | `syndicate-linux-x86_64` |
| Windows | `syndicate-windows-x86_64.exe` |
| Mac (Apple silicon or Intel) | `syndicate-v<version>-macos.tar.gz` |
| Android phone | `syndicate-phone.apk` |

The browser downloads it right away. You don't need a token or a key.

## Install

Run the file you downloaded once. It installs itself to `~/.local/bin/syndicate`, sets itself up
to start when you log in, and opens.

- **Linux:** `chmod +x syndicate-linux-x86_64 && ./syndicate-linux-x86_64`
- **Windows:** double-click `syndicate-windows-x86_64.exe`. If SmartScreen warns you, choose
  *More info → Run anyway*.
- **Mac:** open the `.tar.gz`, then right-click `syndicate` → *Open* the first time (or run
  `xattr -d com.apple.quarantine syndicate` before you start it).
- **Phone:** open the APK on the phone and allow installs from that app. Then, on the computer:
  Settings → Phone → turn on Phone access, and pair.

After that, Syndicate updates itself from here. You don't need to download it again.

## Downloading from a terminal, or asking Claude to

The newest release is always at the same addresses, no sign-in needed:

```bash
curl -fLO https://github.com/dnini12/syndicate/releases/latest/download/syndicate-linux-x86_64
curl -fLO https://github.com/dnini12/syndicate/releases/latest/download/syndicate-windows-x86_64.exe
curl -fLO https://github.com/dnini12/syndicate/releases/latest/download/syndicate-phone.apk
```

The Mac file has the version in its name: copy its link from the Releases page.
