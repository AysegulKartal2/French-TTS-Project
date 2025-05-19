# French-TTS-Project
 Kendi Sesimle Fransızca Konuşan Video Üretimi

Bu proje, üretken yapay zekâ teknikleriyle bir kişinin kendi sesiyle Fransızca konuşuyormuş gibi görünen bir video oluşturmayı hedeflemektedir. Proje kapsamında aşağıdaki teknolojiler kullanılmıştır:

 Amaç
- 120 adet Türkçe ses kaydımı kullanarak Tacotron 2 ile kendi sesimi modellemek.
- Metinleri Fransızcaya çevirerek Fransızca sesler üretmek.
- Bu sesleri Wav2Lip modeli ile bir yüz videosuna dudak senkronizasyonu yaparak entegre etmek.

##  Kullanılan Teknolojiler
- **Tacotron 2** – Metinden kişisel sesle konuşma üretimi (fine-tune)
- **Wav2Lip** – Yüz videosunda dudak senkronizasyonu
- **Google Colab** – Eğitim ve çalışma ortamı
- **Google Translate** – Türkçe-Fransızca çeviri

## Dosyalar
- `notebooks/tacotron2_finetune.ipynb`: Tacotron 2 modelini kişisel sesle eğitme defteri
- `metadata.csv`: Ses dosyaları ile metin eşleşmeleri
- `requirements.txt`: Kullanılan temel Python kütüphaneleri 
- `README.md`: Bu belge

## Durum
Bu bir ders projesidir ve teknik sınırlamalar nedeniyle model eğitimi tam olarak tamamlanamamıştır. Ancak tüm hazırlık adımları ve kullanılan kodlar bu repoda paylaşılmıştır.

##  Google Drive Bağlantısı
Veri boyutu nedeniyle ses dosyaları doğrudan burada paylaşılmamıştır. `Tacotron2_Sounds` adlı klasör Google Drive üzerinde saklanmaktadır.

---

Hazırlayan: [Ayşegül KARTAL]  
 Tarih: Mayıs 2025
