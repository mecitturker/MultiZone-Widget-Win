# MultiZone-Widget-Win 🕒🌐

![Windows 10](https://img.shields.io/badge/Windows-10-blue?logo=windows)
![Windows 11](https://img.shields.io/badge/Windows-11-0078D4?logo=windows11)
![Windows Server](https://img.shields.io/badge/Windows_Server-2016%2B-0078D4?logo=windows-server)
![.NET 8.0](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**MultiZone-Widget-Win**, Windows 10, Windows 11 ve Windows Server işletim sistemleri için geliştirilmiş; masaüstünüze şeffaf, özelleştirilebilir ve canlı dünya saatleri eklemenizi sağlayan hafif (lightweight) bir C# WPF masaüstü widget uygulamasıdır.

---

## ✨ Öne Çıkan Özellikler

* 🎨 **Özelleştirilebilir Renk ve Şeffaflık:** Her bir saat dilimi için özel renk paleti ve Opacity (şeffaflık) ayarı.
* 🚩 **Otomatik Ülke Bayrağı ve Önbellekleme:** TimeZone seçiminde otomatik dolan ülke kodları ve çevrimdışı (offline) çalışabilen hibrit bayrak önbellekleme sistemi.
* 🖥️ **Masaüstüne Entegre Katman (Z-Order):** Sticker'ları doğrudan masaüstü seviyesinde tutma veya diğer pencerelerin üstüne sabitleme (Always on Top) imkanı.
* 🔍 **Arama Yapılabilir TimeZone Listesi:** Dünya üzerindeki tüm saat dilimleri arasında hızlı arama ve otomatik şehir/ülke eşleştirme.
* 📌 **Görev Çubuğu Önizleme Support:** Görev çubuğundaki simgenin üzerine gelindiğinde tüm saatleri canlı önizleme kartları şeklinde görme ve tek tıkla öne getirme.
* 🚀 **Sistem Başlangıcında Çalışma:** Windows Registry entegrasyonu ile otomatik başlama desteği.
* 💾 **JSON Tabanlı Kayıt Sistemi:** Tüm saat konumlama, renk ve tercihlerin yerel `%AppData%` dizininde saklanması.

---

## 📸 Ekran Görüntüleri

| Ana Dashboard | Masaüstü Sticker Widget'ları |
| :---: | :---: |
| *Yönetim Paneli ve Saat Listesi* | *Şeffaf Masaüstü Saatleri ve Bayraklar* |

---

## 🛠️ Kurulum ve Derleme (Build)

### Gereksinimler
* [NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
* Visual Studio 2022 (WPF Desktop Development yüklenmiş olmalıdır)

### Kaynak Koddan Derleme
```bash
# Repoyu klonlayın
git clone [https://github.com/mecitturker/MultiZone-Widget-Win.git](https://github.com/mecitturker/MultiZone-Widget-Win.git)

# Proje dizinine gidin
cd MultiZone-Widget-Win

# Projeyi derleyin ve çalıştırın
dotnet run
