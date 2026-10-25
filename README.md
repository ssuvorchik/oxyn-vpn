<p align="center">
  <img src="docs/logo.png" width="96" alt="Oxyn VPN logo">
</p>

<h1 align="center">Oxyn VPN</h1>

<p align="center">
  <b>A VPN with its own protocol — built for networks where WireGuard and OpenVPN get blocked.</b><br>
  Windows · Linux · Android — 15 days free, just an email, no card.
</p>

<p align="center">
  <a href="https://github.com/ssuvorchik/oxyn-vpn/releases/latest"><img src="https://img.shields.io/github/v/release/ssuvorchik/oxyn-vpn?label=latest&color=2dd4bf"></a>
  <a href="https://github.com/ssuvorchik/oxyn-vpn/releases"><img src="https://img.shields.io/github/downloads/ssuvorchik/oxyn-vpn/total?color=2dd4bf"></a>
  <a href="https://oxyn.site/en"><img src="https://img.shields.io/badge/website-oxyn.site-2dd4bf"></a>
</p>

## Download

| Platform | Download |
|---|---|
| **Windows** 10/11 | [oxyn-vpn-windows-setup.exe](https://github.com/ssuvorchik/oxyn-vpn/releases/latest/download/oxyn-vpn-windows-setup.exe) |
| **Android** 7+ | [oxyn-vpn-android.apk](https://github.com/ssuvorchik/oxyn-vpn/releases/latest/download/oxyn-vpn-android.apk) |
| **Linux** x64 | [oxyn-vpn-linux.bin](https://github.com/ssuvorchik/oxyn-vpn/releases/latest/download/oxyn-vpn-linux.bin) — then `chmod +x oxyn-vpn-linux.bin` |
| iPhone, iPad, Mac | via the [Happ](https://oxyn.site/en/apps) client with your Oxyn subscription link |

Sign up right inside the app — **15 days and 30 GB free**, no card.

## Why Oxyn

Most VPNs use OpenVPN or WireGuard. Both are easy to fingerprint with deep packet inspection (DPI),
so in many countries they connect for a minute — or not at all. → [Why VPNs get blocked](https://oxyn.site/en/vpn-blocked)

- **Own protocol** — built on the Noise framework (Noise_IK), not OpenVPN or WireGuard.
- **Looks like HTTPS** — runs over TCP 443 with a real-browser TLS fingerprint, designed to blend in with normal web traffic.
- **Kill switch** — if the tunnel drops, traffic never leaks outside the VPN.
- **Leak protection** — DNS, IPv6 and WebRTC leaks closed.
- **No VPN activity logs** — we don't record sites you visit, traffic or DNS queries. Details: [Privacy Policy](https://oxyn.site/privacy).
- **Just an email** — no phone number. Pay by card, crypto (USDT, BNB…) or Telegram Stars.
- **Servers in several countries**, all included in every plan.

## Where it helps

- [VPN blocked or not connecting?](https://oxyn.site/en/vpn-blocked)
- [Tor too slow or blocked? An alternative](https://oxyn.site/en/tor-alternative)
- [VPN for Iran](https://oxyn.site/en/vpn-iran)
- [Türkiye'de çalışan VPN](https://oxyn.site/tr/vpn-turkiye)

## Installing

**Android — "unknown sources":** when you open the APK, tap **Settings** on the warning, enable
**Allow from this source** for your browser/file manager, then install again.

**Windows — SmartScreen:** the installer isn't code-signed yet. Click **More info → Run anyway**.

**Verify the download (SHA-256):** each release lists hashes. Compare with
`certutil -hashfile <file> SHA256` (Windows) or `sha256sum <file>` (Linux/macOS).
More: [oxyn.site/safety](https://oxyn.site/safety)

## Links

- Website: [oxyn.site](https://oxyn.site/en)
- Support: [t.me/oxyn_support](https://t.me/oxyn_support)
- Tor mirror: `oxyn6nixejyfceylvdymsnajyo4bcbtbegbyahh54jr6gswncm2pdtyd.onion`

---

<sub>This repository hosts official Oxyn VPN builds and release notes. The apps are proprietary.</sub>
