# 🎙️ VoiceNoteMate  

**VoiceNoteMate**, sesinizi yazıya dönüştürüp `.docx` dosyası olarak kaydeden basit ama kullanışlı bir **kişisel sesli not uygulamasıdır**.  
Herhangi bir ekstra araca ihtiyaç duymaz — sadece çalıştırın ve konuşmaya başlayın!  

---

## 🚀 Özellikler  
- 🎤 **Gerçek zamanlı ses tanıma** — konuşmalarınızı anında yazıya dönüştürür.  
- 💾 **Otomatik kayıt** — notlarınızı Word (`.docx`) dosyası olarak kaydeder.  
- 🛑 **Kolay durdurma** — konuşmayı `Ctrl + C` ile bitirebilir, ardından “Kayıt bitti” mesajı alırsınız.  
- 🧠 **Tamamen offline çalışır** — internet bağlantısına gerek yoktur.  
- 🪶 Hafif ve basit — sadece birkaç Python kütüphanesiyle çalışır.

---

## 🧩 Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki paketlere ihtiyacınız var:

```bash
pip install vosk
pip install sounddevice
pip install python-docx
pip install pyttsx3
Ayrıca, Türkçe dil modeli için Vosk Model TR sayfasından
vosk-model-small-tr-0.3 dosyasını indirip proje klasörüne koymanız gerekir.


🧠 Kullanım

1.Terminali açın ve proje klasörüne gidin.

2.Aşağıdaki komutu çalıştırın:

    python main.py


3.Uygulama açıldığında konuşmaya başlayın.

4.Ctrl + C tuş kombinasyonuna bastığınızda kayıt sonlanır ve notlarınız “voice_notes.docx” dosyasına kaydedilir.

5.Kayıt tamamlandığında “💾 Kayıt bitti” mesajı ekranda görünür.

🧱 Proje Yapısı

VoiceNoteMate/
│
├── main.py                    # Ana Python dosyası
├── vosk-model-small-tr-0.3/   # Türkçe ses tanıma modeli
├── voice_notes.docx           # Otomatik oluşturulan not dosyası
└── README.md

# VoskVoiceNotes