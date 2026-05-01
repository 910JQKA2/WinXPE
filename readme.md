# WinXPE

<div align="center">

**Một bản WinPE tùy chỉnh, nhẹ và đầy đủ công cụ cho việc cứu hộ & cài đặt Windows.**

**A lightweight, customized WinPE packed with essential tools for system recovery & Windows installation.**

</div>

---

## 📖 Giới thiệu / Introduction

**Tiếng Việt:**
WinXPE là một bản Windows Preinstallation Environment (WinPE) được tùy chỉnh, sử dụng **WinXShell** làm shell chính thay cho Explorer mặc định. WinXPE được thiết kế để nhẹ, nhanh và đủ công cụ cho các tác vụ cứu hộ hệ thống, quản lý ổ đĩa và cài đặt Windows.

**English:**
WinXPE is a customized Windows Preinstallation Environment (WinPE) using **WinXShell** as the primary shell instead of the default Explorer. WinXPE is designed to be lightweight, fast, and packed with essential tools for system recovery, disk management, and Windows installation.

---

## ✨ Tính năng / Features

**Tiếng Việt:**
- 🖥️ Shell WinXShell hiện đại, thay thế CMD mặc định
- 🛠️ Bộ công cụ đầy đủ cho cứu hộ & cài Windows
- 📦 Hỗ trợ .NET Framework cơ bản (WinPE-NetFX)
- 🌐 Hỗ trợ kết nối mạng (PENetwork)
- 💾 Hỗ trợ Explorer++ làm file manager
- ⚡ Khởi động nhanh, nhẹ

**English:**
- 🖥️ Modern WinXShell replacing default CMD
- 🛠️ Full toolkit for recovery & Windows installation
- 📦 Basic .NET Framework support (WinPE-NetFX)
- 🌐 Network connectivity support (PENetwork)
- 💾 Explorer++ as file manager
- ⚡ Fast boot, lightweight

---

## 🧰 Danh sách ứng dụng / Included Applications

| Ứng dụng / App | Chức năng / Function |
|---|---|
| **AOMEI Backupper** | Backup & restore hệ thống / System backup & restore |
| **AOMEI Partition Assistant** | Quản lý phân vùng / Partition management |
| **Dism++ x64** | Tích hợp driver, cài Windows / Driver integration, Windows setup |
| **WinNTSetup x64** | Cài đặt Windows / Windows installation |
| **PENetwork** | Kết nối mạng trong PE / Network connectivity in PE |
| **CrystalDiskInfo** | Kiểm tra sức khỏe ổ đĩa / Disk health check |
| **BOOTICE** | Sửa bootloader / Bootloader repair |
| **Snappy Driver Installer** | Cài driver nhanh / Quick driver installation |
| **ntpwedit** | Reset mật khẩu Windows / Windows password reset |
| **Recuva** | Khôi phục dữ liệu / Data recovery |
| **ShowKeyPlus** | Lấy product key Windows / Retrieve Windows product key |
| **CPU-Z** | Thông tin phần cứng / Hardware information |
| **Explorer++** | Trình quản lý file / File manager |
| **7-Zip** | Nén & giải nén file / File compression & extraction |

---

## 🚀 Hướng dẫn sử dụng / How to Use

**Tiếng Việt:**
1. Tải file ISO từ trang [Releases](../../releases)
2. Ghi ISO ra USB bằng **Rufus**, **Ventoy**, hoặc tool tương tự
   - Rufus: Chọn file ISO, chọn USB, nhấn Start
   - Ventoy: Copy file ISO vào USB đã cài Ventoy, chọn khi boot
3. Boot máy từ USB
4. WinXShell sẽ tự khởi động, chọn công cụ cần dùng từ desktop

**English:**
1. Download the ISO from the [Releases](../../releases) page
2. Flash the ISO to a USB drive using **Rufus**, **Ventoy**, or similar tool
   - Rufus: Select the ISO file, select USB, click Start
   - Ventoy: Copy the ISO file to a Ventoy-installed USB, select it at boot
3. Boot your machine from the USB
4. WinXShell will start automatically, select the tool you need from the desktop

---

## ⚙️ Yêu cầu hệ thống / System Requirements

| | Tối thiểu / Minimum | Khuyến nghị / Recommended |
|---|---|---|
| **CPU** | x64 | x64, 2+ cores |
| **RAM** | 4 GB | 4 GB+ |
| **USB** | 4 GB | 4 GB |
| **Boot** | UEFI / Legacy | UEFI |

---

## 📝 Ghi chú / Notes

**Tiếng Việt:**
- WinXPE được build dựa trên Windows ADK & WinPE Add-ons
- Tất cả ứng dụng đi kèm là bản **miễn phí (Free)**

**English:**
- WinXPE is built using Windows ADK & WinPE Add-ons
- All included applications are **free versions**
---

## 🙏 Credits

- [WinXShell](https://github.com/torchgm/WinXShell) — Shell chính / Primary shell
- [Explorer++](https://explorerplusplus.com/) — File manager
- [Windows ADK](https://learn.microsoft.com/en-us/windows-hardware/get-started/adk-install) — Build environment

---

<div align="center">

Made with ❤️ | WinXPE Project

</div>