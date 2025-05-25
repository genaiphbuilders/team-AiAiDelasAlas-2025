# team-AiAiDelasAlas-2025

# **BudolBlocker.AI**

### *An Agentic Misleading Content Detector for Social Media — Powered by AI*

---

## Project Description

**BudolBlocker.AI** is a lightweight browser extension that proactively flags misleading social media content such as scam links, doctored images, and emotionally manipulative posts. Powered by agentic AI and unsupervised learning, it ensures Filipinos can scroll safely — free from *budol*.

---

## Tech Stack

**Languages:** JavaScript, Python
**Frameworks:** TensorFlow\.js, Node.js
**Libraries:** Tesseract.js (OCR), Scikit-learn, Transformers (HuggingFace)
**Tools:** Chrome Extension (Manifest V3), Git, Google Colab

---

## Table of Contents

1. [Features](#features)
2. [Usage Guide](#usage-guide)
3. [Quick Start](#quick-start)
4. [Repository Structure](#repository-structure)
5. [Team Members](#team-members)

---

## Features

* **Real-Time Feed Monitoring** on platforms like Facebook, TikTok, and Twitter
* **Meme & Screenshot Scanning** using OCR to detect scammy phrases (e.g., “Donate”)
* **Affiliate Link Detection** and inspection
* **Multi-Agent AI Framework** for flagging and verifying misleading content
* **User Feedback System** with trust scoring and democratic moderation
* **Sentiment & Semantic Analysis** to understand emotional manipulation

**Example Use Cases:**

* Flags fake celebrity clickbait (e.g., Jilian Ward + Shopee scams)
* Detects “Help Now” emotional scams
* Screens memes with altered or misleading texts
* Inspects context mismatches between post content and landing links

---

## Usage Guide

1. Install the browser extension on Chrome.
2. Navigate to your social media feed.
3. The extension will automatically scan and flag suspicious posts.
4. Click on the flag icon to view the reason and vote (accurate/inaccurate).
5. Help improve the system through your feedback.

---

## Quick Start

### Prerequisites:

* Node.js v16+
* Chrome Browser (with Extension Developer Mode enabled)
* Python 3.9+ (for AI backend dev)

### Installation:

```bash
git clone https://github.com/your-org/BudolBlocker.AI.git
cd BudolBlocker.AI
```

### Frontend (Extension):

1. Go to `chrome://extensions/`
2. Enable "Developer Mode"
3. Click "Load Unpacked" and select the `extension/` folder

### Backend (AI Components):

```bash
cd backend/
pip install -r requirements.txt
python run_agents.py
```

Access backend logs via `http://localhost:5000/logs`

---

## Repository Structure

```
BudolBlocker.AI/
├── extension/              # Chrome extension code (UI + flags)
│   ├── manifest.json       # Manifest V3 configuration
│   ├── popup.html          # UI HTML
│   ├── popup.js            # UI logic
│   ├── icons/              # Extension icons
├── backend/                # ML & AI agent logic
│   ├── agents/             # Multi-agent framework scripts
│   ├── ocr_module.py       # Meme OCR processor
│   ├── link_scanner.py     # Affiliate link inspector
│   ├── feedback_loop.py    # Learns from user actions
│   ├── requirements.txt    # Python dependencies
├── README.md               # Project documentation
```

---

## Team Members

* **Cilla Adlawan** (Team Lead) – [GitHub](https://github.com/Chiila) | [LinkedIn](https://www.linkedin.com/in/cilla-adlawan-7b78bb2a1)

* **Luis Laguardia** (Role) – [GitHub](https://github.com/luislaguardia) | [LinkedIn](http://linkedin.com/in/devluislaguardia)

* **Iber Bonilla** (Role) – [GitHub](https://github.com/berbonila) | [LinkedIn](https://linkedin.com/in/iber-joseph-bonilla)

* **Nicole Alcantara** (Role) – [GitHub](https://github.com/risingkap) | [LinkedIn](https://linkedin.com/in/alcantaranc)
