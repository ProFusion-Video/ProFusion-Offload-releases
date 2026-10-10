# ProFusion Offload

Offload and verify camera cards on a Mac: copies to several drives at once, checksum-verified, ASC MHL, reports.

**Download:** the newest zip under [Releases](../../releases/latest). Needs an Apple Silicon Mac with macOS 14 or later.

## Installing (the app is not notarized yet)

1. Unzip and drag **ProFusion Offload** to your Applications folder.
2. Open it. macOS will say it can't verify the developer. Go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to ProFusion Offload, then confirm.
3. If that doesn't work, run this in Terminal once: `xattr -dr com.apple.quarantine "/Applications/ProFusion Offload.app"`
4. The first time it touches a card or network drive, macOS asks permission. Choose Allow.

After that, ProFusion Offload checks for updates by itself (Settings → Updates) and tells you when a new version is ready.

Feedback and crash reports: Help → Send Feedback… (you choose what is included).

This repository only hosts downloads and the update feed (`appcast.json`).
