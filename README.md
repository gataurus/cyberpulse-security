# 🛡️ Cyber Security — WordPress Security Plugin

**Advanced WordPress protection against bots, vulnerability scanners, brute force attacks, and AI scraping. Multi-layer verification with analysis of User-Agent, Referer, behavioral patterns, and browser headers.**

[![Version](https://img.shields.io/badge/version-5.9-blue.svg)](https://github.com/gataurus/cyber-security)
[![License](https://img.shields.io/badge/license-GPL%20v2-green.svg)](LICENSE)
[![PHP](https://img.shields.io/badge/PHP-7.4+-purple.svg)](https://php.net)
[![WordPress](https://img.shields.io/badge/WordPress-5.0+-blue.svg)](https://wordpress.org)

**Author:** [gataurus](https://github.com/gataurus)

---

## 🚀 Features

### Multi-Layer Bot Detection
- ✅ User-Agent analysis (empty, anomalous, CLI tools)
- ✅ Referer verification (fake, spam referrers)
- ✅ HTTP header validation (Sec-Fetch, Accept-Language, Accept-Encoding)
- ✅ Browser fingerprint detection
- ✅ HTTP/1.0 blocking (legacy protocol)
- ✅ Direct IP access protection

### AI Scraping Protection
- 🤖 GPTBot (OpenAI)
- 🤖 ChatGPT-User
- 🤖 CCBot (Common Crawl)
- 🤖 Claude-Web / ClaudeBot (Anthropic)
- 🤖 PerplexityBot
- 🤖 Google-Extended
- 🤖 Bytespider (ByteDance)
- 🤖 Amazonbot

### Behavioral Analysis
- 🧠 Page transition speed analysis
- 🧠 Sequential URL scanning detection
- 🧠 GET/POST ratio monitoring
- 🧠 Hidden file path detection

### Brute Force Protection
- 🔒 Login attempt tracking (wp-login.php, xmlrpc.php, /wp-admin/)
- 🔒 Automatic permanent /24 subnet ban
- 🔒 Configurable attempt limits

### Cloudflare Turnstile Integration
- ☁️ Smart CAPTCHA — invisible to real users in 90% of cases
- ☁️ Free up to 1,000,000 verifications/month
- ☁️ Automatic fallback to simple math test if unavailable

### DDoS Protection
- 🛡️ Application-layer (Layer 7) flood protection
- 🛡️ Configurable thresholds and ban durations
- 🛡️ Global high-protection mode

### Monitoring & Logging
- 📊 Page visit tracking
- 📋 Detailed blocked/allowed request logs
- 📈 Hourly statistics
- 🌍 IP geolocation
- 📧 Attack spike email alerts
- 🔍 User-Agent statistics

### WordPress Security Hardening
- 🔐 Hide WordPress version
- 🔐 Remove version strings from URLs
- 🔐 Hide login error details
- 🔐 Disable XML-RPC pingbacks
- 🔐 Content Security Policy headers
- 🔐 Secure cookies (Secure + HttpOnly)

### Content Protection
- 🛡️ Text selection prevention
- 🛡️ Right-click blocking
- 🛡️ Drag-and-drop prevention
- 🛡️ Hotkey blocking (Ctrl+U, F12, etc.)
- 🛡️ Source link added on copy

### Whitelist Management
- ✅ IP addresses
- ✅ CIDR subnets
- ✅ Hostnames / PTR records
- ✅ User-Agent patterns
- ✅ Automatic search engine whitelisting

---

## 📦 Installation

1. Download the plugin ZIP archive
2. Go to WordPress Admin → Plugins → Add New → Upload Plugin
3. Choose the ZIP file and click "Install Now"
4. Activate the plugin
5. Configure via "Cyber Security" menu

---

## ⚙️ Default Configuration

The plugin is pre-configured for optimal protection out of the box:

| Setting | Default Value |
|---------|---------------|
| Referer Check | ✅ Enabled |
| WordPress Hiding | ✅ Enabled |
| Brute Force Protection | ✅ Enabled (5 attempts / 15 min) |
| Rate Limiting | ✅ Enabled (60 requests / 60 sec) |
| Behavioral Analysis | ✅ Enabled |
| Auto Unblock | 30 minutes |

---

## 🔧 Requirements

- WordPress 5.0 or higher
- PHP 7.4 or higher
- Write permissions to `/wp-content/uploads/`

---

## 📊 Real-World Performance

Based on 24 hours of operation on a production site:

| Metric | Value |
|--------|-------|
| Attacks blocked | ~100+ |
| False positives | 0 |
| AI bots blocked | ~10 |
| Permanent bans | ~5 |
| Search engines allowed | ~200+ |

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs via [GitHub Issues](https://github.com/gataurus/cyber-security/issues)
- 💡 Suggest new features
- 🔧 Submit pull requests

---

## 📄 License

GNU General Public License v2.0 — see [LICENSE](LICENSE)

---

**Developed by [gataurus](https://github.com/gataurus)**
