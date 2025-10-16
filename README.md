# 🚀 Node.js Setup Guide

Welcome to this quick and beginner-friendly guide on setting up **Node.js** on your system!  
Whether you're starting your first JavaScript project or preparing for backend development — this guide has you covered. ⚡

---

## 📦 What is Node.js?

**Node.js** is a runtime environment that lets you run JavaScript outside your browser — perfect for building fast, scalable network applications like servers, APIs, or even bots! 🤖

---

## 🧰 Prerequisites

Before we start, make sure you have:

- A computer running **Windows**, **macOS**, or **Linux** 🖥️  
- Internet connection 🌐  
- Basic knowledge of using the **terminal / command prompt** 💻  

---

## ⚙️ Step 1: Download & Install Node.js

1. Go to the official website:  
   👉 [https://nodejs.org](https://nodejs.org)

2. You’ll see two versions:
   - **LTS (Recommended for most users)** 🟢  
   - **Current (Latest features, may be unstable)** 🧪  

   Choose **LTS** for stability.

3. Download the installer and run it.

4. During installation:
   - Keep all default settings ✅  
   - Make sure the **“Add to PATH”** option is checked ☑️  

5. Once installation is complete, restart your terminal or command prompt.

---

## 🧪 Step 2: Verify Installation

To make sure Node.js and npm (Node Package Manager) are installed correctly, run these commands:

👉 This shows the Node.js version (example: v20.10.1)

npm -v


👉 This shows the npm version (example: 10.2.3)

If both return version numbers — congratulations! 🎉
You’ve successfully installed Node.js on your machine.

🧩 Step 3: Create Your First Node Project

Open your terminal or VS Code.

Create a new folder:
<pre> bash
  
mkdir my-first-node-app
cd my-first-node-app


Initialize your project:

npm init -y


This creates a package.json file (your project’s DNA 🧬).

Create a test file:

echo "console.log('Hello from Node.js!');" > index.js


Run it:

node index.js


🎯 You should see:

Hello from Node.js!
 </pre>
💡 Bonus Tips

Use VS Code for best experience: https://code.visualstudio.com
<pre> bash

To check Node.js version , use the Node Version Manager (nvm)

Keep npm packages up to date with:

npm update -g

node -v
</pre>

🧠 Summary
Command	Description
node -v	Check Node.js version
npm -v	Check npm version
npm init -y	Initialize a new Node.js project
node filename.js	Run a JavaScript file
❤️ Contribute

If you found this guide helpful, star ⭐ this repo or share it with your friends who are learning Node.js!


