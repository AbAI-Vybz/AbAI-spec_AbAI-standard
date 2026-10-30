# Contributing to AbAI

Thank you for your interest in contributing to **AbAI (Assisted by AI)**! This project thrives on practical utility, clean architecture, and the symbiotic collaboration between human intuition and machine intelligence.

Before submitting code, please review the guidelines below to ensure a smooth integration workflow.

---

## Code of Conduct & Guiding Philosophy

* **Direct & Constructive**: We value candid, high-signal technical feedback, clear logic, and respectful dialogue.
* **First-Principles Design**: Keep solutions lean, reproducible, and decoupled. Avoid unnecessary bloat or redundant dependencies.
* **Zero Guesswork**: Document why a technical decision or refactor was made, especially when integrating with AI models, APIs, or native interfaces.

---

## How to Contribute

### 1. Reporting Bugs & Proposing Features
* Check open and closed GitHub Issues before filing a new ticket to avoid duplicates.
* For bug reports, include:
  * Minimal reproduction steps.
  * System environment details (OS, architecture, runtime version).
  * Observed vs. expected behavior with relevant log traces.
* For new features or architectural changes, open a **Discussion** or an issue marked `[RFC]` prior to submitting large PRs.

### 2. Branching & Commit Conventions
* Fork the repository and create a descriptive feature branch:
  ```bash
  git checkout -b feat/android-dpad-support
  # or
  git checkout -b fix/auth-token-refresh
