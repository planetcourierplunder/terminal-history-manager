# 💳 Terminal History Manager — Complete Guide

<div align="center">

![Terminal History](https://img.shields.io/badge/Terminal-History%20Manager-0891B2?style=for-the-badge&logo=gnubash&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-Bash%20%7C%20Zsh%20%7C%20Fish-7C3AED?style=for-the-badge&logo=gnometerminal&logoColor=white)
![Privacy](https://img.shields.io/badge/Privacy-First-16A34A?style=for-the-badge&logo=shieldcheck&logoColor=white)
![Guides](https://img.shields.io/badge/Guides-96K-EA580C?style=for-the-badge&logo=readthedocs&logoColor=white)

### 🖥️ Search, Sync, and Secure Your Shell History Across Machines

*A complete guide to taming years of terminal commands*

</div>

<div align="center">

<img width="1280" height="720" alt="maxresdefault (71)" src="https://github.com/user-attachments/assets/28dd273f-520c-419e-b4f6-a2ffd20b73e9" />


</div>

---

## 🧭 Navigation Flow

> **🗂️ Documentation topology**

```
┌─────────────────────────────────────────────────┐
│     TERMINAL HISTORY MANAGER — GUIDE MAP        │
├─────────────────────────────────────────────────┤
│                                                 │
│   ①  INTRODUCTION                               │
│      ╰─ Overview · Why · Concepts               │
│                                                 │
│   ②  ENVIRONMENT                                │
│      ╰─ Requirements · Get Instructions         │
│                                                 │
│   ③  INSTALLATION                               │
│      ╰─ Setup · Shell Integration · Config      │
│                                                 │
│   ④  DAILY USE                                  │
│      ╰─ Search · Sync · Prune · Export          │
│                                                 │
│   ⑤  SECURITY                                   │
│      ╰─ Secrets · Redaction · Encryption        │
│                                                 │
│   ⑥  REFERENCE                                  │
│      ╰─ CLI · Config · Troubleshooting · FAQ    │
└─────────────────────────────────────────────────┘
```

---

## 🎯 Overview

**Terminal History Manager** is a cross-shell tool that gives you **full control over your command history**. It goes far beyond the basic `history` command — providing fuzzy search, smart deduplication, cross-machine sync, secret redaction, and encrypted backup.

If you've ever thought *"what was that command I ran last week?"* — this is the tool for you.

### 🧩 What It Does

| Capability | Description |
|-----------|-------------|
| 🔎 **Fuzzy Search** | Find commands by partial match |
| 🧹 **Smart Dedup** | Collapse repetitive entries |
| 🌐 **Cross-Shell** | Bash, Zsh, Fish, PowerShell |
| ☁️ **Sync** | Across machines via git/cloud |
| 🔐 **Secret Redaction** | Auto-clean sensitive data |
| 📦 **Export** | JSON, CSV, Markdown |
| 📊 **Statistics** | Usage patterns |
| 🗂️ **Tagging** | Organize commands |
| 🔒 **Encryption** | At-rest protection |
| ⏪ **Restore** | Bring back old sessions |

---

## 💡 Why It Matters

| Problem | Solution |
|---------|----------|
| 🐌 Default history is linear | Fuzzy, filtered search |
| 🔁 Duplicates everywhere | Smart deduplication |
| 🖥️ Each machine isolated | Cloud sync |
| 🔐 Secrets in history | Automatic redaction |
| 📉 No insights | Usage analytics |
| 💾 Lost after cleanup | Encrypted backups |
| 🧩 Different per shell | Unified view |

---

## 🧬 Core Concepts

| Term | Meaning |
|------|---------|
| 📚 **History Store** | Unified database of commands |
| 🔗 **Sync Remote** | Cloud or git backend |
| 🔐 **Redaction Rule** | Pattern that hides secrets |
| 🏷️ **Tag** | User-defined category |
| 📸 **Session** | Commands from one shell |
| 🔎 **Fuzzy Match** | Approximate search |
| ⏱️ **TTL** | Auto-prune age |
| 🗂️ **Profile** | Named config set |

---

## 🖥️ System Requirements

### 🔹 Minimum

```
✅ OS: Linux, macOS, Windows (WSL/Git Bash)
✅ Shell: Bash 4+, Zsh 5+, Fish 3+, PowerShell 7+
✅ CPU: Any modern x86-64
✅ RAM: 512 MB
✅ Storage: 50 MB
✅ Runtime: Node.js 18+ or Python 3.10+
```

### 🔸 Recommended

```
⭐ OS: Ubuntu 22.04+ / macOS 13+ / Windows 11 + WSL2
⭐ Shell: Zsh + Oh My Zsh, or Fish
⭐ CPU: Dual-core 2.0 GHz+
⭐ RAM: 4 GB
⭐ Storage: 500 MB SSD
⭐ Sync: Private git repo or cloud storage
⭐ Encryption: age or GPG installed
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-0891B2?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=155E75)](https://share.google/O4MpxHvCpKYWnXM3y)

</div>

---

## 📘 Get Instructions

<div align="center">

### 🚀 Access the Official Setup Guide

Click below to reach the instructions portal:

<br>

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=4C1D95)](https://share.google/O4MpxHvCpKYWnXM3y)

<br>

*Open Source • Cross-Shell • Privacy-First*

</div>

### 📚 Available Guides

| Guide | Purpose |
|-------|---------|
| 📘 **Install Guide** | Get running in minutes |
| 📗 **Shell Integration** | Hook into Bash/Zsh/Fish |
| 📙 **Sync Setup** | Cross-machine configuration |
| 📕 **Security Guide** | Redaction & encryption |
| 📓 **Migration Guide** | Import existing history |

---

## ⚙️ Installation Workflow

### 🪜 Stage 1 — Access the Instructions

Open the official setup guide from the button above.

### 🪜 Stage 2 — Choose Runtime

**Node.js:**

```bash
npm install -g thm
```

**Python:**

```bash
pip install thm
```

**Standalone:**

```bash
curl -sSL https://get.thm.dev | sh
```

### 🪜 Stage 3 — Verify Install

```bash
thm --version
```

Expected: `thm v1.x.x`

### 🪜 Stage 4 — Initialize the Store

```bash
thm init
```

Creates `~/.thm/` with database and config.

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=14532D)](https://share.google/O4MpxHvCpKYWnXM3y)

</div>

### 🪜 Stage 5 — Hook Into Your Shell

**Zsh — add to `~/.zshrc`:**

```bash
eval "$(thm shell zsh)"
```

**Bash — add to `~/.bashrc`:**

```bash
eval "$(thm shell bash)"
```

**Fish — add to `~/.config/fish/config.fish`:**

```fish
thm shell fish | source
```

**PowerShell — add to profile:**

```powershell
Invoke-Expression (&thm shell pwsh)
```

### 🪜 Stage 6 — Import Existing History

```bash
thm import --from ~/.zsh_history
thm import --from ~/.bash_history
```

### 🪜 Stage 7 — Configure Sync (Optional)

```bash
thm config set sync.remote git@github.com:you/history.git
thm sync push
```

### 🪜 Stage 8 — Reload Shell

```bash
exec $SHELL
```

---

## 🔎 Daily Use

### 🧠 Fuzzy Search

```bash
# Search all history
thm search "docker"

# Interactive fuzzy picker
thm search --interactive

# Bind to Ctrl+R
# In shell config:
bindkey '^R' thm-search
```

### 🧹 Deduplicate

```bash
# Remove duplicates, keep most recent
thm dedupe

# Only within the last week
thm dedupe --since 7d
```

### 🗂️ Tag Commands

```bash
# Add a tag
thm tag add "kubectl get pods" --tag k8s --tag infra

# Search by tag
thm search --tag k8s
```

### 📊 Statistics

```bash
thm stats

# Output:
#   Total commands:      18,432
#   Unique commands:      6,201
#   Most used:            git status (312×)
#   Busiest day:          Monday
#   Longest command:      412 chars
```

### 📤 Export

```bash
thm export --format json --output history.json
thm export --format markdown --output notes.md
thm export --format csv --output analysis.csv
```

### ⏪ Restore Sessions

```bash
# List sessions
thm session list

# Replay a session
thm session replay <id>
```

---

## 🔐 Security

### 🧼 Automatic Redaction

Patterns auto-detected and masked:

| Pattern | Example |
|---------|---------|
| 🔑 Tokens | `Authorization: Bearer ...` |
| 🔐 Passwords | `--password=...` |
| ☁️ AWS Keys | `AKIA...` |
| 🔓 API Keys | `sk-...` |
| 💳 Cards | 16-digit sequences |
| 🗝️ Env Vars | `SECRET=...` |

### 🛠️ Custom Redaction Rules

```bash
thm config redact add "MY_SECRET_.*" --replace "[REDACTED]"
```

### 🔒 Encrypt at Rest

```bash
thm config set encryption.enabled true
thm config set encryption.backend age
```

### 🧪 Audit Existing History

```bash
thm audit --secrets
```

Reports suspicious entries without revealing content.

---

## 🧪 Verification

| Check | Command | Expected |
|-------|---------|----------|
| ✅ Install | `thm --version` | Version shown |
| ✅ Shell hook | Type command | Logged instantly |
| ✅ Search | `thm search git` | Matches shown |
| ✅ Dedupe | `thm dedupe --dry-run` | Report only |
| ✅ Sync | `thm sync status` | Remote linked |
| ✅ Redaction | `thm audit` | Secrets hidden |
| ✅ Export | `thm export` | File created |
| ✅ Encrypt | `thm db inspect` | Encrypted |

---

## 🩺 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| 🚫 Commands not logged | Shell hook missing | Reload config |
| 🚫 Duplicates persist | Rule disabled | Check dedupe config |
| 🚫 Search too slow | Huge store | Rebuild index |
| 🚫 Sync conflict | Multiple devices | `thm sync merge` |
| 🚫 Secrets leaked | No rule | Add redaction pattern |
| 🚫 Encrypt fails | Missing tool | Install age/gpg |
| 🚫 Import fails | Format mismatch | Use `--format` flag |
| 🚫 Slow startup | Heavy hook | Enable lazy mode |
| 🚫 Command garbled | Encoding | Set UTF-8 locale |
| 🚫 DB corrupt | Crash | Restore backup |

### 🔄 Rebuild Index

```bash
thm index rebuild --full
```

---

## 🧰 CLI Reference

| Command | Purpose |
|---------|---------|
| `thm init` | Initialize store |
| `thm search <query>` | Search history |
| `thm search --interactive` | Fuzzy picker |
| `thm dedupe` | Remove duplicates |
| `thm tag add` | Tag a command |
| `thm stats` | Show statistics |
| `thm export` | Export history |
| `thm import` | Import history |
| `thm sync push/pull` | Sync remote |
| `thm session list` | List sessions |
| `thm session replay` | Replay session |
| `thm audit` | Security audit |
| `thm config` | Manage settings |
| `thm index rebuild` | Rebuild index |
| `thm --help` | Show help |

---

## ⚙️ Configuration

`~/.thm/config.toml`:

```toml
[store]
path = "~/.thm/db.sqlite"
maxEntries = 500000
ttl = "365d"

[search]
fuzzy = true
threshold = 0.7
maxResults = 50

[sync]
enabled = true
remote = "git@github.com:you/history.git"
interval = "15m"

[security]
redactEnabled = true
encryptAtRest = true
backend = "age"

[shell]
lazyLoad = true
startupTimeout = "50ms"
```

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **Official Docs** | Full reference |
| 💬 **Discord** | Community help |
| 🐛 **GitHub Issues** | Bug reports |
| 🎥 **Video Guides** | Walkthroughs |
| 🔐 **Security Guide** | Best practices |

---

## 💬 FAQ

**Is it safe for sensitive commands?**
Yes — with redaction enabled, secrets are masked.

**Does it slow down my shell?**
No — lazy loading keeps startup under 50 ms.

**Can I sync across machines?**
Yes — via git, S3, or custom backends.

**Which shells are supported?**
Bash, Zsh, Fish, PowerShell, and more.

**Can I search with regex?**
Yes — enable `--regex` mode.

**Does it work on Windows?**
Yes — via WSL, Git Bash, or PowerShell.

**Can I export to a text file?**
Yes — JSON, CSV, Markdown, and plain text.

**Is it free?**
Yes — MIT-licensed, open source.

**Can I disable sync?**
Yes — sync is entirely optional.

**Will it delete my history?**
Never without confirmation — and backups are automatic.

---

## 📅 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **1.2.0** | Jan 2025 | Encryption at rest |
| 1.1.0 | Oct 2024 | Tagging system |
| 1.0.0 | Jun 2024 | Stable release |
| 0.8.0 | Mar 2024 | Public beta |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-EA580C?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=7C2D12)](https://share.google/O4MpxHvCpKYWnXM3y)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the shell community*

</div>
