# 🚀 AISDC 2026 GitHub Copilot Workshop

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/112698e1-2940-4183-acf5-9972ae1ff043" />


> **Your AI-powered coding companion — from setup to shipping.**

Welcome to the **2026 GitHub Copilot Program**! This guide walks you through everything you need to get started with GitHub Copilot, activate your Azure for Students benefits, and begin building with Microsoft's AI-powered developer tools.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Getting Started with GitHub Copilot](#getting-started-with-github-copilot)
- [Installation — VS Code](#installation--vs-code)
- [Installation — Visual Studio](#installation--visual-studio)
- [Your First Copilot Interaction](#your-first-copilot-interaction)
- [Azure for Students Activation](#azure-for-students-activation)
- [Azure AI Services — Learn More](#azure-ai-services--learn-more)
- [Useful Commands & Tips](#useful-commands--tips)
- [Resources](#resources)
- [License](#license)

---

## Overview

GitHub Copilot is an AI pair-programming assistant that suggests whole lines, functions, and even entire blocks of code as you type. In 2026, Copilot goes far beyond autocomplete — it includes:

| Feature | Description |
|---|---|
| **Inline Completions** | Ghost-text suggestions that appear as you type |
| **Copilot Chat** | Conversational AI panel for Q&A, explanations, and code generation |
| **Copilot Edits** | Multi-file editing powered by natural language |
| **Agent Mode** | Autonomous task execution for complex workflows |
| **CLI Extension** | AI assistance directly in your terminal |

---

## Prerequisites

Before you begin, make sure you have the following:

- ✅ A **GitHub account** — [Sign up free](https://github.com/join)
- ✅ **VS Code 1.95+** or **Visual Studio 17.8+** installed
- ✅ A **stable internet connection** (Copilot processes requests in the cloud)
- ✅ An active **Copilot plan** (Free tier available — see below)

### Copilot Plans at a Glance

| Plan | Price | Highlights |
|---|---|---|
| **Copilot Free** | $0/month | Limited completions & chat — great for exploring |
| **Copilot Pro** | $10/month | Unlimited completions, priority models, advanced features |
| **Copilot Pro+** | $39/month | Everything in Pro plus premium models & higher limits |
| **Copilot Business** | $19/user/month | For teams and organisations |

> 💡 **Students**: You may be eligible for Copilot access through the [GitHub Student Developer Pack](https://education.github.com/pack).

---

## Getting Started with GitHub Copilot

### Step 1 — Sign Up for a Copilot Plan

1. Go to [github.com/features/copilot](https://github.com/features/copilot).
2. Click **Get started for free** to start with Copilot Free, or choose a paid plan.
3. Sign in with your GitHub account and follow the prompts.

### Step 2 — Choose Your Editor

GitHub Copilot works in multiple environments:

- **VS Code** (recommended — full feature support)
- **Visual Studio** (Windows)
- **JetBrains IDEs** (IntelliJ, PyCharm, WebStorm, etc.)
- **GitHub.com** (browser-based — no install needed)
- **GitHub Mobile**
- **CLI** (via the GitHub CLI Copilot extension)

---

## Installation — VS Code

### 1. Install the Extension

Open VS Code and run:

```
Ctrl+Shift+X    (Windows/Linux)
Cmd+Shift+X     (macOS)
```

Search for **"GitHub Copilot"** and click **Install**.

This installs the core extension bundle, which includes:
- Inline completions
- Copilot Chat
- Copilot Edits

> If **"GitHub Copilot Chat"** doesn't install automatically, install it separately from the Extensions panel.

### 2. Sign In to GitHub

After installation, a sign-in prompt appears in the bottom-right corner of VS Code.

1. Click **Sign in to GitHub**.
2. Complete the OAuth authorisation in your browser.
3. Return to VS Code — a solid Copilot icon in the status bar confirms activation.

**If the prompt doesn't appear:**

```
Ctrl+Shift+P    →    GitHub Copilot: Sign In
```

### 3. Verify It's Working

Open or create any code file (e.g., `hello.py`) and start typing:

```python
# Function to greet the user
def greet(name):
```

Copilot should suggest a completion in grey text. Press `Tab` to accept.

---

## Installation — Visual Studio

1. Open **Visual Studio 2022** (version 17.8 or later).
2. Go to **Extensions → Manage Extensions**.
3. Search for **"GitHub Copilot"** and install.
4. Restart Visual Studio.
5. Click the **GitHub Copilot badge** in the upper-right corner and select **Open Chat Window**.
6. Sign in with your GitHub account when prompted.

> 💡 **Tip**: Update to the latest Visual Studio version for the best Copilot experience — `Help → Check for Updates`.

---

## Your First Copilot Interaction

### In the Editor (Inline Completions)

Simply start coding. Copilot will suggest completions as ghost text:

```javascript
// Express.js route to fetch all users
app.get('/users', async (req, res) => {
    // Copilot suggests the function body here ✨
});
```

| Shortcut | Action |
|---|---|
| `Tab` | Accept the full suggestion |
| `Esc` | Dismiss the suggestion |
| `Alt + ]` | See the next suggestion |
| `Alt + [` | See the previous suggestion |

### In Copilot Chat

Open the chat panel and try prompts like:

```
Explain this file.
How could I improve this code?
Write unit tests for the selected function.
Refactor this to use async/await.
```

### Agent Mode (VS Code)

1. Open the Copilot Chat panel.
2. Switch from **Ask** to **Agent**.
3. Give a high-level instruction:

```
Create a REST API with Express that has CRUD endpoints for a "tasks" resource.
```

Copilot will autonomously create files, write code, and run commands.

---

## Azure for Students Activation

As a student, you get **free access** to Microsoft Azure — including **$100 in credits** for 12 months, with no credit card required.

### How to Activate

1. **Visit** the Azure for Students page:  
   👉 [https://azure.microsoft.com/free/students/](https://azure.microsoft.com/free/students/)

2. **Click** "Start free".

3. **Sign in** with your school/university email address (e.g., `you@university.edu`).

4. **Verify** your student status:
   - Microsoft may auto-verify via your email domain.
   - If not, upload a student ID or enrolment letter.

5. **Done!** Your Azure subscription is now active.

### What You Get

- 💰 **$100 credit** valid for 12 months
- 🆓 **Free monthly amounts** of 20+ popular services (for 12 months)
- ♾️ **65+ always-free services** (no expiry)
- 🔄 **Annual renewal** — renew as long as you're a student
- 🔒 **No credit card required**

### Troubleshooting

| Issue | Solution |
|---|---|
| Email not accepted | Ensure it belongs to an accredited institution |
| Verification fails | Upload a clear photo of your student ID |
| Region restrictions | Check eligibility at the [Azure for Students FAQ](https://azure.microsoft.com/free/students/) |

---

## Azure AI Services — Learn More

Take your projects further with Azure AI Services — pre-built APIs and models for vision, speech, language, and decision-making.

🔗 **Microsoft Learn — Azure AI Services**:  
[https://learn.microsoft.com/azure/ai-services/](https://learn.microsoft.com/azure/ai-services/)

Key services to explore:

- **Azure OpenAI Service** — Access GPT, DALL·E, and other frontier models
- **Azure AI Language** — Sentiment analysis, entity recognition, summarisation
- **Azure AI Vision** — Image analysis, OCR, spatial analysis
- **Azure AI Speech** — Speech-to-text, text-to-speech, translation
- **Azure AI Content Safety** — Detect harmful content in text and images

> 🎓 **Recommended Learning Path**: [Introduction to AI in Azure](https://learn.microsoft.com/training/paths/get-started-with-artificial-intelligence-on-azure/) on Microsoft Learn.

---

## Useful Commands & Tips

### VS Code Keyboard Shortcuts

```
Ctrl+Shift+P  →  GitHub Copilot: Sign In
Ctrl+Shift+P  →  GitHub Copilot: Enable/Disable
Ctrl+I        →  Open Copilot Inline Chat
Ctrl+Shift+I  →  Open Copilot Chat Panel
```

### GitHub CLI — Copilot Extension

```bash
# Install the GitHub CLI (if not installed)
# Visit: https://cli.github.com

# Install the Copilot CLI extension
gh extension install github/gh-copilot

# Ask Copilot to explain a command
gh copilot explain "git rebase -i HEAD~3"

# Ask Copilot to suggest a command
gh copilot suggest "find all .log files larger than 100MB"
```

### Best Practices for Effective Prompts

1. **Be specific** — "Write a Python function that validates email addresses using regex" beats "write some code".
2. **Provide context** — Open relevant files so Copilot understands your project.
3. **Use comments as prompts** — Write a comment describing what you want, then let Copilot complete.
4. **Iterate** — Cycle through suggestions with `Alt + ]` / `Alt + [`.
5. **Review before accepting** — Always read and understand generated code.

---

## Resources

| Resource | Link |
|---|---|
| GitHub Copilot Docs | [docs.github.com/copilot](https://docs.github.com/copilot) |
| GitHub Copilot Quickstart | [docs.github.com/copilot/quickstart](https://docs.github.com/copilot/quickstart) |
| VS Code + Copilot Guide | [code.visualstudio.com/docs/copilot](https://code.visualstudio.com/docs/copilot) |
| Azure for Students | [azure.microsoft.com/free/students](https://azure.microsoft.com/free/students/) |
| Azure AI Services (Learn) | [learn.microsoft.com/azure/ai-services](https://learn.microsoft.com/azure/ai-services/) |
| Microsoft Learn — AI Hub | [learn.microsoft.com/ai](https://learn.microsoft.com/ai/) |
| GitHub Student Developer Pack | [education.github.com/pack](https://education.github.com/pack) |
| GitHub CLI | [cli.github.com](https://cli.github.com/) |

---

## License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  <strong>Built with ❤️ and GitHub Copilot</strong><br>
  <em>Vincent's 2026 Program</em>
</p>
