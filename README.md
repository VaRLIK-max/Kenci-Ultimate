# Kenci Ultimate Suite v1.0.0

Video, görsel, ses ve dosya yönetimini tek bir masaüstü arayüzünde toplayan **Kenci Ultimate Suite** yayında. Cihaz üzerinde çalışan yapay zeka ses üretimi, evrensel format dönüştürücü, gelişmiş arka plan stüdyosu, çoklu video sıkıştırma ve akıllı RAM optimizasyonları artık tek çatı altında.

---

## Öne Çıkan Modüller & Özellikler

### Yapay Zeka Ses (Supertonic 3 — Yerel TTS)
* **Tamamen Yerel & Çevrimdışı:** İnternet bağlantısı gerektirmeden cihaz üzerinde çalışan *Supertonic 3* motoru.
* **31 Dil & 12 Konuşmacı:** Türkçe dahil 31 dil desteği; `F1–F5`, `M1–M5` ve özel profiller (*Özel Kadın / Özel Erkek*) ile ses üretimi.
* **Esnek Kontrol & `.txt` İçe Aktarma:** Kalite adımı (`2–16`) ve konuşma hızı (`0.80x – 1.30x`) ayarları, metin dosyalarından doğrudan aktarım.
* **Dahili Oynatıcı & Hızlı Paylaşım:** Canlı dalga formu (*waveform*), sürüklenebilir zaman çizelgesi, anlık performans metrikleri (*İşlem Süresi, Karakter/Sn, RTF*) ve tek tıkla diske kaydetme veya panoya kopyalama.

### Evrensel Dönüştürücü
* **Sürükle-Bırak Toplu Kuyruk:** Video, ses ve görseller için küçük resim (*thumbnail*), süre ve çözünürlük önizlemeli toplu dönüştürme.
* **Geniş Medya & Görsel Desteği:** `MP3, MP4, MKV, AVI, MOV, WEBM, GIF, WAV, AAC, FLAC, M4A, OGG` (`128–320 kbps` bitrate seçimi) ile `PNG, JPG, WEBP, BMP, PDF` ve çoklu boyutlu (`16×16` – `256×256`) `.ico` çıktıları.
* **Hızlı Çıktı Erişimi:** İşlem sonrası tek tıkla çıktı klasörünü açma veya dönüştürülen dosyaları panoya kopyalama.

### Arka Plan Silici (AI & Manuel Stüdyo)
* **Yerel AI & Toplu İşlem:** `u2net.onnx` modeliyle tek tıkla arka plan silme, dahili Model İndirici ve Toplu Klasör İşleme.
* **Hassas Düzenleme:** Manuel Silgi (`E`), Geri Getir (`R`), toleranslı Sihirli Değnek (`W`), Kırpma (`C`), fırça boyutu (`[` / `]` veya `Alt + Tekerlek`) ve yumuşaklık kontrolü.
* **Kenar, Efekt & Renk Araçları:** Kenar Yumuşatma, Halo temizleme, Arka Plan Bulanıklaştırma, Aura Modu ve sürükleyip ölçeklendirilebilir (`Ctrl + Tekerlek`) Arka Plan Ekleme. Parlaklık/kontrast/doygunluk/keskinlik ayarları, Önce/Sonra Çift Panel, `Ctrl+Z` / `Ctrl+Y` ve pano (`Ctrl+C` / `Ctrl+V`) desteği.

### Video Küçültücü (Kenci Video Forge)
* **Eşzamanlı Paralel İşleme:** 1, 2, 4, 6 veya 8 videoyu aynı anda kodlama (*RTX 4000+ çoklu NVENC* uyumlu).
* **4 Çalışma Modu:** *Hedef Boyut* (Discord / özel MB sınırı), *Ultra Kalite*, *Arşiv* ve *Sadece Ses Çıkar (`MP3`)*.
* **Donanım & Kodek Seçenekleri:** NVIDIA (`NVENC`), AMD (`AMF`) ve `CPU` üzerinden `H.264`, `H.265 / HEVC` ve `AV1` kodlama; 1-Pass ve 2-Pass (`P7 + HQ`) profilleri.
* **Akıllı Optimizasyonlar:** Otomatik siyah şerit kırpma, gürültü azaltma (*Denoise*), gereksiz ardışık kare silme (`mpdecimate`) ve ses kaldırma.

### Gizlilik & Dosya Araçları
* **EXIF Cleaner:** Görsellerdeki gizlilik ve meta verileri temizleyerek `PNG`, `JPG`, `WebP` veya orijinal formatta kaydedin; çoklu önizleme ve pano (`Ctrl+V` / tek tıkla kopyalama) ile hızlıca işlem yapın.
* **Süper Taşıyıcı:** Klasördeki dosyaları *Video, Müzik, Resim, Belge* ve *Uygulama* olarak tek tıkla ayırın. Uzantı özelleştirme, alt klasör tarama, isim çakışması kuralları ve tek tıkla **Geri Al (`Undo`)** desteği içerir.

---

## Ayarlar & Performans

* **Otomatik RAM Temizleyici:** Sekme değiştirdiğinizde arka planda kullanılmayan ağır yapay zeka modellerini (*Supertonic / u2net*) otomatik olarak bellekten temizler.
* **Kişiselleştirilebilir Başlangıç:** Uygulamanın her açılışta doğrudan tercih ettiğiniz sekme ile başlamasını seçebilirsiniz.
* **Akıcı Arayüz:** Animasyonlu sekme göstergesi, yırtılmasız geçişler, anlık bildirimler (*toast*) ve `kenci_ayarlar.json` üzerinden kalıcı ayar kaydı.

---

## Kurulum ve Kullanım

1. **Releases** bölümünden güncel arşivi indirin ve bir klasöre çıkartın.
2. `Kenci Ultimate Suite.exe` dosyasını çalıştırın.
3. İlk kullanımda *Arka Plan Silici* veya *Yapay Zeka Ses* modelleri eksikse uygulama içi indirici üzerinden tek tıkla otomatik kurabilirsiniz.
