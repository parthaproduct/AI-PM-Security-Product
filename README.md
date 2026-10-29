# 🛡️ AI Security Portfolio Repo Builder & Launchpad

A lightweight, browser-based interactive dashboard and wizard designed for AI Product Managers, Security Engineers, and Developers looking to build, test, and launch production-ready **AI Security GitHub Repositories**.

---

## 🌟 Overview

The **AI Security Repo Builder** (`index.html`) is a self-contained web app that helps you create portfolio projects across three core AI security domains:
1. **Automated LLM Red-Teaming Pipelines** (Offensive scanning using Promptfoo, PyRIT, Garak).
2. **Agentic Tool Execution Firewalls** (Defensive inline proxies scanning tool call arguments).
3. **RAG Vector Database Poisoning Defenses** (Context boundary isolation and indirect prompt injection defense).

---

## 🚀 How to Use / Host

Since the app is built as a single interactive HTML file (`index.html` or `AI Security Repo builder.html`), you can run it in two easy ways:

### Option 1: Open Locally in Your Browser
1. Clone or download this repository.
2. Double-click `index.html` (or open it with Chrome, Firefox, Safari, or Edge).
3. No build step, node modules, or web servers required!

### Option 2: Host for Free with GitHub Pages
1. Go to your repository settings on GitHub (**Settings** $\rightarrow$ **Pages**).
2. Under **Source**, select `main` (or `master`) branch and click **Save**.
3. Rename `AI Security Repo builder.html` to `index.html` if it isn't already.
4. Your builder will be live at `https://<your-username>.github.io/<your-repo-name>/`.

---

## 🛠️ Features Included in the Tool

* **Interactive Project Wizard:** Customizes repo names, target LLM models (Llama 3, GPT-4o, Claude 3.5), and specific OWASP Top 10 for LLM/Agentic vulnerabilities.
* **Real-Time Code Generator:** Instantly generates syntax-checked code for:
  * `main.py` (Core security logic / firewall scanner)
  * `README.md` (Project documentation)
  * `.github/workflows/ci.yml` (GitHub Actions CI/CD scanner)
  * `Dockerfile` (Containerized test environment)
  * `requirements.txt` (Dependencies)
* **One-Click Export:** Download the entire repository configuration as a `.zip` file ready to push to GitHub.
* **Git & Build Simulator Terminal:** Test common commands (`git init`, `git add`, `git commit`, `docker build`, `pytest`) inside an interactive terminal simulator.
* **LinkedIn Article Generator:** Auto-creates technical launch posts ready to copy and share on LinkedIn or Medium.

---

## 📋 OWASP Framework Alignment

Projects generated using this builder align directly with enterprise standards:
* **OWASP Top 10 for LLM Applications**
* **OWASP Top 10 for Agentic Applications**
* **NIST AI Risk Management Framework (AI RMF)**
* **MITRE ATLAS Framework**

---

## 🤝 Contributing

Feel free to submit Pull Requests to add new templates, guardrail rules, or features to the builder HTML app!

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).