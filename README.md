<p align="center">
    <img src="https://github.com/user-attachments/assets/188c42f8-d249-4a72-b27a-e2b4f10a00a8" alt="Bitchat Logo" width="480">
</p>

# Bitchat

A decentralized, peer-to-peer messaging app for Android that works over Bluetooth mesh networks.
No internet required. No servers. No phone numbers. Just encrypted, direct communication.

> ⚠️ This is an independently maintained project and is under active development.
> Do not rely on it for sensitive communication until it has undergone proper security review.

---

## ✨ Features

* **Decentralized Mesh Network** – Peer discovery and multi-hop messaging over Bluetooth LE
* **End-to-End Encryption** – Secure communication using modern cryptographic standards
* **Offline Communication** – Works without internet using mesh networking
* **Channel-Based Chats** – Join topic-based group conversations
* **Private Messaging** – Direct encrypted messages between users
* **Store & Forward** – Messages delivered when offline users reconnect
* **No Registration** – No accounts, emails, or phone numbers required
* **Privacy First** – No tracking or persistent identifiers
* **Modern Android UI** – Built with Jetpack Compose and Material Design 3
* **Dark/Light Themes** – Clean and minimal interface
* **Battery Optimization** – Adaptive scanning and efficient power usage

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/aijazmirzza/Bitchat.git
cd Bitchat
```

---

### Build the Project

```bash
./gradlew build
```

---

### Install on Device

```bash
./gradlew installDebug
```

---

## 🛠️ Requirements

* Android Studio (latest recommended)
* Android SDK (API 26 or higher)
* Kotlin 1.8+
* Gradle 7.0+
* Android device with Bluetooth LE support

---

## 📱 Permissions

The app requires:

* Bluetooth (mesh communication)
* Location (required for BLE scanning on Android)
* Network (optional, for extended connectivity features)
* Notifications (message alerts)

---

## 💬 Usage

### Basic Commands

* `/j #channel` – Join or create a channel
* `/m @name message` – Send a private message
* `/w` – List online users
* `/channels` – Show discovered channels
* `/block @name` – Block a user
* `/unblock @name` – Unblock a user
* `/clear` – Clear chat
* `/pass [password]` – Set channel password
* `/transfer @name` – Transfer ownership
* `/save` – Toggle message retention

---

### Getting Started

1. Install the app on your Android device
2. Grant required permissions
3. Launch the app
4. Set your nickname
5. Join a channel using `/j #general`
6. Start chatting

---

## 🔐 Security & Privacy

* End-to-end encryption for private messages
* Secure key exchange mechanisms
* No centralized servers
* Messages stored only on device memory by default
* Optional message retention controlled by users

> ⚠️ Security has not been formally audited yet.

---

## ⚡ Performance

* Efficient message routing with multi-hop delivery
* Adaptive power usage based on battery level
* Optimized Bluetooth communication
* Lightweight architecture for fast performance

---

## 🏗️ Architecture

* Bluetooth LE mesh networking
* Asynchronous operations using Kotlin Coroutines
* Modern Android architecture (MVVM)
* Secure local storage for user preferences
* Modular and scalable codebase

---

## 🧪 Development

### Debug Build

```bash
./gradlew assembleDebug
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

### Release Build

```bash
./gradlew assembleRelease
```

---

## 🗺️ Roadmap

* Improve UI/UX experience
* Enhance mesh networking reliability
* Optimize battery performance
* Add new privacy and encryption features
* Expand scalability of the network

---

## 🤝 Contributing

Contributions are welcome!

You can help by:

* Reporting bugs
* Suggesting features
* Improving performance
* Enhancing UI/UX
* Writing documentation

---

## 🛟 Support

* Open an issue for bugs or errors
* Suggest improvements via discussions

---

## 📄 License

This project is released under the terms specified in the LICENSE file.

---

## ⚠️ Disclaimer

This project is for educational and experimental purposes.
Use at your own risk.
