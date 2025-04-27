
# CareerConnect 🚀

AI-Powered Job Application Automation

---

## 📚 Proje Tanımı

**CareerConnect**, yapay zeka destekli bir iş başvurusu otomasyon platformudur.  
Kullanıcıların profiline ve şirketlerin odak alanlarına göre **kişiselleştirilmiş başvuru mektupları** oluşturur ve **otomatik e-posta gönderimi** gerçekleştirir.

Bu sistem sayesinde kullanıcılar doğru firmalara doğru içeriklerle başvuru yaparak iş bulma şanslarını artırır, zaman tasarrufu sağlar ve başvuru süreçlerini profesyonel bir şekilde yönetir.

🏆 **CareerConnect**, AI ve Otomasyon temalı yarışmalar için geliştirilmiştir.

---

##  Özellikler

- Yapay zeka destekli başvuru mektubu üretimi (Llama 3.3 70B)
- Otomatik ve güvenli e-posta gönderimi (SMTP SSL ile)
- Retry mekanizması ve detaylı loglama
- Dinamik kullanıcı ve firma profili yönetimi
- Modüler yapı, hızlı özelleştirme imkanı

---

## 🛠️ Kullanılan Teknolojiler

- Python 3.10+
- Nest Asyncio
- iointel (AI Agent API)
- SMTP Email (SSL Güvenlikli)
- OpenAI API / Intelligence API
- Retry & Error Handling

---

## 📂 Proje Yapısı

```
CareerConnect/
│
├── config.py              # E-posta ve API anahtarlarının bulunduğu dosya
├── main.py                # Uygulamanın ana çalışma dosyası
├── cv.pdf                 # Başvurularda eklenecek CV dosyası
├── email_log.txt          # Başarılı e-posta logları
├── email_error_log.txt    # Hatalı e-posta logları
└── README.md              # Proje açıklamaları (bu dosya)
```

---

## ⚙️ Kurulum ve Çalıştırma

1. Gerekli Python kütüphanelerini yükleyin:
```bash
pip install nest_asyncio iointel
```

2. Proje dizinine bir `config.py` dosyası oluşturun:
```python
# config.py
sender_email = "seninmailin@gmail.com"
sender_password = "senin_gmail_uygulama_sifren"
openai_api_key = "senin_openai_api_key"
```

3. CV dosyanızı `cv.pdf` olarak proje dizinine ekleyin.

4. Uygulamayı çalıştırın:
```bash
python main.py
```

> **Not:** Gmail hesabınız için "Uygulama Şifresi" oluşturmanız gerekir. Normal giriş şifresiyle çalışmaz.

---

## 📈 Sistem Akışı

```
Kullanıcı Profili + Şirket Profili
         ↓
   AI Agent (Llama-3.3-70B)
         ↓
  Kişisel Başvuru Mektubu
         ↓
       E-posta Gönderimi
         ↓
      Loglama & Hata Yönetimi
```

---

## 🎯 Neden CareerConnect?

- AI ile kişiye özel başvuru mektupları
- Zamandan büyük tasarruf
- Profesyonel ve güvenli başvuru süreci
- Hatalara karşı güvenli retry sistemi
- Yüksek etkili otomasyon akışı

---

## 📜 Lisans

Bu proje yarışma amaçlı geliştirilmiş olup, açık kaynak olarak paylaşılabilir.  
Ticari kullanım veya yeniden dağıtım için geliştiriciden izin alınması önerilir.

---

#  CareerConnect ile kariyerine güçlü bir adım at!
