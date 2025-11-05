
# GenP

## 📋 Table of Contents

- [⚖️ Legal Disclaimer](#️-legal-disclaimer)
- [❓ About GenP](#-about-genp)
- [✅ System Requirements](#-system-requirements)
- [📥 Downloads](#-downloads)
- [📖 Documentation](#-documentation)
- [⚠️ Known Limitations](#️-known-limitations)
- [🌐 Community](#-community)

---

## ⚖️ Legal Disclaimer

> [!IMPORTANT]
>
> This mirror repository **only** exists following the takedown of the reddit community. The owner and maintainer(s) of this repository are:
> - **NOT affiliated** with the official/unofficial GenP community
> - **DO NOT endorse** copyright infringement or piracy
> - Provide this for **educational and research purposes only**
>
> **Terms of Use:**
> - This tool is strictly for **educational and research purposes only**
> - Users assume **full responsibility** for any use
> - **No warranties or guarantees** provided for any use
> - Owner/maintainers accept **no liability** for any misuse

---

> [!WARNING]
> **NEVER DOWNLOAD GenP FROM:**
> 
> | Source Type | Examples |
> |-------------|----------|
> | **Video Platforms** | YouTube tutorials, TikTok, video descriptions |
> | **Code Hosting** | GitHub (always verify the legitimacy of source-codes and/or binaries before running) |
> | **Social Media** | Discord servers, Telegram channels, Reddit posts |
> | **File Sharing** | MediaFire, Mega.nz, torrent sites, P2P networks |
> | **Third-Party Sites** | Any site with ads, surveys, wait times, or extra clicks |
>
> **These sources commonly contain:**
> - Embedded malware, trojans, and ransomware
> - Modified versions with backdoors
> - Fake installers bundled with adware
> - Outdated versions causing system damage
> - Password stealers and keyloggers
>
> **Red Flags (You're on a fake/dangerous site if you see):**
> - Extra clicks, surveys, or tasks required before download
> - Requests for payment or donations
> - Multiple download buttons (ads disguised as downloads)
> - Shortened URLs or redirect chains
> - Claims of "premium" or "pro" versions
> - Requests for personal information

---

## ❓ About GenP

**GenP** (Generic Patcher) is a Windows-based utility designed to extend Creative Cloud trial periods indefinitely by modifying system files and resetting trial timers.

### 🌟 Key Features

- ✅ **One-Click Patching** - Simple, automated process
- ✅ **Wide Compatibility** - Supports CC 2019-2025 apps
- ✅ **Update Support** - Works with Creative Cloud updates (re-patch required)
- ✅ **AGS Removal** - Automatically removes Genuine Service
- ✅ **Community-Driven** - Active support and regular updates
- ✅ **100% Free** - No payments, no donations, no subscriptions

---

## ✅ System Requirements

### 🟢 Fully Supported

<table>
<tr>
<td width="50%">

**Operating System**
- ✅ Windows 10 (64-bit)
- ✅ Windows 11 (64-bit)
- ✅ Official Microsoft builds only

</td>
<td width="50%">

**Hardware**
- ✅ x64/AMD64 CPU (Intel/AMD)
- ✅ 100MB+ free disk space
- ✅ Administrator privileges
- ✅ Internet (for CC installation only)

</td>
</tr>
</table>

### 🔴 NOT Supported (may/may not work)

<details>
<summary><b>🚫 Incompatible Architectures</b></summary>

| Type | Examples | Why It Fails |
|------|----------|--------------|
| **ARM64** | Qualcomm Snapdragon X Elite/Plus | GenP requires native x64 for low-level patching |
| **Copilot+ PCs** | Surface Pro 11, Dell XPS 13 (2024+), HP Elite Folio | Use ARM processors |
| **Windows on ARM** | All devices with Snapdragon processors | Emulation layer breaks patching |
| **x86 (32-bit)** | Old systems, legacy hardware | GenP only supports 64-bit |

**Technical Explanation:** GenP modifies binaries at a low level. Windows on ARM uses Prism emulation for x64 apps, which interferes with patching. Additionally, Adobe is transitioning to native ARM64 builds with no x64 binaries to patch.

</details>

<details>
<summary><b>🚫 Incompatible Operating Systems</b></summary>

| OS | Alternative Solution |
|----|---------------------|
| **macOS** (all versions) | Use [Zii](https://adobezii.com) or [Cmacked](https://cmacked.com) |
| **Linux** (Ubuntu, Kali, Arch, etc.) | No native solution available |
| **Windows 7/8/8.1** | Upgrade to Windows 10/11 |

</details>

<details>
<summary><b>🚫 Modified Windows Editions</b></summary>

❌ **These Windows variants are NOT supported:**

- **LTSC** (Long-Term Servicing Channel) - Missing system components
- **IoT** (Internet of Things editions) - Stripped functionality
- **Tiny10/Tiny11** - Removed critical Windows features
- **GhostSpectre** - Heavily modified builds
- **Windows PE** (Preinstallation Environment) - Not a full OS
- **Debloated/Custom Builds** - Missing dependencies
- **Windows Insider Preview** - Unstable, no support

**Why?** GenP modifies applications directly, so all official system requirements apply. Modified Windows editions often lack necessary system libraries, registry entries, and services that GenP and apps depend on.

</details>

### ⚙️ Additional Requirements

- **Creative Cloud** must be installed from [Official website](https://creativecloud.adobe.com)
- **Antivirus exclusions** configured (GenP triggers false positives)
- **Dummy account** recommended (never use your primary account)
- **AGS (Genuine Service)** will be removed by GenP

---

## 📥 Downloads

### Available in This Repository

| Type | Location | Description |
|------|----------|-------------|
| **Binaries** | `/Releases/` | Pre-compiled executables |
| **Source Codes** | `/SRCs/` | Complete source files |
| **Build Tools** | Included in source | Development utilities |

### Version Information

- **Latest Stable:** v3.7.1 (recommended, see [Releases](https://github.com/Cur10s1tyByt3/GenP/releases) for more info/download)
- **Legacy Versions:** See [Releases](https://github.com/Cur10s1tyByt3/GenP/tree/main/Releases)/[SRCs](https://github.com/Cur10s1tyByt3/GenP/tree/main/SRCs) for older builds/sources

---

## 📖 Documentation

### Resources

<table>
<tr>
<td width="50%">

**📚 Main Guides**
- [Installation Guide](https://wiki.dbzer0.com/genp-guides/guide)
- [GenP Setup & Best Practices](https://wiki.dbzer0.com/genp-guides/genp-setup)
- [Monkrus Setup Guide](https://wiki.dbzer0.com/genp-guides/monkrus-setup)
- [Full System Cleaning](https://wiki.dbzer0.com/genp-guides/cleaning)

</td>
<td width="50%">

**🔧 Support Resources**
- [Troubleshooting Guide](https://wiki.dbzer0.com/genp-guides/troubleshoot)
- [Compatibility List](https://wiki.dbzer0.com/genp-guides/compatibility-list)
- [GenP vs Monkrus Comparison](https://wiki.dbzer0.com/genp-guides/genp-vs-monkrus)
- [Community Rules](https://wiki.dbzer0.com/genp-guides/rules)

</td>
</tr>
</table>

---

## ⚠️ Known Limitations

### AI Features Require Genuine Subscription

<table>
<tr>
<th>❌ Does NOT Work</th>
<th>✅ Still Works</th>
</tr>
<tr>
<td valign="top">

**Cloud-Based AI (Requires Subscription):**
- Generative Fill (Firefly mode)
- Firefly integration
- AI Background Removal (cloud)
- Neural Filters (cloud processing)
- Generative AI text effects (Illustrator)
- AI audio enhancement (Premiere/Audition)
- Content Credentials
- Creative Cloud Libraries sync

</td>
<td valign="top">

**Local AI/Traditional Tools:**
- Content-Aware Fill (non-Firefly mode)
- Sensei ML tools (local)
- Object Selection & Select Subject
- Sky Replacement
- Neural Filters (local models only)
- Traditional editing tools
- Most Photoshop features

</td>
</tr>
</table>

### Workarounds

<details>
<summary><b>🔧 Photoshop Remove Tool Workaround</b></summary>

In Photoshop, set Remove Tool mode to **"Generative AI Off"**. This reverts to Sensei (traditional machine learning) instead of cloud-based Firefly, allowing local processing.

**Note:** Illustrator, Premiere Pro, InDesign, Lightroom, After Effects, and Express do NOT offer Generative AI toggle options - their AI features are fully cloud-based and require subscriptions.

</details>

### Update Requirements

- Apps require **re-patching after every update**
- Creative Cloud may push updates automatically
- Always **keep GenP.exe** for future re-patches
- Updates occur monthly or bi-monthly

---

## 🌐 Community

### Support Forum/GC

<table>
<tr>
<td align="center" width="33%">

### 💬 Forum
**[lemmy.dbzer0.com/c/GenP](https://lemmy.dbzer0.com/c/GenP)**

📝 Long-form discussions<br>
📚 Guides and tutorials<br>
🔍 Searchable archive<br>
📌 Announcements

</td>
<td align="center" width="33%">

### 🗨️ Chat
**[stoat.chat/invite/p3V3ETD4](https://stoat.chat/invite/p3V3ETD4)**

⚡ Real-time support<br>
👥 Community help<br>
🤝 Quick questions<br>
💡 Tips and tricks

</td>
<td align="center" width="33%">

### 📖 Wiki
**[wiki.dbzer0.com/genp-guides](https://wiki.dbzer0.com/genp-guides)**

📘 Complete documentation<br>
🔧 Troubleshooting guides<br>
📋 Compatibility lists<br>

</td>
</tr>
</table>

---

**This tool is intended for educational and research purposes only! Use at your own risk.**
