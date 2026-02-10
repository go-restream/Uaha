<p align="center">
  <img src="assets/imgs/logo.png" alt="Uaha Logo" width="120" height="120">
</p>

<p align="center">
  <a href="https://github.com/go-restream/Uaha/stargazers">
    <img src="https://img.shields.io/github/stars/go-restream/Uaha" alt="GitHub Stars">
  </a>
  <a href="https://github.com/go-restream/Uaha/issues">
    <img src="https://img.shields.io/github/issues/go-restream/Uaha" alt="GitHub Issues">
  </a>
  <a href="https://github.com/go-restream/Uaha/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/go-restream/Uaha" alt="GitHub License">
  </a>
</p>

<p align="center">
  English | <a href="README_zh_CN.md">简体中文</a>
</p>

<h1 align="center">Uaha</h1>

<p align="center">
  <b>Modern AI Model Service Management Desktop Application</b>
</p>

<p align="center">
  A cross-platform desktop application built with native technologies based on the Aha engine, providing a clean and intuitive interface for managing AI models and API services.
</p>

<p align="center">
  <img src="assets/uaha.gif" alt="Uaha Interface Demo" width="400">
</p>

---

## 📢 Changelog

### v0.1.0-beta (2026-02-11)

#### 🎉 First Public Beta Release

**Core Features**:
- Model Management: Browse, download, delete AI models with real-time progress display
- API Service Management: Create, start, stop multiple model service instances
- Configuration Management: Aha path configuration, model download settings, theme switching
- Cross-Platform Architecture: Built with Wails v3 native technology stack

**Platform Support**:
- macOS ✅ | Windows 🚧 | Linux 🚧

[View Full Changelog →](docs/changelog.md)

---

## 🚀 Quick Start

### Installation

1. **Download Installer** - Visit [GitHub Releases](https://github.com/go-restream/Uaha/releases)
2. **Run Installer** - Follow platform-specific instructions
3. **Launch App** - Configure Aha engine path on first run

### Build from Source

```bash
# Clone repository
git clone https://github.com/go-restream/Uaha.git && cd Uaha

# Build application
wails3 build
wails3 package GOOS=darwin

```

[Detailed Installation Guide →](docs/getting-started.md)

---

## ✨ Key Features

- **Model Management** - One-click download and manage AI models with real-time progress tracking
- **Service Management** - Create and manage multiple API service instances with resource monitoring
- **Flexible Configuration** - Rich customization options including themes and appearance settings
- **Cross-Platform** - Supports major operating systems like macOS, Windows, Linux
- **Modern UI** - Beautiful interface built with Vue 3 and Tailwind CSS

---

## 📚 Documentation

| Document | Description |
|----------|-------------|
| [Quick Start](docs/getting-started.md) | Installation and first-time setup guide |
| [User Guide](docs/user-guide.md) | Detailed feature usage instructions |
| [Development Guide](docs/development.md) | Architecture design and contributing |
| [FAQ](docs/faq.md) | FAQ and troubleshooting |
| [Changelog](docs/changelog.md) | Version history |

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| **Backend** | Go 1.25+ |
| **Framework** | Wails v3 |
| **Frontend** | Vue 3 + Vite |
| **Styling** | Tailwind CSS |
| **State** | Pinia |

---

## 🤝 Contributing

Contributions are welcome! Please check the [CONTRIBUTING.md](CONTRIBUTING.md) file to learn how to contribute.

---

## 📄 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

---

## 🔗 Related Links

- [Wails v3 Documentation](https://v3.wails.io)
- [Aha Engine](https://github.com/jhqxxx/aha)
- [Issue Tracker](https://github.com/go-restream/Uaha/issues)

---

<p align="center">
  <b>Uaha</b> © 2025 xiaoyang · Built with ❤️ and Wails
</p>
