# GoBus – Mobile Exploratory Testing

## 📌 Project Overview

**GoBus Mobile Testing** is a team-based **Exploratory Testing project** focused on evaluating the GoBus application from a mobile user's perspective.

Instead of using predefined test cases, the team performed **Exploratory Testing** to explore the application, identify unexpected behavior, reproduce issues, and report defects.

The project was managed and documented using **Jira**.

---

# 🎯 Testing Scope

The exploratory testing focused on:

* Functional behavior
* User interaction
* Navigation
* UI behavior
* Responsive behavior
* Different screen sizes
* Mobile usability
* Input validation
* Unexpected application behavior

### Testing Approach

The team followed an **Exploratory Testing** approach where test design and test execution occurred simultaneously.

The testing process included:

1. Exploring the application
2. Identifying risk areas
3. Trying different user scenarios
4. Observing unexpected behavior
5. Reproducing defects
6. Reporting bugs
7. Retesting after fixes

**No predefined test case suite was created for this project.**

---

# 📱 Test Environments

Testing was performed using multiple environments to increase device and screen coverage.

### 1. Real Mobile Device

The application was tested on a **physical mobile device** to validate actual user interaction and behavior on real hardware.

Testing included:

* Touch interactions
* Navigation
* Screen rendering
* Input fields
* Application behavior
* Mobile usability

### 2. Android Studio Emulator

**Android Studio Emulator** was used to test the application on a virtual Android device.

It allowed the team to explore the application under different Android device configurations without relying only on physical devices.

### 3. Mobile Simulator – Responsive Testing Tool

The **Mobile Simulator – Responsive Testing Tool** Chrome Extension was used for responsive testing and mobile screen simulation.

It was used to explore:

* Different screen sizes
* Mobile layouts
* Device presets
* Portrait / Landscape views
* Responsive UI behavior

The extension provides multiple device presets for responsive testing.

---

# 🔎 Exploratory Testing

During exploratory testing, the team:

* Navigated through different application flows
* Explored different user scenarios
* Tried valid and invalid inputs
* Tested mobile interactions
* Checked different screen sizes
* Investigated unexpected behavior
* Reproduced discovered issues
* Reported defects
* Performed retesting when fixes were available

The testing was performed without a predefined test case suite, allowing the team to investigate the application dynamically based on observations and risks.

---

# 🐞 Defect Reporting

Discovered defects were documented and tracked using **Jira**.

Bug reports included relevant information such as:

* Bug Title
* Description
* Steps to Reproduce
* Expected Result
* Actual Result
* Test Environment
* Evidence
* Defect Status

The team also performed **retesting** after defect fixes.

---

# 🛠️ Tools & Technologies

| Tool                                       | Purpose                           |
| ------------------------------------------ | --------------------------------- |
| Real Mobile Device                         | Real-device testing               |
| Android Studio                             | Android Emulator / AVD testing    |
| Mobile Simulator – Responsive Testing Tool | Responsive & device simulation    |
| Jira                                       | Bug Tracking & Project Management |
| Chrome                                     | Responsive testing                |

---

# ⚙️ Tool Installation & Setup

## Android Studio

Android Studio was used to create and run Android Virtual Devices for mobile testing.

### Installation – Ubuntu

## Android Studio

Android Studio was used to create and run Android Virtual Devices (AVDs) for mobile testing.

### Installation – Ubuntu

Android Studio can be installed by downloading the Linux `.tar.gz` package from the official Android Developer website.

After downloading the package, open the Terminal and follow these steps.

### 1. Open the Downloads directory

```bash
cd ~/Downloads
```

This command moves to the directory where the Android Studio package was downloaded.

### 2. Extract the Android Studio package

Replace the filename with the actual downloaded file name:

```bash
tar -xzf android-studio-<version>-linux.tar.gz
```

**Command explanation:**

* `tar` → Tool used to work with compressed archives.
* `-x` → Extract the archive.
* `-z` → Handle gzip compression.
* `-f` → Specify the archive file.
* `android-studio-<version>-linux.tar.gz` → The downloaded Android Studio package.

### 3. Move Android Studio to `/opt`

```bash
sudo mv android-studio /opt/
```

**Command explanation:**

* `mv` → Moves a file or directory.
* `/opt/` → Common Linux directory for installing additional software.
* `sudo` → Runs the command with administrator privileges.

### 4. Open the Android Studio `bin` directory

```bash
cd /opt/android-studio/bin
```

The `bin` directory contains the files required to launch Android Studio.

### 5. Launch Android Studio

```bash
./studio.sh
```

This starts Android Studio and opens the Setup Wizard.

### 6. Install and configure the Android SDK

From Android Studio:

```text
More Actions
    ↓
SDK Manager
```

Make sure the required Android SDK components are installed.

### 7. Create an Android Virtual Device

From Android Studio:

```text
More Actions
    ↓
Virtual Device Manager
    ↓
Create Device
    ↓
Select Device
    ↓
Select Android System Image
    ↓
Download
    ↓
Next
    ↓
Finish
```

The Android Virtual Device (AVD) can then be started from **Device Manager** by clicking the **▶ Run** button.

### 8. Verify ADB installation

To check whether Android Debug Bridge (ADB) is available:

```bash
adb --version
```

### 9. Check connected Android devices

```bash
adb devices
```

Example output:

```text
List of devices attached
emulator-5554    device
```

If the emulator appears with the status `device`, it is successfully connected and ready for mobile testing.


---

## Mobile Simulator – Chrome Extension

The **Mobile Simulator – Responsive Testing Tool** was installed as a Chrome Extension.

### Installation

```text
Chrome Web Store
    ↓
Mobile Simulator - Responsive Testing Tool
    ↓
Add to Chrome
    ↓
Open Extension
    ↓
Select Device
    ↓
Start Responsive Testing
```

The extension provides multiple mobile device presets for responsive testing.

---

# 🐞 Jira – Project Management & Bug Tracking

The complete **GoBus Mobile Exploratory Testing project** was managed through Jira.

Jira was used for:

* Exploratory Testing activities
* Task Management
* Bug Reporting
* Bug Tracking
* Defect Status Tracking
* Team Collaboration
* Retesting

All project tasks, reported defects, and related testing activities are documented in the Jira project.

### Jira Project

`JIRA_PROJECT_LINK:``(https://fatmaaldardery.atlassian.net/jira/software/projects/GB/boards/233/backlog?atlOrigin=eyJpIjoiN2ZiYjVkOTFkMjY2NDAwODg2Njk0NmJiOTExNmI5MzYiLCJwIjoiaiJ9)`

> Jira access may require authorization.

---

# 📊 Project Summary

| Item               | Details              |
| ------------------ | -------------------- |
| Project            | GoBus Mobile Testing |
| Testing Type       | Exploratory Testing  |
| Test Approach      | Exploratory          |
| Test Cases         | Not predefined       |
| Real Device        | Yes                  |
| Android Emulator   | Yes                  |
| Mobile Simulator   | Yes                  |
| Bug Tracking       | Jira                 |
| Project Management | Jira                 |
| Project Type       | Team Project         |

---

# 📁 Repository Structure

```text
GoBus-Mobile-Exploratory-Testing/
│
├── README.md
│
└── .gitignore
```

The GitHub repository provides an overview and documentation of the project, while the complete testing activities, tasks, and defect reports are maintained in Jira.

---

# 👩‍💻 My Role

**QA / Mobile Tester**

* Participated in exploratory testing sessions
* Explored GoBus mobile user flows
* Tested the application on a real mobile device
* Tested using Android Studio Emulator
* Performed responsive testing using a mobile simulator
* Investigated unexpected application behavior
* Reproduced discovered defects
* Reported and tracked bugs using Jira
* Participated in retesting and defect verification
