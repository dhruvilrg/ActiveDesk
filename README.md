# ActiveDesk 🚀

> **Smart Workforce Monitoring Suite for Remote & Distributed Teams**

ActiveDesk bridges the trust gap between enterprise management and distributed teams with automated active time tracking, randomized multi-display captures, webcam verification, and instant payroll-ready attendance logs.

---

## 📋 Table of Contents

* [Overview](https://www.google.com/search?q=%23overview)
* [Key Features](https://www.google.com/search?q=%23key-features)
* [Real-Time Input Analytics](https://www.google.com/search?q=%23real-time-input-analytics)
* [Automated Screen & Camera Captures](https://www.google.com/search?q=%23automated-screen--camera-captures)
* [Leave, Attendance & Payroll Sync](https://www.google.com/search?q=%23leave-attendance--payroll-sync)
* [Admin Analytics & Reporting](https://www.google.com/search?q=%23admin-analytics--reporting)
* [Security & Infrastructure](https://www.google.com/search?q=%23security--infrastructure)


* [Directory & Feature Matrix](https://www.google.com/search?q=%23directory--feature-matrix)
* [System Architecture](https://www.google.com/search?q=%23system-architecture)
* [Getting Started](https://www.google.com/search?q=%23getting-started)
* [License & Support](https://www.google.com/search?q=%23license--support)

---

## 🔍 Overview

ActiveDesk acts as a virtual manager for distributed and work-from-home teams, providing transparent activity reports, leave approvals, and accurate attendance logs. It focuses on aggregate activity levels and session snapshots rather than recording personal passwords or plain text, ensuring a privacy-preserving monitoring environment.

---

## ✨ Key Features

### Real-Time Input Analytics

* **Keystroke & Mouse Analytics**: Calculates active vs. idle hours minute-by-minute. Measures mouse movements, clicks, and keyboard strokes per minute without keylogging sensitive plain text.
* **Background System Hooks**: System-level background hooks measure active engagement with minimal CPU and memory usage.

### Automated Screen & Camera Captures

* **Multi-Monitor Screenshots**: Generates 10-minute activity sessions and captures 3 randomized screen grabs across all attached displays, providing full contextual proof of work.
* **Webcam Presence Verification**: Configurable webcam access periodically takes snapshots to verify that the assigned employee is physically present at the workstation.

### Leave, Attendance & Payroll Sync

* **Leave Management & Approval**: In-app leave module allows employees to submit requests directly. Managers receive email alerts with one-click approve/reject actions.
* **Payroll Automation**: Maps active hours, overtime, and approved leaves to calculate automated monthly payroll figures, removing manual calculation errors.

### Admin Analytics & Reporting

* **Visual Dashboard**: Comprehensive visual timeline charts, screenshot galleries, and team comparison metrics available to managers and enterprise admins.
* **Team Comparison**: Compare activity averages, active hours, and productivity levels across departments.

### Security & Infrastructure

* **Privacy First**: Designed to track engagement without capturing passwords, confidential text inputs, or personal browsing data.
* **High-Deliverability SMTP**: Uses local loopback SMTP (`127.0.0.1`) and DKIM domain alignment (`activedesk.in`) to ensure instant manager email alerts and zero delivery delays.

---

## 📑 Directory & Feature Matrix

| Category | Module / Feature | Description |
| --- | --- | --- |
| **Input Analytics** | Keystroke & Mouse Counter | Tracks clicks, movements, and keypresses per minute without plain-text logging. |
|  | Active vs. Idle Tracking | Differentiates active work from idle periods minute-by-minute. |
| **Visual Proof** | Multi-Monitor Screenshots | Captures 3 randomized screenshots per 10-min session across all monitors. |
|  | Webcam Verification | Snapshot checks to confirm employee presence at the workstation. |
| **HR & Payroll** | In-App Leave Requests | Employees apply for leave directly within the desktop application. |
|  | Payroll Sync | Converts logged active hours and leaves into monthly salary figures. |
| **Reporting** | Visual Timeline & Gallery | Interactive screenshot galleries and team comparison dashboards for admins. |

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

```

---

## ⚙️ Getting Started

### Prerequisites

* **Client OS**: Windows 10/11 or macOS.
* **Server**: Web server running PHP 8.0+ with local SMTP capabilities (e.g., MailEnable / IIS / Postfix).
* **Domain Alignment**: Configured DKIM (`rsa-sha256`) and SPF records for reliable notification routing.

### Installation & Client Setup

1. Download the latest ActiveDesk desktop application installer.
2. Run the installer and sign in using your enterprise user credentials.
3. Grant necessary desktop permissions for multi-monitor captures and optional webcam access.
4. The application will run silently in the background tray during working hours.

---

## 📬 Contact & Support

For enterprise setup, integration assistance, or support inquiries:

* **Website**: [activedesk.in](https://activedesk.in)
* **Email**: support@activedesk.in
