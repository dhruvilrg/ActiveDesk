To force external links (like your website) to open in a new tab in Markdown, you can use HTML `<a>` tags with `target="_blank" rel="noopener noreferrer"` instead of standard Markdown syntax.

Here is the updated **`README.md`** file with the website link configured to open in a new tab:

```markdown
# ActiveDesk 🚀

> **Smart Workforce Monitoring Suite for Remote & Distributed Teams**

ActiveDesk bridges the trust gap between enterprise management and distributed teams with automated active time tracking, randomized multi-display captures, webcam verification, and instant payroll-ready attendance logs.[cite: 2]

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
  - [Real-Time Input Analytics](#real-time-input-analytics)
  - [Automated Screen & Camera Captures](#automated-screen--camera-captures)
  - [Leave, Attendance & Payroll Sync](#leave-attendance--payroll-sync)
  - [Admin Analytics & Reporting](#admin-analytics--reporting)
  - [Security & Infrastructure](#security--infrastructure)
- [Directory & Feature Matrix](#-directory--feature-matrix)
- [System Architecture](#️-system-architecture)
- [Getting Started](#️-getting-started)
- [Contact & Support](#-contact--support)

---

## 🔍 Overview

ActiveDesk acts as a virtual manager for distributed and work-from-home teams, providing transparent activity reports, leave approvals, and accurate attendance logs.[cite: 2] It focuses on aggregate activity levels and session snapshots rather than recording personal passwords or plain text, ensuring a privacy-preserving monitoring environment.[cite: 2]

---

## ✨ Key Features

### Real-Time Input Analytics
* **Keystroke & Mouse Analytics**: Calculates active vs. idle hours minute-by-minute.[cite: 2] Measures mouse movements, clicks, and keyboard strokes per minute without keylogging sensitive plain text.[cite: 2]
* **Background System Hooks**: System-level background hooks measure active engagement with minimal CPU and memory usage.[cite: 2]

### Automated Screen & Camera Captures
* **Multi-Monitor Screenshots**: Generates 10-minute activity sessions and captures 3 randomized screen grabs across all attached displays, providing full contextual proof of work.[cite: 2]
* **Webcam Presence Verification**: Configurable webcam access periodically takes snapshots to verify that the assigned employee is physically present at the workstation.[cite: 2]

### Leave, Attendance & Payroll Sync
* **Leave Management & Approval**: In-app leave module allows employees to submit requests directly.[cite: 2] Managers receive email alerts with one-click approve/reject actions.[cite: 2]
* **Payroll Automation**: Maps active hours, overtime, and approved leaves to calculate automated monthly payroll figures, removing manual calculation errors.[cite: 2]

### Admin Analytics & Reporting
* **Visual Dashboard**: Comprehensive visual timeline charts, screenshot galleries, and team comparison metrics available to managers and enterprise admins.[cite: 2]
* **Team Comparison**: Compare activity averages, active hours, and productivity levels across departments.[cite: 2]

### Security & Infrastructure
* **Privacy First**: Designed to track engagement without capturing passwords, confidential text inputs, or personal browsing data.[cite: 2]
* **High-Deliverability SMTP**: Uses local loopback SMTP (`127.0.0.1`) and DKIM domain alignment (`activedesk.in`) to ensure instant manager email alerts and zero delivery delays.[cite: 2]

---

## 📑 Directory & Feature Matrix

| Category | Module / Feature | Description |
|---|---|---|
| **Input Analytics** | Keystroke & Mouse Counter | Tracks clicks, movements, and keypresses per minute without plain-text logging.[cite: 2] |
| | Active vs. Idle Tracking | Differentiates active work from idle periods minute-by-minute.[cite: 2] |
| **Visual Proof** | Multi-Monitor Screenshots | Captures 3 randomized screenshots per 10-min session across all monitors.[cite: 2] |
| | Webcam Verification | Snapshot checks to confirm employee presence at the workstation.[cite: 2] |
| **HR & Payroll** | In-App Leave Requests | Employees apply for leave directly within the desktop application.[cite: 2] |
| | Payroll Sync | Converts logged active hours and leaves into monthly salary figures.[cite: 2] |
| **Reporting** | Visual Timeline & Gallery | Interactive screenshot galleries and team comparison dashboards for admins.[cite: 2] |

---

## 🛠️ System Architecture

```text
ActiveDesk Ecosystem
├── Desktop Application (Client)
│   ├── Input Activity Hooks (Keystrokes/Mouse)
│   ├── Multi-Monitor Screenshot Capture Engine
│   ├── Webcam Verification Module
│   └── In-App Leave Request Interface
│
├── Server & Backend Infrastructure
│   ├── SMTP Mail Dispatcher (127.0.0.1 / MailEnable)
│   ├── DKIM & Anti-Spam Headers (activedesk.in)
│   └── reCAPTCHA v2 Validation
│
└── Admin Web Dashboard
    ├── Activity Timeline & Screenshot Gallery
    ├── Manager Email Approval Routing
    └── Payroll & Attendance Log Exporter
```[cite: 2]

---

## ⚙️️ Getting Started

### Prerequisites

* **Client OS**: Windows 10/11 or macOS.[cite: 2]
* **Server**: Web server running PHP 8.0+ with local SMTP capabilities (e.g., MailEnable / IIS / Postfix).[cite: 2]
* **Domain Alignment**: Configured DKIM (`rsa-sha256`) and SPF records for reliable notification routing.[cite: 2]

### Installation & Client Setup

1. Download the latest ActiveDesk desktop application installer.[cite: 2]
2. Run the installer and sign in using your enterprise user credentials.[cite: 2]
3. Grant necessary desktop permissions for multi-monitor captures and optional webcam access.[cite: 2]
4. The application will run silently in the background tray during working hours.[cite: 2]

---

## 📬 Contact & Support

For enterprise setup, integration assistance, or support inquiries:[cite: 2]

* **Website**: <a href="https://activedesk.in" target="_blank" rel="noopener noreferrer">https://activedesk.in</a>
* **Email**: [support@activedesk.in](mailto:support@activedesk.in)

```
