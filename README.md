# dev-dotfiles

These are my personal dotfiles, managed with [chezmoi](https://www.chezmoi.io/).  
It includes shell configuration, editor settings, CLI tools, and helper scripts.

> ⚠️ **WARNING:** This repo is part of a larger monorepo structure.  
> If you clone this repo on its own, **some symlinks may break**.

---

## 📦 Repository Structure

```plaintext
dev-dotfiles/               # <== This repo (chezmoi-managed)
├── dot_config/
├── private_dot_local/
├── run-dev-dotfiles             # Main setup script
└── .chezmoiignore
```

---

## ✅ Recommended Usage: Use the Full Monorepo

To ensure everything works correctly, use the full monorepo:  
🔗 https://github.com/LuckyBastrd/dev/tree/master

---

## 💡 Using This Repo Standalone

Clone and run (HTTPS):

```bash
git clone https://github.com/LuckyBastrd/dev-dotfiles.git && cd dev-dotfiles && ./run-dev-dotfiles
```

Or use SSH:

```bash
git clone git@github.com:LuckyBastrd/dev-dotfiles.git && cd dev-dotfiles && ./run-dev-dotfiles
```

> Note: Some features may not work due to broken symlinks if used standalone.

---

## 🚀 Manual Usage

To run manually after cloning:

```bash
./run-dev-dotfiles
```

This will:

- Install chezmoi if not already present
- Apply all dotfiles in this repo
- Create symlinks and configure your environment

---
