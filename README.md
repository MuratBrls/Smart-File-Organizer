📂 Smart File Organizer (Python Desktop)
Modern, şık ve güçlü bir masaüstü dosya düzenleme aracı. Karmaşık klasörlerinizi saniyeler içinde analiz eder ve dosya türlerine göre (Video, Müzik, Görsel, Belge vb.) otomatik olarak kategorize edilmiş klasörlere ayırır.
![alt text](https://img.shields.io/badge/Python-3.x-blue.svg)
![alt text](https://img.shields.io/badge/GUI-CustomTkinter-green.svg)
![alt text](https://img.shields.io/badge/License-MIT-yellow.svg)
🌟 Özellikler
Modern Arayüz: CustomTkinter ile hazırlanmış şık "Karanlık Mod" (Dark Mode) tasarımı.
Akıllı Kategorilendirme: Dosyaları uzantılarına göre otomatik tanır ve ilgili klasörlere taşır.
Çakışma Önleme: Aynı isimde dosya varsa üzerine yazmaz, otomatik olarak yeniden adlandırır (örn: dosya_1.jpg).
Canlı İstatistikler: İşlenen, taşınan, atlanan ve hata veren dosya sayılarını anlık gösterir.
Detaylı Log Sistemi: Yapılan her işlemi (taşıma, hata, uyarı) zaman damgasıyla birlikte raporlar.
Güvenli: Sistem dosyalarını veya gizli dosyaları (örn: .git, .env) otomatik olarak atlar.
🗂️ Klasör Yapısı ve Desteklenen Uzantılar
Uygulama, seçtiğiniz klasörün içinde aşağıdaki alt klasörleri oluşturur ve dosyaları buraya dağıtır:
Klasör Adı	İçerdiği Dosya Türleri
🎥 Videolar	.mp4, .mov, .avi, .mkv, .webm, .flv
🎵 Muzik_Ses	.mp3, .wav, .aac, .flac, .ogg, .m4a
🖼️ Gorseller	.jpg, .jpeg, .png, .gif, .bmp, .svg, .heic, .webp
📄 Belgeler	.pdf, .docx, .txt, .xlsx, .pptx, .csv
📦 Arsivler	.zip, .rar, .7z, .tar, .gz
💾 Kurulum_Dosyalari	.exe, .msi, .iso
📂 Diger_Dosyalar	Yukarıdaki kategorilere girmeyen diğer tüm dosyalar.
🚀 Kurulum ve İlk Çalıştırma (Önemli!)
Projeyi bilgisayarınıza indirdiğinizde, güvenlik ve dosya bütünlüğü açısından dosya uzantılarını düzenlemeniz gerekmektedir. Lütfen aşağıdaki adımları sırasıyla uygulayın:
1. Gereksinimler
Bilgisayarınızda Python 3.x yüklü olmalıdır.
2. Dosya Hazırlığı (txt -> py/bat dönüşümü)
İndirdiğiniz klasörde .txt uzantılı dosyalar göreceksiniz. Bunları çalıştırılabilir hale getirmek için şu adımları izleyin:
Klasördeki mevcut main.py dosyasını silin.
main.txt dosyasının adını main.py olarak değiştirin.
Klasördeki mevcut CALISTIR.bat dosyasını silin.
CALISTIR.txt dosyasının adını CALISTIR.bat olarak değiştirin.
(Windows'ta dosya uzantılarını göremiyorsanız: Dosya Gezgini -> Görünüm -> Dosya adı uzantıları kutucuğunu işaretleyin.)
3. Uygulamayı Başlatma
Hazırlık bittikten sonra uygulamayı başlatmak için tek yapmanız gereken:
CALISTIR.bat dosyasına çift tıklayın.
Bu script otomatik olarak:
Gerekli kütüphaneleri (customtkinter, pillow vb.) yükleyecektir.
Uygulamayı başlatacaktır.
📖 Kullanım Rehberi
Klasör Seçimi: Uygulama açıldığında sağ üstteki "Select Folder" butonuna tıklayın ve düzenlemek istediğiniz (dağınık olan) klasörü seçin.
Analiz: Seçim yaptıktan sonra log ekranında kaç dosya bulunduğu ve uygulamanın hazır olduğu belirtilir.
Başlatma: "Start Organization" butonuna basın.
İzleme: İlerleme çubuğundan süreci takip edin. Dosyalarınız anında kategorilere ayrılacaktır.
Tamamlanma: İşlem bittiğinde "Done" mesajını göreceksiniz. Log ekranından hangi dosyanın nereye taşındığını inceleyebilirsiniz.
🛠️ Geliştirici Notları
Eğer kodu geliştirmek veya manuel çalıştırmak isterseniz:
code
Bash
# Gerekli paketleri yükleyin
pip install -r requirements.txt

# Uygulamayı başlatın
python main.py
📜 Lisans
Bu proje MIT lisansı ile lisanslanmıştır. İstediğiniz gibi kullanabilir, değiştirebilir ve dağıtabilirsiniz.
