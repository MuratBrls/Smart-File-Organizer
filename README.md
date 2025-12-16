# 📂 Smart File Organizer / Akıllı Dosya Düzenleyici

![Python](https://img.shields.io/badge/Python-3.x-blue.svg) ![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-green.svg) ![License](https://img.shields.io/badge/License-MIT-yellow.svg)

[🇹🇷 Türkçe Rehber](#-türkçe-kullanım-rehberi) | [🇺🇸 English Guide](#-english-user-guide)

---

# 🇹🇷 Türkçe Kullanım Rehberi

**Smart File Organizer**, karmaşık ve dağınık klasörlerinizi saniyeler içinde düzenleyen, Python tabanlı modern bir masaüstü uygulamasıdır. Dosyalarınızı türlerine göre (Video, Müzik, Belge vb.) analiz eder ve otomatik olarak oluşturduğu klasörlere taşır.

## 🚀 Kurulum ve İlk Çalıştırma (Önemli!)

**Güvenlik önlemleri nedeniyle**, proje dosyaları varsayılan olarak `.txt` (metin dosyası) formatında sunulmuştur. Uygulamayı çalıştırmak için lütfen aşağıdaki iki dosyayı manuel olarak yeniden adlandırın:

### 1. Dosya İsimlerini Değiştirme
İndirdiğiniz klasörün içinde:

1.  **`main.txt`** dosyasının adını 👉 **`main.py`** yapın.
2.  **`CALISTIR.txt`** dosyasının adını 👉 **`CALISTIR.bat`** yapın.

*(İpucu: Eğer dosya uzantılarını göremiyorsanız, klasör penceresinde "Görünüm" sekmesine gidin ve "Dosya adı uzantıları" kutucuğunu işaretleyin.)*

### 2. Başlatma
*   İsim değişikliğini yaptıktan sonra **`CALISTIR.bat`** dosyasına çift tıklayın.
*   Program otomatik olarak gerekli kütüphaneleri yükleyecek ve açılacaktır.

---

## 📖 Nasıl Kullanılır?

1.  **Klasör Seçimi:** Sağ üstteki **"Select Folder"** butonuna tıklayın ve düzenlemek istediğiniz dağınık klasörü seçin.
2.  **Analiz:** Uygulama klasörü tarar ve durumu size bildirir.
3.  **Başlat:** **"Start Organization"** butonuna basın.
4.  **Sonuç:** Dosyalarınız türlerine göre ayrıştırılırken ilerleme çubuğunu izleyebilirsiniz.

## 🗂️ Klasör Kategorileri

Uygulama seçilen dizinde şu klasörleri oluşturur ve dosyaları dağıtır:

| Klasör | İçerik |
| :--- | :--- |
| **Videolar** | `mp4`, `mov`, `avi`, `mkv` vb. |
| **Muzik_Ses** | `mp3`, `wav`, `flac`, `aac` vb. |
| **Gorseller** | `jpg`, `png`, `gif`, `webp` vb. |
| **Belgeler** | `pdf`, `docx`, `txt`, `xlsx` vb. |
| **Arsivler** | `zip`, `rar`, `7z` vb. |
| **Kurulum_Dosyalari** | `exe`, `msi`, `iso` |
| **Diger_Dosyalar** | Tanımlanamayan diğer dosyalar |

---
---

# 🇺🇸 English User Guide

**Smart File Organizer** is a modern, Python-based desktop tool designed to organize your chaotic folders in seconds. It analyzes files by extension and automatically moves them into categorized folders (Videos, Images, Documents, etc.).

## 🚀 Installation & Setup (Important!)

**Due to security measures**, the executable files are provided as `.txt` (text files). To run the application, you must manually rename the following two files:

### 1. Renaming the Files
Inside the downloaded folder:

1.  Rename **`main.txt`** to 👉 **`main.py`**.
2.  Rename **`CALISTIR.txt`** to 👉 **`CALISTIR.bat`**.

*(Tip: If you cannot see file extensions like .txt, go to the "View" tab in your folder window and check "File name extensions".)*

### 2. Running the App
*   After renaming, double-click on **`CALISTIR.bat`**.
*   This script will automatically install the required libraries and launch the application.

---

## 📖 How to Use

1.  **Select Folder:** Click the **"Select Folder"** button at the top right and choose the messy directory you want to organize.
2.  **Analyze:** The app scans the directory and prepares for organization.
3.  **Start:** Click the **"Start Organization"** button.
4.  **Done:** Watch the progress bar as your files are sorted instantly.

## 🗂️ Category Mapping

The app creates the following subfolders in your selected directory:

| Folder | Extensions |
| :--- | :--- |
| **Videolar** (Videos) | `mp4`, `mov`, `avi`, `mkv`, etc. |
| **Muzik_Ses** (Audio) | `mp3`, `wav`, `flac`, `aac`, etc. |
| **Gorseller** (Images) | `jpg`, `png`, `gif`, `webp`, etc. |
| **Belgeler** (Docs) | `pdf`, `docx`, `txt`, `xlsx`, etc. |
| **Arsivler** (Archives) | `zip`, `rar`, `7z`, etc. |
| **Kurulum_Dosyalari** (Setup)| `exe`, `msi`, `iso` |
| **Diger_Dosyalar** (Others) | Any unmatched files |

---

## 🛠️ Requirements
*   Python 3.x
*   Windows (Recommended for the .bat script), but `main.py` works on macOS/Linux if dependencies are installed manually.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Copyright (c) 2025 Murat
