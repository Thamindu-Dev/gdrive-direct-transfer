# 📂 Google Drive Direct Transfer Tool (Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Thamindu-Dev/gdrive-direct-transfer/blob/main/GDrive_Direct_Transfer_Tool.ipynb)

A powerful, Python-based tool designed to run on **Google Colab**. This tool allows you to copy large shared folders, files, and Google Workspace content directly to your "My Drive" using Google's servers.

**🚫 No Local Bandwidth Needed | 🚀 High Speed | ☁️ Cloud-to-Cloud**

## 🌟 Key Features

* **Smart Duplicate Detection:** Automatically skips files that already exist in the destination (saves time and storage).
* **Google Workspace Support:** Intelligently handles `.gdoc`, `.gsheet`, and `.gslides` files (prevents errors or skips them based on the selected method).
* **Auto-Shortcut Handling:** Simply paste a shared link; the script creates a temporary shortcut, copies data, and cleans up automatically.
* **Progress Tracking:** Real-time progress bars with file counts and size calculation.
* **Resumable:** If the process stops, run it again—it picks up exactly where it left off.

## 🛠️ Included Methods

This notebook contains 3 different methods to suit your needs:

### 🔹 Method 1: Direct Copy (Standard)
Best for copying standard files (PDF, MP4, Zip) from a shortcut you already created.
* *Features:* Progress bar, Size calculator, Duplicate skip.

### 🔹 Method 2: Link-to-Copy (All-in-One)
The easiest method!
1.  Paste the **Shared Link**.
2.  The script auto-creates a shortcut.
3.  Copies all valid files (skips native Google files to prevent errors).
4.  Deletes the shortcut automatically.

### 🔹 Method 3: API Copy (Advanced)
Best for copying **Google Native Files** (Docs, Sheets, Slides) and restricted folders.
* *Features:* Uses Google Drive API directly. Doesn't require mounting Drive in some cases. Handles "Restricted" errors gracefully.

## 🚀 How to Use

1.  Click the **"Open in Colab"** badge above.
2.  Select the method (Cell) you want to use.
3.  Run the code block.
4.  **Authenticate** with your Google Account when prompted.
5.  Enter your **Link** or **Folder Names** in the configuration section.
6.  Sit back and let Google's servers handle the transfer!

## ⚙️ Requirements

* A Google Account with sufficient Drive storage.
* Google Colab (Free tier works perfectly).

## ⚠️ Disclaimer

This tool is for educational and personal data management purposes. Please respect copyright laws and the terms of service of the content you are accessing.

---
*Created by [Thamindu-Dev](https://github.com/Thamindu-Dev)*
