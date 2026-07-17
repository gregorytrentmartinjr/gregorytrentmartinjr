# Gregory Martin | Linux Distribution Engineer 🌊

<p align="center">
  <a href="https://mainstreamos.org">
    <img src="https://raw.githubusercontent.com/MainstreamOS/dots-hyprland/mainstream/.github/assets/desktop.webp" alt="The Mainstream OS desktop" width="720" />
  </a>
</p>

<p align="center">
  <b>Building an Arch-based desktop anyone can live on — powerful under the hood, welcoming on the surface.</b><br>
  Creator &amp; maintainer of <b>Mainstream OS</b>: Arch, approachable. Hyprland, at home.
</p>

<p align="center">
  <a href="https://mainstreamos.org">Website</a> • <a href="https://github.com/MainstreamOS">Mainstream OS</a> • <a href="https://mainstreamos.org/download">Download</a>
</p>

---

### ⚡ Technical Arsenal

| Category | Tools & Technologies |
| :--- | :--- |
| **Desktop & Shell** | Hyprland, **Quickshell (QML)**, Material You theming, Wayland, gamescope |
| **Distro Engineering** | archiso, **Calamares**, Limine + snapper rollback, **GPG-signed pacman repo** |
| **Languages** | Bash, Python, **QML / JavaScript**, Rust, C++ |
| **Systems** | Arch Linux, systemd, Btrfs, LUKS, ntsync, per-GPU driver auto-config |
| **Release & Trust** | Signed ISOs, `SigLevel = Required`, no-AUR-at-install, install self-verification |

---

### 🚀 Featured Projects

#### [dots-hyprland](https://github.com/MainstreamOS/dots-hyprland) | *The desktop itself*
The Quickshell shell and Hyprland configuration at the heart of Mainstream OS.
- Bar, dock, overview, launcher, lock screen, and a full **GUI settings app** — never a config file.
- **Material You** theming generated from any wallpaper (image *or* video), propagated across GTK, Qt, and the terminal.
- SteamOS-style **Gaming Mode**: a session-level gamescope Big Picture switch, and a Console Mode install.

#### [archiso](https://github.com/MainstreamOS/archiso) | *The ISO builder*
Turns the desktop into a signed, installable operating system.
- **Calamares** installer with five install methods, full-disk encryption, and install-alongside dual-boot.
- **snapper + Limine** one-click rollback, with a Btrfs snapshot before every update.
- Signed ISO releases plus a **19-check post-install self-verification** that writes a health report.

#### [packages](https://github.com/MainstreamOS/packages) | *The signed [mainstream] repo*
A GPG-signed binary repository so nothing compiles on the user's machine.
- Prebuilt in CI from **public build scripts**, signed, and verified before anything installs.
- Replaces the AUR at install time — no compile-at-install roulette.

#### [mpris-hyprland](https://github.com/MainstreamOS/mpris-hyprland) | *Per-tab media bridge (Rust)*
A native-messaging MPRIS bridge for the bar's media widget.
- Publishes **one MPRIS player per browser tab** for Firefox/Zen and Chromium.
- Lightweight Rust host + a browser extension, packaged for the signed repo.

---
