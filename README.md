# 📟 TheServerBorn // System Initialized...

> **"Hey you, you're finally awake..." Welcome to the Terminal.**

I am an **IT Support Specialist** by day and a **Retro-Wasteland Engineer** by night. I hold the CompTIA **A+, Network+, Security+, and CySA+** certifications and spend my free time building software, homelab infrastructure, retro-inspired hardware, and systems that probably have more personality than they strictly need.

---

## 🛡️ Professional Credentials

- 🛠️ **CompTIA A+** | Systems & Support
- 🌐 **CompTIA Network+** | Infrastructure & Protocols
- 🔒 **CompTIA Security+** | Core Security Architecture
- 🎯 **CompTIA CySA+** | Cybersecurity Analysis & Incident Response

---

## 🕹️ Active Project: J-29 Interface Engine — v0.27

The **J-29 Interface Engine** is an open-source, Python-based interface and game-launching engine built around a simple idea:

**Modern hardware. Retro experience.**

What began as a terminal-style launcher for a custom retro-computer build has evolved into a modular interface engine capable of presenting local games, Steam titles, emulated software, and physical media through a unified fictional-computer experience.

The original **J-29 Terminal** remains the reference shell, while the underlying Engine is being designed to support alternate shells, themes, hardware builds, and community-created interfaces.

### 💻 Current Capabilities

- **Modular Engine + Shell Architecture**  
  Core functionality is separated from the user interface, allowing multiple shells to share the same game library, metadata, launch systems, and configuration.

- **J-29 Terminal Shell**  
  Fullscreen retro-terminal interface with animated startup, CRT-style presentation, keyboard navigation, command support, contextual controls, and configurable machine identity.

- **Unified Game Library**  
  Local programs, automatically discovered ROMs, and installed Steam games appear through the same J-29 library system.

- **Game Metadata**  
  Titles can carry platform, year, genre, developer, publisher, launch type, emulator, Steam ID, favorite state, and other metadata.

- **Favorites & Recent Games**  
  Persistent favorites and recently launched software are integrated directly into the interface.

- **Steam Integration**  
  J-29 automatically discovers installed Steam libraries and titles and launches them through the same interface used for other software.

- **Automatic ROM Discovery**  
  Configured ROM libraries are scanned automatically and organized by platform.

- **Emulator Integration**  
  J-29 can automatically route supported ROMs through configured emulator profiles, including RetroArch core selection and support for standalone emulators.

- **Physical Media Detection**  
  J-29 detects supported removable media including SD cards, USB storage, external drives, and other mounted media.

- **Physical Launch Keys**  
  Physical media does not need to contain the actual game. A tiny metadata file can represent an installed ROM or Steam title and launch it through J-29.

- **Self-Contained Game Media**  
  Physical media can alternatively contain both J-29 metadata and the actual software payload.

- **Physical Media Collections**  
  A single physical disk or card can represent an entire collection of games. Insert the media, open the collection, and launch multiple titles through the J-29 interface.

- **Dynamic Physical Media Interface**  
  Recognized media automatically appears in the main menu while mounted, including media already present when J-29 starts.

- **Cross-Platform Architecture**  
  Windows is the initial release target, while engine components are being written with Linux and macOS compatibility in mind.

### 💾 Physical Media Philosophy

One of J-29's defining features is treating physical media as an **interface**, rather than merely a storage device.

A floppy disk, SD card, USB drive, or other removable medium can represent software that actually lives somewhere else on the system.

For example:

```text
INSERT PHYSICAL MEDIA
        │
        ▼
   J-29 DETECTS IT
        │
        ▼
    HARVEST MOON
        │
        ▼
    LOAD GAME? [Y/N]
        │
        ▼
J-29 RESOLVES LIBRARY ENTRY
        │
        ▼
ROM / STEAM / LOCAL SOFTWARE
