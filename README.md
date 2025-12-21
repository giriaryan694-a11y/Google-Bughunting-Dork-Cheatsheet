# Google-Bughunting-Dork-Cheatsheet

## 📋 Overview
A comprehensive, categorized collection of Google Dorks for security researchers and bug bounty hunters to streamline reconnaissance and vulnerability discovery during authorized security assessments.

## 🚀 Quick Start

Open this link : https://giriaryan694-a11y.github.io/Google-Bughunting-Dork-Cheatsheet/

## Features
· One-click copy: Click any dork to automatically copy it to your clipboard
· Responsive design: Works seamlessly on desktop and mobile devices
· Offline functionality: Entirely self-contained HTML file
· Categorized dorks: Organized by vulnerability type and target

## 📁 File Structure
```
Google-bughunt-dorks-cheatsheet/
│
├── index.html  # Main interactive webpage
└── README.md                             # This documentation file
```

## 🗂️ Dork Categories
The cheatsheet includes specialized dorks for:

- 1. 🔐 Login Portals & Admin Interfaces - Authentication pages and admin panels
- 2. 📁 Sensitive Files & Data - Configuration files, backups, and exposed data
- 3. 🖥️ WordPress Specific - WordPress-related vulnerabilities and exposures
- 4. 🔧 API & Configuration Files - API keys, endpoints, and config files
- 5. 🗺️ Reconnaissance & Discovery - Subdomains, directories, and infrastructure mapping
- 6. ⚡ Advanced Hunting - Error messages, log files, and document discovery
  7. more

## Pro Tips

· Combine operators for more precise results: site:target.com intext:"API_KEY" -inurl:github
· Use quotes for exact phrase matching: "DB_PASSWORD="
· Exclude noise with minus operator: inurl:login -inurl:assets
· Always start with site: operator to focus on your target

## ⚠️ Ethical & Legal Guidelines

CRITICAL: AUTHORIZED USE ONLY

This cheatsheet is intended exclusively for:

· Security testing on systems you own
· Bug bounty programs where you have explicit permission
· Educational purposes in controlled environments

## STRICTLY PROHIBITED

· ❌ Testing systems without authorization
· ❌ Accessing or downloading unauthorized data
· ❌ Disrupting services or infrastructure
· ❌ Any activity violating applicable laws or terms of service

You are solely responsible for ensuring your testing is legal and authorized.

