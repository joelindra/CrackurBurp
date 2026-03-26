# Anonre Activation Console 🛡️

[![Java Version](https://img.shields.io/badge/Java-17%2B-orange.svg)](https://www.oracle.com/java/technologies/javase-downloads.html)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Burp Suite](https://img.shields.io/badge/Burp%20Suite-Professional-red.svg)](https://portswigger.net/burp)

A premium, modern, and high-performance **Burp Suite Professional Loader & License Manager**. Designed with a focus on aesthetics and ease of use, it automates the complex configuration required to run the latest versions of Burp Suite Pro.

---

## ✨ Key Features

- **💎 Premium Dark UI:** Built with a custom dark-themed interface using [FlatLaf](https://github.com/JFormDesigner/FlatLaf) for a state-of-the-art visual experience.
- **🚀 Automated Loader:** Automatically detects your Burp Suite JAR and configures the necessary `javaagent` and JVM arguments (supports Java 17, 21, and 22+).
- **🔑 Advanced Keygen:** Integrated license generator and activation response processor for seamless professional activation.
- **📥 Version Monitor:** Real-time checking for the latest Burp Suite releases with direct download integration.
- **📜 Script Generator:** One-click generation of `.bat` and `.vbs` startup scripts to launch Burp Suite in the background without needing the console.
- **🛠️ Smart Patches:** Includes specialized bytecode transformers (BigInteger patches and more) to ensure smooth operations across all environments.

---

## 📸 Preview & Demo

https://github.com/user-attachments/assets/ffc6397b-1ef2-488d-bc89-fb5b52ffb335

*Modern Dark UI with Accent Highlights*

---

## 🚀 How to Use

1.  **Preparation:**
    - Place the `burploader.jar` in the same directory as your Burp Suite Professional JAR (e.g., `burpsuite_pro_v2026.x.jar`).
    - Ensure you have **JDK 17 or newer** installed.

2.  **Activation:**
    - Run the jar: `java -jar burploader.jar`.
    - Enter your preferred name in the **LICENSE TO** field.
    - Copy the generated **LICENSE KEY** and paste it into Burp Suite.
    - Choose **Manual Activation** in Burp.
    - Copy the **Activation Request** from Burp and paste it into the **ACTIVATION REQUEST** field in the tool.
    - Copy the resulting **ACTIVATION RESPONSE** back into Burp Suite to complete activation.

3.  **Launch:**
    - Use the **Run** button to launch Burp directly.
    - Alternatively, click **Create Start Script** to generate `burp.bat` and a silent VBS launcher for future use.

---

## ⚙️ System Requirements

- **Runtime:** Java Development Kit (JDK) 17 / 21 / 22.
- **OS:** Windows / Linux / macOS.
- **Target:** Burp Suite Professional (Stable/Early Adopter).

---

## ⚠️ Disclaimer

This tool is for educational and research purposes only. Use it at your own risk. The author is not responsible for any misuse or damage caused by this application. Burp Suite is a product of PortSwigger Ltd.

---
