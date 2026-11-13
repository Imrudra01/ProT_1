# ProT_1 - Shared Team Coding Environment

Welcome to **ProT_1**! This repository is configured as a turnkey, cloud-based shared coding environment for team collaboration using **GitHub Codespaces** and **Visual Studio Live Share**.

---

## 🚀 How to Launch the Environment

### Option 1: GitHub Codespaces (Cloud IDE — Zero Setup)
1. In the GitHub repository page, click the green **Code** button.
2. Select the **Codespaces** tab.
3. Click **Create codespace on main**.
4. GitHub will build the pre-configured container with:
   - Full Linux development container (Python, Node.js, Git CLI).
   - VS Code extensions pre-installed (Live Share, GitLens, Prettier).
   - Forwarded ports (3000, 8080) for web dev previews.

### Option 2: Real-Time Pair Programming (Live Share)
Once inside the Codespace or VS Code:
1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`).
2. Search and select: `Live Share: Start Collaboration Session`.
3. Copy the invite link generated and send it to your teammate(s).
4. Teammates can join right in their browser or in VS Code to edit files together, co-debug, and share terminals in real time.

### Option 3: GitHub Web Editor (Quick Edits)
- Press the `.` (dot) key on your keyboard anywhere on the GitHub repository page to immediately open VS Code for the web.

---

## 👥 How to Share with Your Team

1. Go to your repository on GitHub: `https://github.com/<your-username>/ProT_1`.
2. Click **Settings** > **Collaborators** (under "Access").
3. Click **Add people** and enter your teammates' GitHub usernames or email addresses.
4. Once they accept the invitation, they can immediately launch their own Codespace or join your live coding sessions.

---

## 🛠 Included Configurations
- **`.devcontainer/devcontainer.json`**: Codespaces & Dev Containers runtime specification.
- **VS Code Recommendations**: Pre-configured extensions for formatting, git analysis, and live pairing.
- **Port Forwarding**: 3000 and 8080 configured for instant local web server previewing.

