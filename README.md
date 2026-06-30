<p align="center">
  <img src="assets/screenshots/ventoy.png" alt="Ventoy Hero" width="800">
</p>

# Ventoy

<p align="left">
  <img src="https://img.shields.io/badge/Ventoy-210111?style=flat-square" alt="Ventoy">
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white" alt="Arch Linux">
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" alt="Kali Linux">
  <img src="https://img.shields.io/badge/NixOS-5277C3?style=flat-square&logo=nixos&logoColor=white" alt="NixOS">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square" alt="Windows">
  <img src="https://img.shields.io/badge/SystemRescue-FF6600?style=flat-square&logo=linux&logoColor=white" alt="SystemRescue">
  <img src="https://img.shields.io/badge/Clonezilla-27ae60?style=flat-square&logo=linux&logoColor=white" alt="Clonezilla">
  <img src="https://img.shields.io/badge/GParted-orange?style=flat-square&logo=linux&logoColor=white" alt="GParted">
  <img src="https://img.shields.io/badge/MemTest86+-red?style=flat-square&logo=linux&logoColor=white" alt="MemTest86+">
  <img src="https://img.shields.io/badge/Tails-563D7C?style=flat-square&logo=tails&logoColor=white" alt="Tails">
</p>

Multiboot USB configuration for operating system installation, recovery, diagnostics, and maintenance workflows. The repository stores Ventoy configuration, theme assets, ISO layout conventions, and documentation for the included boot entries.

- [**Ventoy Official Website**](https://www.ventoy.net)
- [**Ventoy GitHub Repository**](https://github.com/ventoy/Ventoy)

## Project Structure

The repository is organized by asset type, ISO category, and Ventoy runtime configuration.

```text
/
├── assets/                 # Repository visual assets and logos
│   └── screenshots/        # Tool and OS environment captures
├── iso/                    # ISO storage directory
│   ├── rescue/             # Specialized recovery environments
│   └── tools/              # Utility-focused distributions
└── ventoy/                 # Ventoy core configuration
    └── ventoy/
        ├── ventoy.json      # Global settings, persistence, and aliases
        └── theme/           # Custom GRUB boot theme (Squid)
```

---

## Toolkit Content

### Primary Operating Systems

#### <img src="assets/arch.png" width="24"> Arch Linux
A minimal rolling-release Linux distribution.

- **ISO**: `iso/archlinux-x86_64.iso`
- **Documentation**: [Official Wiki](https://wiki.archlinux.org/)
- **Download**: [Official Release](https://archlinux.org/download/)

![Arch Linux Screenshot](assets/screenshots/arch.png)

---

#### <img src="assets/kali.png" width="24"> Kali Linux
A security-focused Linux distribution, configured with a dedicated persistence file.

- **ISO**: `iso/kali-linux-2025.4-live-amd64.iso`
- **Persistence**: `kali-persistence.dat`
- **Documentation**: [Official Docs](https://www.kali.org/docs/)
- **Download**: [Get Kali](https://www.kali.org/get-kali/)

![Kali Linux Screenshot](assets/screenshots/kali.png)

---

#### <img src="assets/nixos.png" width="24"> NixOS
A declarative Linux distribution built on the Nix package manager, offering reproducible builds and reliable rollbacks.

- **ISO**: `iso/nixos-graphical-26.05pre956934.cf59864ef8aa-x86_64-linux.iso`
- **Documentation**: [Official Manual](https://nixos.org/manual/)
- **Download**: [NixOS Download](https://nixos.org/download.html)

![NixOS Screenshot](assets/screenshots/nixos.png)

---

#### <img src="assets/windows.png" width="24"> Windows 11
Included for system deployment, recovery, and dual-boot configuration.

- **ISO**: `iso/Win11_25H2_French_x64_v2.iso`
- **Documentation**: [Official Docs](https://learn.microsoft.com/en-us/windows/)
- **Download**: [Windows 11 Download](https://www.microsoft.com/software-download/windows11)

![Windows 11 Screenshot](assets/screenshots/windows.png)

---

### Recovery & Specialized Tools

#### <img src="assets/windows-pe.png" width="24"> Hiren's BootCD PE
A Windows PE emergency boot environment with recovery and partitioning tools.

- **ISO**: `iso/HBCD_PE_x64.iso`
- **Download**: [HBCD Official Website](https://www.hirensbootcd.org/download/)

![Windows PE Screenshot](assets/screenshots/windows-pe.png)

---

#### <img src="assets/rescue.png" width="24"> SystemRescue
A Linux rescue environment for system repair and data recovery.

- **ISO**: `iso/rescue/systemrescue.iso`
- **Download**: [SystemRescue Download](https://www.system-rescue.org/Download/)

![SystemRescue Screenshot](assets/screenshots/rescue.png)

---

#### <img src="assets/clonezilla.png" width="24"> Clonezilla
A partition and disk imaging/cloning utility for backup and deployment workflows.

- **ISO**: `iso/tools/clonezilla-live-3.2.1-9-amd64.iso`
- **Download**: [Clonezilla Downloads](https://clonezilla.org/downloads.php/)

![Clonezilla Screenshot](assets/screenshots/clonezilla.png)

---

#### <img src="assets/gparted.png" width="24"> GParted
A graphical partition editor for resizing, copying, and moving disk partitions.

- **ISO**: `iso/tools/gparted-live-1.6.0-3-amd64.iso`
- **Download**: [GParted Download](https://gparted.org/download.php)

![GParted Screenshot](assets/screenshots/gparted.png)

---

#### <img src="assets/memtest.png" width="24"> MemTest86+
An open-source standalone memory tester for x86 and x86-64 architecture computers.

- **ISO**: `iso/tools/grub-memtest.iso`
- **Download**: [MemTest86+ Website](https://memtest.org/)

![MemTest86+ Screenshot](assets/screenshots/memtest.png)

---

#### <img src="assets/tails.png" width="24"> Tails
The Amnesic Incognito Live System. A security-focused Debian-based Linux distribution aimed at preserving privacy and anonymity.

- **ISO**: `iso/tools/tails-amd64-7.5.iso`
- **Documentation**: [Tails Documentation](https://tails.net/doc/)
- **Download**: [Install Tails](https://tails.net/install/)

![Tails Screenshot](assets/screenshots/tails.png)
