# DataGaurd

DataGuard – File Integrity Monitoring and Tamper Detection Tool

DataGuard is a cross-platform File Integrity Monitoring (FIM) tool designed to ensure the security and integrity of sensitive files in real time. It provides a user-friendly GUI built with customtkinter and includes both real-time and scheduled monitoring functionalities. DataGuard continuously watches selected files for unauthorized changes using SHA-256 hashing, file metadata (size, modification time, permissions), and content similarity checks.
Key Features:

    Real-Time Monitoring: Instantly detects changes to critical files and triggers alerts via GUI message boxes, in-app Alert Box, and email notifications.

    Scheduled Scans: Supports customizable scan intervals based on file sensitivity (High – every 30 minutes, Medium – every 24 hours, Low – every week).

    File Metadata Analysis: Compares file hash, size, modification time, and permission changes to detect tampering.

    Change Logging: Logs all detected changes with timestamps for audit and forensic analysis.

    Alert System: Provides visual alerts, stores all alerts in an Alert Box tab, and supports email notifications for quick response.

    User Management: Allows each user to register their email for receiving alerts, with secure encrypted storage of app passwords.

    Modern GUI: Clean and responsive interface using customtkinter, with a dashboard, navigation bar, file status indicators, and interactive controls.

    File Backup & Recovery: Automatically backs up modified files to support recovery and investigation.

DataGuard is ideal for system administrators, security analysts, and developers seeking to monitor file integrity, prevent tampering, and maintain system trustworthiness in sensitive environments.
