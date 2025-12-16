# 📂 Smart File Organizer / Akıllı Dosya Düzenleyici
![Python](https://img.shields.io/badge/Python-3.x-blue.svg) ![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-green.svg) ![License](https://img.shields.io/badge/License-MIT-yellow.svg)

[🇹🇷 Türkçe Rehber](#-türkçe-kullanım-rehberi) | [🇺🇸 English Guide](#-english-user-guide)

# 🇹🇷 Türkçe Kullanım Rehberi

**Smart File Organizer**, karmaşık ve dağınık klasörlerinizi saniyeler içinde düzenleyen, Python tabanlı modern bir masaüstü uygulamasıdır. Dosyalarınızı türlerine göre (Video, Müzik, Belge vb.) analiz eder ve otomatik olarak oluşturduğu klasörlere taşır.

## 🚀 Kurulum ve İlk Çalıştırma (Önemli!)

Güvenlik ve dağıtım kolaylığı nedeniyle proje dosyaları `.txt` uzantılı olarak gelmektedir. Uygulamayı çalıştırmak için **ilk kez indirirken** aşağıdaki adımları sırasıyla uygulamanız gerekmektedir:

### 1. Dosya Uzantılarını Düzenleme
İndirdiğiniz klasörde aşağıdaki dosya adı değişikliklerini yapın:

1.  Eğer klasörde hali hazırda `main.py` veya `CALISTIR.bat` varsa bunları **silin**.
2.  **`main.txt`** dosyasının adını 👉 **`main.py`** olarak değiştirin.
3.  **`CALISTIR.txt`** dosyasının adını 👉 **`CALISTIR.bat`** olarak değiştirin.

*(Not: Windows'ta dosya uzantılarını göremiyorsanız: Dosya Gezgini > Görünüm > "Dosya adı uzantıları" kutucuğunu işaretleyin.)*

### 2. Başlatma
*   **`CALISTIR.bat`** dosyasına çift tıklayın.
*   Bu işlem otomatik olarak gerekli kütüphaneleri (`customtkinter` vb.) yükleyecek ve uygulamayı başlatacaktır.

---

## 📖 Nasıl Kullanılır?

1.  **Klasör Seçimi:** Sağ üstteki **"Select Folder"** butonuna tıklayın ve düzenlemek istediğiniz dağınık klasörü seçin.
2.  **Analiz:** Uygulama klasörü tarar ve kaç dosya bulduğunu log ekranında gösterir.
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

For distribution purposes, the executable scripts are provided as `.txt` files. You must follow these steps to rename them before running the app:

### 1. Preparing the Files
In the project folder, follow these renaming steps:

1.  If `main.py` or `CALISTIR.bat` already exist from a previous attempt, **delete them**.
2.  Rename **`main.txt`** to 👉 **`main.py`**.
3.  Rename **`CALISTIR.txt`** to 👉 **`CALISTIR.bat`**.

*(Note: If you cannot see file extensions in Windows: File Explorer > View > Check "File name extensions".)*

### 2. Running the App
*   Double-click on **`CALISTIR.bat`**.
*   This script will automatically install the required libraries (like `customtkinter`) and launch the application.

---

## 📖 How to Use

1.  **Select Folder:** Click the **"Select Folder"** button at the top right and choose the messy directory you want to organize.
2.  **Analyze:** The app scans the directory and logs the number of files found.
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
MIT License. Free to use and modify.
