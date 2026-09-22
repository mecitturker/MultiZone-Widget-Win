# MultiZone-Widget-Win 🕒🌐

![Windows 10](https://img.shields.io/badge/Windows-10-blue?logo=windows)
![Windows 11](https://img.shields.io/badge/Windows-11-0078D4?logo=windows11)
![Windows Server](https://img.shields.io/badge/Windows_Server-2016%2B-0078D4?logo=windows-server)
![.NET 8.0](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**MultiZone-Widget-Win** is a lightweight, customizable C# WPF desktop widget application designed for Windows 10, Windows 11, and Windows Server. It allows users to place transparent, sticker-like world clocks directly onto their desktop screen.

---

## ✨ Key Features

* 🎨 **Custom Color & Opacity:** Fully customizable color palette and transparency (Opacity) settings for each clock sticker.
* 🚩 **Country Flags & Offline Caching:** Automatic ISO country code mapping with a hybrid caching system that downloads flag icons and stores them locally for offline availability.
* 🖥️ **Desktop Layer (Z-Order) Control:** Pin widgets directly to the desktop wallpaper level (`HWND_BOTTOM`) or set individual clocks to "Always on Top".
* 🔍 **Searchable TimeZone Picker:** Quickly search through global time zones with auto-filling city and country code fields.
* 📌 **Taskbar Thumbnail Preview Support:** Hover over the taskbar icon to see live preview cards of all open clock widgets and bring any widget to the front with a single click.
* 🚀 **Launch at Startup:** Built-in Windows Registry integration for automatic system startup.
* 💾 **JSON-Based Storage:** Persists all clock positions, dimensions, colors, and user preferences cleanly in `%AppData%`.

---

## 🛠️ Build & Installation

### Prerequisites
* [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
* Visual Studio 2022 (with WPF Desktop Development workload installed)

### Building from Source
```bash
# Clone the repository
git clone [https://github.com/mecitturker/MultiZone-Widget-Win.git](https://github.com/mecitturker/MultiZone-Widget-Win.git)

# Navigate into the project folder
cd MultiZone-Widget-Win

# Build and run
dotnet run
