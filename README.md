# 🤖 DroidScour - Android

**Android app for scanning hotspot-connected devices and capturing network traffic using Termux and root access.**

# 📱 DroidScour APK Installation Guide

This repository provides the latest APK releases of the **DroidScour** Android application.

## 🔽 How to Download and Install the App

1. Go to the [Releases](https://github.com/brendaschussler/DroidScour-Android-App/releases/latest) section of this repository.
2. Download the latest `.apk` file from the Assets list.
3. Open the downloaded file on your Android device.
4. When prompted, **allow installation from unknown sources**:
   - If it's your first time, Android will block the install and show a warning.
   - Tap "Settings" and enable **"Install unknown apps"** for your browser or file manager.
5. Proceed with the installation and open the app.

---

## 📱 SYSTEM REQUIREMENTS

- ✔ ROOT access on your device  
- ✔ Termux installed via **F-Droid** (not the Play Store)  
- ✔ Termux packages installed  

---

### 🔧 How to Install Termux via F-Droid

1. Download **F-Droid** from: [https://f-droid.org/](https://f-droid.org/)
2. Open F-Droid and search for **"Termux"**
3. Install **Termux**

> ⚠️ **DO NOT** install Termux from the Play Store. It is outdated and unsupported.

> 🚨️ IMPORTANT NOTICE:
>- Always maintain Termux updated through F-Droid
>- Updates often include critical bug fixes

---

### 📥 How to Install Required Termux Packages
Open Termux and run the command below:

```bash
pkg update -y && pkg upgrade -y && pkg install root-repo -y && pkg install iproute2 -y && pkg install tcpdump -y && pkg install coreutils -y
```


### 🧪 Testing Root Access in Termux
1. Open Termux  
2. Type `su` and press Enter  
3. If the prompt changes from `$` to `#`, root access is working.

## 📡 Packet Capture Instructions
- 👉 Devices must be connected to your phone via Hotspot (Wi-Fi tethering).
- ✔  Activate the hotspot on the cell phone running the app.
- ✔  Connect the devices you want to scan and capture packets from to this hotspot.

## 🔋 Battery Warning
- ⚠️ Keep your phone battery above 25% while capturing packets.
- Low power mode may kill app threads and interrupt the capture process.


## 📨 Support
 Contact support if you have any issues or questions: droidscour@gmail.com





