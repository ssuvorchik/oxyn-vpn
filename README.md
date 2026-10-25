# oxyn-vpn

A fast, private VPN with our own protocol. No activity logs, no card needed for the trial.

## Why Oxyn

- **Our own protocol** — built on the Noise framework. Traffic looks like a normal website, so it keeps working where regular VPNs get blocked.
- **No activity logs** — we never record which sites you visit, your traffic content, or DNS queries. We do keep minimal account data (login email, sign-in IP, device last-seen time) for account security and to enforce per-plan device limits — see the [Privacy Policy](https://oxyn.site/privacy) for the full, precise list.
- **Just an email** — no phone number, no card needed for the trial.
- **One account, every device** — Windows, Linux and Android.
- **15 days free** — try it, no card required.

## Download

Get the latest version from the [Releases](../../releases) page.

| Platform | File |
|---|---|
| Windows | `oxyn-vpn-windows-setup.exe` — installer |
| Linux | `oxyn-vpn-linux.bin` — after downloading: `chmod +x oxyn-vpn-linux.bin` |
| Android | `oxyn-vpn-android.apk` |

Always the latest version:

- https://github.com/ssuvorchik/oxyn-vpn/releases/latest/download/oxyn-vpn-android.apk
- https://github.com/ssuvorchik/oxyn-vpn/releases/latest/download/oxyn-vpn-windows-setup.exe
- https://github.com/ssuvorchik/oxyn-vpn/releases/latest/download/oxyn-vpn-linux.bin

### Android: "unknown sources" warning

Android blocks installs from outside Google Play by default. When you open the APK, tap **Settings** on the warning screen, then enable **Allow from this source** for your browser/file manager, and install again.

### Windows: SmartScreen warning

The installer isn't code-signed yet, so Windows SmartScreen may show "Windows protected your PC". Click **More info**, then **Run anyway** to continue.

### Verifying the download (SHA-256)

Compare the hash printed below each release against the file you downloaded.

- Windows (PowerShell): `certutil -hashfile oxyn-vpn-windows-setup.exe SHA256`
- Linux / macOS: `sha256sum oxyn-vpn-linux.bin`

## Get started

1. Download the app for your system.
2. Sign up with an email — 15 days free unlock instantly.
3. Pick a location and connect.

## Links

- Website: [oxyn.site](https://oxyn.site)
- Privacy Policy: [oxyn.site/privacy](https://oxyn.site/privacy)
- Support: [t.me/oxyn_support](https://t.me/oxyn_support)
- **Tor mirror:** `oxyn6nixejyfceylvdymsnajyo4bcbtbegbyahh54jr6gswncm2pdtyd.onion`
