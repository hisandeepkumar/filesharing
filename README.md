# filesharing
# 🚀 Ultra Fast File Transfer (Android ↔ iPhone Supported)

This is a peer-to-peer (P2P) file transfer web app that allows ultra-fast file sharing between devices, including Android and iPhone, without requiring a server. The app uses WebRTC via PeerJS to establish direct connections between users.

## ✨ Features
- 📲 **Cross-Platform Support** (Android, iPhone, Windows, Mac)
- 🚀 **Ultra-Fast Transfer** with direct P2P connection
- 🔑 **Secure & Private** (No third-party server storage)
- 📎 **Multiple File Transfer** support
- 📤 **Parallel Chunk Transfer** for large files
- 🖥️ **Simple, Clean UI** with modern design

## 📜 How It Works
1. Open the webpage on both the sender and receiver devices.
2. The sender shares their **Unique ID** with the receiver.
3. The receiver enters the sender’s **ID** and connects.
4. The sender selects files and clicks **Send**.
5. Files are sent directly to the receiver with real-time progress tracking.

## 📂 File Transfer Mechanism
- Files are **split into chunks** (default: 4MB per chunk).
- **Parallel transmission** (up to 40 chunks at a time).
- The receiver **reconstructs the file** after receiving all chunks.
- Uses **WebRTC’s DataChannel** for direct communication.

## 🛠️ Setup & Usage
### **Option 1: Use Directly**
- Open the `index.html` file in a web browser.
- No installation or setup required.

### **Option 2: Host on GitHub Pages**
1. Upload the project files to a GitHub repository.
2. Enable **GitHub Pages** from the repository settings.
3. Share the **GitHub Pages link** with users.

### **Option 3: Deploy on a Web Server**
- Upload the files to a web server (e.g., Vercel, Netlify).
- Ensure HTTPS is enabled for PeerJS WebRTC compatibility.

## 🔧 Technologies Used
- **HTML, CSS, JavaScript**
- **PeerJS (WebRTC-based P2P library)**
- **STUN Servers** (Google & Twilio) for NAT traversal

## 🎯 Future Improvements
- 📡 **QR Code Support** for easy device pairing
- 🔐 **End-to-End Encryption** for enhanced privacy
- 📊 **Transfer Speed Optimization** with adaptive chunking

## 🏆 License
This project is open-source and free to use under the **MIT License**.

---
🔗 **Made with ❤️ by Sandeep**
