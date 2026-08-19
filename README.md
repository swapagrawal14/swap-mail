<div align="center">

# ✉️ SwapMail

### A clean, privacy-minded temporary inbox interface

[![Open SwapMail](https://img.shields.io/badge/Open%20the%20demo-GitHub%20Pages-5865F2?style=for-the-badge&logo=github-pages&logoColor=white)](https://swapagrawal14.github.io/swap-mail/)
[![Status](https://img.shields.io/badge/status-live%20demo-19b87f?style=for-the-badge)](https://swapagrawal14.github.io/swap-mail/)

**[↗ Try SwapMail](https://swapagrawal14.github.io/swap-mail/)** · **[Report an issue](https://github.com/swapagrawal14/swap-mail/issues)**

</div>

---

## What is SwapMail?

SwapMail is a responsive disposable-email interface for low-risk verification and software-testing flows. It offers a polished inbox experience while loading the current public domain directory from the connected mail API.

> **Important:** Use temporary inboxes only for legitimate low-risk testing and verification. Never use them for banking, purchases, account recovery, fraud, or bypassing another service’s rules.

## Features

- 🌐 **Live domain directory** — loads active public domains dynamically
- ⚡ **Custom & random addresses** — generate an address in one click
- 📋 **Copy tools** — copy an address, API endpoint, or verification code
- 📨 **Inbox experience** — refresh, clear, and inspect sample messages
- 🔔 **Inbox alert preference** — saved locally in the browser
- 🕘 **Recent address history** — quickly restore up to five recent addresses
- 🌓 **Light and dark themes** — your selection persists locally
- 📱 **Responsive layout** — built for desktop and mobile screens

## Live demo

Once GitHub Pages is enabled, the website is published at:

### [https://swapagrawal14.github.io/swap-mail/](https://swapagrawal14.github.io/swap-mail/)

## Run locally

No install or build process is required.

```bash
python3 -m http.server 8000 --bind 0.0.0.0
```

Then open [http://localhost:8000](http://localhost:8000).

## Publishing with GitHub Pages

This repository includes a GitHub Actions workflow that publishes `index.html` to GitHub Pages whenever changes are pushed to `main`.

If this is the first deployment, open the repository’s **Settings → Pages** and set **Source** to **GitHub Actions**. The workflow will then deploy automatically.

## Tech stack

A lightweight static site using plain HTML, CSS, and JavaScript—no framework, package manager, or build step required.

## License

This project is provided for personal learning and demonstration purposes.
