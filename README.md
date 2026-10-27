# 📱 Chotu AI (ছোটু) — Your Autonomous Pocket Runner
> **"Sahkarmi on your Desktop, Chotu AI in your Pocket!"**

Chotu AI (ছোটু) is an autonomous, on-device Android AI agent. Instead of relying on closed APIs, Chotu operates your smartphone just like a human: it reads your screen via Android's native Accessibility Service and visually interacts with any application—tapping buttons, scrolling feeds, searching, and typing.

---

## 🌟 Key Capabilities

* 🍔 **Autonomous Food Ordering:** Say *"ছোটু, Zomato থেকে Arsalan-এর বিরিয়ানি কার্টে অ্যাড করে দাও"*. Chotu launches the app, searches the restaurant, selects the item, adds it to your cart, and brings you directly to the payment page.
* 🛡️ **Human-in-the-Loop Security:** Financial PINs and UPI OTPs are never touched by the AI. When the payment screen appears, Chotu hands control back to you: *"Please enter your UPI PIN to confirm!"*
* ⚡ **Blazing Fast & Free AI Models:**
  * **Google Gemini:** Free vision models via [Google AI Studio](https://aistudio.google.com).
  * **Groq Cloud:** Ultra-low latency inference via [Groq Console](https://console.groq.com) using Llama 3 / Qwen.
  * Also supports Claude 3.5 Sonnet, GPT-4o, and local Ollama instances.
* 🎈 **Draggable Floating Action Bubble:** A lightweight chat head overlay so you can summon Chotu on top of any active screen (WhatsApp, Zomato, Uber, Maps, etc.).
* 🔒 **Zero Root Required:** Runs 100% on standard unrooted Android devices (Android 8.0+ / API 26 to Android 15+).

---

## 🚀 Quick Start / Installation

### 1. Download the APK
Download the latest `Chotu-AI-*.apk` from the [Releases](https://github.com/ganguydhrubo/chotu-ai/releases) tab.

### 2. Grant Permissions
When you launch Chotu AI for the first time:
1. **Accessibility Permission:** Go to *Settings → Accessibility → Installed Apps → Turn ON Chotu AI*.
2. **Display Over Other Apps:** Allow Chotu to display the floating overlay bubble.

### 3. Add Free API Key
1. Open Chotu AI Settings.
2. Select **Google Gemini** or **Groq**.
3. Paste your free API key (keys are stored locally in Android's `EncryptedSharedPreferences`).

---

## 🏗️ Development & Building from Source

```bash
# Clone the repository
git clone https://github.com/ganguydhrubo/chotu-ai.git
cd chotu-ai

# Build debug APK
./gradlew assembleDebug

# Output APK location:
# app/build/outputs/apk/debug/app-debug.apk
```

---

## 📄 License
Licensed under the Apache License 2.0. Part of the Sahkarmi ecosystem.

Chotu AI is based on [OpenDroid](https://github.com/yashab-cyber/opendroid) by the OpenDroid contributors (Apache License 2.0). See [NOTICE](NOTICE).
