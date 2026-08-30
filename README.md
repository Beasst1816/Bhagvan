# Bhagvan 🚀

Welcome to my portfolio! This repository showcases my best work and projects.

## About Me

I'm a passionate developer dedicated to building innovative solutions and learning new technologies. This repository is a collection of my finest projects and contributions.

## Featured Projects

- **🔐 MyLocker: Digital Gatepass System** - A Flutter-based digital gatepass and locker management system for students, with role-based access control (Student & Guard), Firebase-backed authentication, and QR-code verification. A web-based admin dashboard is currently in development.

- **🎮 CTRLFORGE: Zero-Latency Virtual Gamepad** - A cross-platform Flutter application that turns your mobile device into a low-latency virtual gamepad, emulating an Xbox 360 / DualShock 4 controller on Windows PC over Wi-Fi, Bluetooth, or USB.

- **⏭️ Skip: Stealth Ad Skipper** - A native Android utility that works as a fully functional calculator on the surface, while an Accessibility Service silently skips YouTube Music ads in the background.

## Skills & Technologies

- **Languages**: Dart, Java, Kotlin
- **Frontend & Mobile**: Flutter
- **Backend & APIs**: REST API Integration, Firebase (Cloud Firestore, Firebase Auth)
- **Tools & Platforms**: Git, GitHub, Odoo
- **Other**: Local Data Persistence (SharedPreferences), QR Code Integration, UI/UX Cloning

## Get In Touch

I'm always interested in connecting with recruiters, collaborators, and fellow developers. Feel free to reach out through any of these channels:

### Social Links & Professional Profiles

- **GitHub**: [github.com/Beasst1816](https://github.com/Beasst1816)
- **LinkedIn**: [linkedin.com](https://www.linkedin.com/in/raval-bhagvan-371677370)
- **Portfolio**: [beasst1816.github.io/myportfolio](https://beasst1816.github.io/myportfolio/)
- **Email**: ravalbhagvan.dev@gmail.com
- **Twitter**: [@beasst](https://x.com/beasst___?t=D9ES2MS_6Sfy5P1dV9nC_Q&s=09)

## Resume

Download my resume: [View Resume](./RESUME.md)

## Projects

### Project 1: 🔐 MyLocker: Digital Gatepass System
**Description**: A Flutter-based digital gatepass and locker management system built for students, replacing manual entry logs with a QR-code-based, role-based verification flow.

**Key Features**:
- Role-Based Access Control (RBAC) with **Student** and **Guard** roles
- Guard Scanner: guards scan a student's QR code to validate entry/exit
- Atomic Database Transactions using Firestore `WriteBatch` operations for reliable record consistency
- 🚧 Web-based Admin Dashboard for real-time monitoring — currently in development

**Tech Stack**:
- Frontend: Flutter (Dart) — Android
- Backend: Firebase (Cloud Firestore, Firebase Auth)

### Project 2: 🎮 CTRLFORGE: Zero-Latency Virtual Gamepad
**Description**: A high-performance virtual gamepad application that emulates an Xbox 360 / DualShock 4 controller on a Windows PC, with a fully customizable HUD and multi-protocol connectivity.

**Key Features**:
- Multi-Protocol Connectivity: Wi-Fi/TCP, Bluetooth (Classic SPP), and USB (ADB tunnel)
- Customizable HUD: drag-and-drop layout editor, adjustable accent colors, pressure-sensitive triggers, clickable thumbsticks, and an 8-way D-Pad
- Haptic feedback for tactile button responses
- Lightweight Windows companion app (system tray, no console window) that handles virtual controller emulation

**Tech Stack**:
- Mobile: Flutter (Dart), Provider (State Management)
- PC Host: C#, ViGEm Client (Xbox 360 / DualShock 4 emulation), WinForms system tray
- Networking: `dart:io` TCP/UDP sockets, `flutter_bluetooth_serial`, `usb_serial`

### Project 3: ⏭️ Skip: Stealth Ad Skipper
**Description**: A native Android utility that's a fully working calculator on the surface, while silently skipping YouTube Music ads in the background using Android's Accessibility Services.

**Key Features**:
- Stealth frontend: a genuine, functional calculator UI
- Automated backend: detects and taps "Skip Ad" buttons via the Accessibility API
- Lightweight (~5MB), fully local — no network permissions or tracking
- Distributed via GitHub Releases (not on the Play Store, due to its non-standard use of Accessibility Services)

**Tech Stack**: Kotlin, Android Accessibility API

## Let's Connect! 💼

I'm open to:
- Freelance opportunities
- Full-time positions
- Collaborations on interesting projects
- Mentoring and learning opportunities
