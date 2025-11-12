# ⚡ LAN File Transfer App

A simple yet powerful *LAN-based file transfer web application* built using *Node.js (Express.js)* on the backend and *HTML, CSS, and JavaScript* on the frontend.  
This tool enables users to *send and receive files directly across devices* connected to the same *Local Area Network (LAN)* — *without the need for the internet*.

---

## Features

- ✅ Send files instantly between devices connected to the same LAN/Wi-Fi  
- ✅ Automatic IP detection for easy setup  
- ✅ Real-time upload progress bar for tracking file transfers  
- ✅ Download shared files instantly from the receiver’s panel  
- ✅ Cross-platform compatibility — works on Windows, macOS, and Linux  
- ✅ No third-party services — 100% local and private  

---

## Project Structure

📂 LAN-File-Transfer/
│
├── 📄 server.js # Node.js backend server
├── 📂 public/ # Frontend files
│ ├── index.html # Main user interface
│ ├── script.js # Frontend logic (sending & receiving)
│ ├── style.css # UI styling
│
├── 📂 uploads/ # Auto-created folder for received files
├── 📄 package.json # Node dependencies and metadata
└── 📄 README.md # Project documentation

## ⚙ Technologies Used

| Layer | Technology |
|-------|-------------|
| *Backend* | Node.js, Express.js, Multer, CORS |
| *Frontend* | HTML5, CSS3, JavaScript |
| *Storage* | Local File System (uploads/ directory) |

## Installation & Setup

Follow these steps to run the app locally on your LAN network 👇

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/lan-file-transfer.git
cd lan-file-transfer
2. Install Dependencies
Make sure you have Node.js (v14 or later) installed.
Then run:

npm install express multer cors
3. Start the Server
Run:

node server.js
You should see something like this:

 Server running on http://localhost:5000
 Access from other devices on LAN: http://<your-ip>:5000
