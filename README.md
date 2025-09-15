# Flask Counter App with Docker

Bu proje, basit bir Flask web uygulamasını Docker container içinde çalıştırır.  
Uygulama, her ziyaret edildiğinde bir counter arttırır ve ziyaret sayısını gösterir.  

---

## 🚀 Proje Amacı

- Flask ve Python web uygulamalarını öğrenmek
- Bulut bilişim ve container teknolojilerini öğrenmek
- Docker ile uygulama paketleme ve dağıtım pratiği yapmak

---

## 🛠 Gereksinimler

- Python 3.9 veya üzeri
- Docker Desktop (opsiyonel, container ile çalıştırmak için)
- Git (isteğe bağlı, kodu GitHub’dan çekmek için)

---

## 📂 Proje Dosyaları

| Dosya           | Açıklama |
|-----------------|----------|
| `app.py`        | Flask uygulaması, ana counter fonksiyonunu içerir |
| `requirements.txt` | Python bağımlılıkları (Flask) |
| `Dockerfile`    | Docker image oluşturma talimatları |
| `README.md`     | Proje hakkında bilgi ve kullanım talimatları |

---
## 📦 Docker Flow Görselleştirmesi (opsiyonel)

Uygulamanın Docker ile nasıl çalıştığını adım adım özetleyen şema:

[Local Project Folder]
        │
        ▼
   Docker Build
        │
        ▼
  [Docker Image]  <-- paketlenmiş uygulama + bağımlılıklar
        │
        ▼
  Docker Run
        │
        ▼
 [Docker Container]  <-- canlı çalışan uygulama
        │
        ▼
Tarayıcıdan Erişim: http://127.0.0.1:8080

 
## ⚡ Kurulum ve Çalıştırma

1. Repository’i klonla veya proje klasörünü aç:

```bash
git clone <your-repo-url>
cd flask-counter
