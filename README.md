DataGuard — File Integrity Monitoring & Tamper Detection Tool 🔒

DataGuard is a powerful, cross-platform File Integrity Monitoring (FIM) solution designed to safeguard the security and integrity of your critical files in real-time. Featuring a sleek and intuitive GUI built with customtkinter, DataGuard offers both real-time and scheduled monitoring to keep your data safe from unauthorized changes.

✨ Key Features:

    🕵️‍♂️ Real-Time Monitoring: Instantly detects any changes to critical files and triggers alerts through GUI pop-ups, an in-app Alert Box, and email notifications for rapid response.

    📅 Scheduled Scans: Customize scan intervals based on file sensitivity:

        🔴 High: every 30 minutes

        🟠 Medium: every 24 hours

        🟢 Low: every week

    🔍 Comprehensive File Metadata Analysis: Tracks changes in SHA-256 hashes, file size, modification timestamps, and permission changes to detect tampering effectively.

    📜 Detailed Change Logging: Records all detected modifications with timestamps, supporting audits and forensic investigations.

    🚨 Robust Alert System: Provides clear visual alerts, maintains a history of all alerts in the Alert Box tab, and supports instant email notifications to keep you informed.

    👥 User Management: Enables each user to securely register their email for receiving personalized alerts, with encrypted storage of app credentials.

    🖥️ Modern and Responsive GUI: Crafted with customtkinter, featuring a clean dashboard, navigation bar, file status indicators, and interactive controls.

    💾 File Backup & Recovery: Automatically backs up modified files to aid recovery and forensic analysis.

🖥️ How to Install & Run DataGuard on Windows

    Download Python:
    Ensure Python 3.8 or higher is installed. Download it from python.org.

    Clone the Repository:

Open Command Prompt and run:

git clone https://github.com/YourUsername/DataGuard.git
cd DataGuard

Install Dependencies:

pip install -r requirements.txt

Run DataGuard:

    python main.py

🐧 How to Install & Run DataGuard on Linux

    Install Python 3.8+ and Git:
   
For Ubuntu/Debian:

sudo apt update
sudo apt install python3 python3-pip git

Clone the Repository:

git clone https://github.com/YourUsername/DataGuard.git
cd DataGuard

Install Dependencies:

pip3 install -r requirements.txt

Run DataGuard:

    python3 main.py

Feel free to replace YourUsername and repository URL with your actual GitHub repo link.
