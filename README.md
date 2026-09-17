# 🛡️ Sentinel Scan — AI Prompt Security Firewall

A cybersecurity AI diagnostic dashboard that audits prompts for prompt injection vulnerabilities, jailbreak attempts, and safety risks.

## Features
- **Prompt Security Audit**: Screens raw user inputs for malicious payload markers.
- **Dual-Model Detection Pipeline**:
  - Fast classification via `meta-llama/llama-prompt-guard-2-86m`.
  - Deep threat taxonomy analysis via Groq security LLM (`qwen-2.5-32b`).
- **Threat Vector Diagnostics**: Evaluates 4 attack categories:
  - *Prompt Injection & Hijack*
  - *System Prompt Leakage*
  - *Harmful Intent & Malicious Code*
  - *PII & Data Exfiltration*
- **Horizontal Risk Gauge**: Dynamic color-coded progress meter (0–100 risk score).
- **Prompt Hardening**: Automatically rewrites risky prompts into sanitized, safe alternatives.
- **Security Audit Reports**: Download timestamped Markdown audit summaries.
- **Adversarial Presets**: Preloaded benchmark attacks (DAN jailbreak, context switching, system leak, benign requests).

## Getting Started
1. Open `index.html` in your browser.
2. Click the **Settings (⚙️)** button and enter your Groq API Key.
3. Paste a prompt or click a benchmark preset, then click **Analyze Security**.


## ⌨️ Keyboard Shortcuts
- `Esc`: Close settings and modal dialogs

## 📄 License
Licensed under the [MIT License](LICENSE) by ankitachatt65.
