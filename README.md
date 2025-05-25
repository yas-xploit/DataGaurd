DataGuard — File Integrity Monitoring & Tamper Detection Tool 🔒

DataGuard is a robust, cross-platform File Integrity Monitoring (FIM) tool designed to protect the security and integrity of your critical files in real-time. With a sleek and intuitive GUI built on customtkinter, DataGuard offers both real-time and scheduled monitoring, ensuring your sensitive data remains safe from unauthorized changes.
✨ Key Features

    🕵️‍♂️ Real-Time Monitoring: Immediately detects changes to important files and triggers alerts through GUI pop-ups, an in-app Alert Box, and email notifications for quick response.

    📅 Scheduled Scans: Configure scan intervals based on file sensitivity:

        🔴 High: every 30 minutes

        🟠 Medium: every 24 hours

        🟢 Low: every week

    🔍 File Metadata Analysis: Monitors SHA-256 hashes, file size, modification timestamps, and permission changes to detect tampering accurately.

    📜 Comprehensive Change Logging: Logs all changes with timestamps for audit trails and forensic investigations.

    🚨 Alert System: Provides clear visual alerts, maintains an Alert Box history, and sends instant email notifications.

    👥 User Management: Allows users to securely register emails to receive alerts, with encrypted password storage.

    🖥️ Modern & Responsive GUI: Clean dashboard, navigation bar, file status indicators, and interactive controls built with customtkinter.

    💾 File Backup & Recovery: Automatically backs up modified files to support recovery and forensic analysis.

🖥️ How to Install & Run DataGuard on Windows

    Install Python:

        Ensure Python 3.8 or higher is installed. Download from python.org.

    Clone the Repository:

git clone https://github.com/yourusername/DataGuard.git
cd DataGuard

Install Dependencies:

pip install -r requirements.txt

Run the Application:

    python launcher.py

🐧 How to Install & Run DataGuard on Linux

    Install Python:

        Make sure Python 3.8+ is installed. Use your package manager, for example:

sudo apt update
sudo apt install python3 python3-pip

Clone the Repository:

git clone https://github.com/yourusername/DataGuard.git
cd DataGuard

Install Dependencies:

pip3 install -r requirements.txt

Run the Application:

    python3 main.py

🔐 Why Choose DataGuard?

Whether you are a system administrator, security analyst, or developer, DataGuard helps you maintain trust in your systems by preventing file tampering, enabling swift detection, and simplifying forensic investigations — all through a modern, user-friendly interface.
