<div align="center">
  <img src="https://raw.githubusercontent.com/LeetCommit/LeetCommit/main/dist/icons/128.png" alt="LeetCommit Logo" width="128" height="128" />
  
  # Welcome to LeetCommit 🚀
  
  **Automatically sync your LeetCode accepted submissions directly to GitHub.**
  
  [![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Available_Now-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](#)
  [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](#)
  [![GitHub release (latest by date)](https://img.shields.io/github/v/release/LeetCommit/LeetCommit?style=for-the-badge)](#)
</div>

---

### 🌟 What is LeetCommit?

LeetCommit is an enterprise-grade, secure Chrome Extension designed to streamline your competitive programming workflow. Built with a modern architecture, it silently intercepts your successful LeetCode submissions and pushes them to your GitHub repository in real-time.

Instead of manually copying, pasting, and organizing your code, let LeetCommit handle your GitHub activity graph so you can focus entirely on the algorithms.

### 🛡️ Why We Are Different

Legacy extensions forced you to manually copy and paste highly sensitive **Personal Access Tokens (PATs)** into your browser, exposing you to severe security risks. 

**LeetCommit solves this with modern architecture:**
- **Zero Tokens:** We utilize a highly secure **OAuth 2.0 Web Flow** routed through our private Cloudflare proxy.
- **Client-Side Encryption:** Your active session tokens are encrypted at rest using AES-GCM-256 cryptography.
- **Maximum Privacy:** We don't track your data, and we don't store your source code. Your submissions travel securely from the LeetCode client directly to the GitHub API.

### ⚡ Core Features

- **Real-Time Syncing:** Captures your submission the exact millisecond LeetCode accepts it. No page refreshes required.
- **Background Fallback Queue:** If your internet drops or the GitHub API goes down, LeetCommit automatically queues your code locally and retries the sync later.
- **Organization Support:** Sync to your personal repository or any GitHub Organization repository.
- **Automated README Generation:** LeetCommit automatically generates and updates a global `README.md` in your target repository to showcase your daily streak, total solved count, and language breakdown.

---

<div align="center">
  <h3>🛠️ Built With</h3>
  <p>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/Chrome_Extensions-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Chrome Extensions" />
    <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
    <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions" />
  </p>
</div>

---

<div align="center">
  <b>Want to contribute or report a bug?</b> Check out our <a href="https://github.com/LeetCommit/LeetCommit">main repository</a>!
</div>
