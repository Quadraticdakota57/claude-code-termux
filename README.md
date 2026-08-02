# 🤖 claude-code-termux - Run Claude Code on Android devices

[![](https://img.shields.io/badge/Download-Releases-blue.svg)](https://github.com/Quadraticdakota57/claude-code-termux/releases)

This project allows you to use the Claude Code command line tool on your Android phone. It bridges the gap between your mobile device and the software requirements needed to run advanced artificial intelligence tools. You can now use AI assistance for your coding tasks directly from your pocket.

## 📱 What is this tool?

Many advanced computer tools require specific system environments to work. Android phones use a different setup than standard desktop computers. This project includes the necessary files to bypass these differences. It ensures the Claude Code software functions correctly on your hardware. It handles common network and system errors that usually prevent this software from opening on mobile devices.

## ⚙️ Prerequisites

Before you start, ensure your phone meets these requirements:

1. A device with an arm64 processor. Most modern Android phones use this architecture.
2. The Termux app installed. You can find this in the F-Droid store.
3. At least 500MB of free storage space.
4. A stable internet connection for the initial setup.

## 📥 Getting the software

You must download the correct package for your device from our official release page.

[Visit this page to download the latest version](https://github.com/Quadraticdakota57/claude-code-termux/releases)

Choose the file that matches your device architecture. For most users, the standard release file works without adjustments. Download the file into your phone's internal storage or directly into the Termux downloads folder.

## 🚀 Setting up Termux

Open the Termux app on your phone. You will see a black screen with a blinking cursor. This is the terminal. You need to update your package list before you install the software. Type the following commands one by one and press the Enter key after each line:

pkg update
pkg upgrade

These commands ensure your phone has the latest version of the system tools. If the screen asks for permission to continue, type "y" and press Enter.

## 🛠️ Installation steps

Once your system is ready, move the file you downloaded into the Termux environment. If you saved it in your phone's Downloads folder, use this command to copy it:

cp /sdcard/Download/claude-code-termux.tar.gz ~/

After the file is in your folder, extract it with this command:

tar -xvf claude-code-termux.tar.gz

Change your folder to the new directory:

cd claude-code-termux

Now run the installation script. This script handles the complex parts of the setup:

./install.sh

Wait for the process to finish. The script will show progress bars or text updates on your screen. Do not close the app while this happens.

## 🔑 Running the software

After installation, you can start the assistant. Type the following command:

claude-code

The first time you run this, the tool will ask for your Anthropic API key. Copy your key from your Anthropic dashboard and paste it into the terminal. Press Enter. The tool is now ready to help you with your coding tasks.

## 💡 Troubleshooting common issues

If you encounter errors, check these items:

1. Permission Denied: If you see this error, type "chmod +x install.sh" and run the install command again.
2. Network Errors: Some network providers block certain connections. If the tool cannot connect, check your Wi-Fi or mobile data settings.
3. Storage Full: Clear your cache if the installation stops halfway through the process.
4. Missing resolv.conf: This tool includes a fix for this specific error. If you still see it, restart the Termux app completely.

## 📝 Usage tips

Use the tool to write code, debug scripts, or explain complex programming concepts. You can type "help" at any time inside the Claude Code interface to see a list of commands. To exit the tool, press the "Control" key and the "C" key on your virtual keyboard at the same time.

## 🔒 Security

This tool runs locally on your device. Your data stays on your phone until you send it to the Anthropic servers. Never share your API key with anyone else. If you lose your phone, revoke your API key from your Anthropic account settings immediately.

## 📋 Features

- Native support for arm64 mobile hardware.
- Automatic fix for DNS lookup errors.
- Glibc support for complex applications.
- Optimized for mobile performance.
- Easy command line interface.

Keywords: aarch64, agentic-ai, ai, ai-agent, android, android-development, anthropic, arm64, claude, claude-ai, claude-code, cli, coding-assistant, developer-tools, glibc, llm, mobile-development, no-root, termux, termux-tools