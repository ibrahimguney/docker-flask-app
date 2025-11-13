# Docker Flask App

Bu proje, basit bir Flask uygulamasının Docker kullanılarak container içerisinde çalıştırılmasını gösteren örnek bir yapıdır.

## 🚀 Proje Özeti

Bu uygulama:
- Python + Flask kullanır
- Docker container içinde çalışır
- 5000 portu üzerinden "Merhaba Docker ve GitHub dünyası!" mesajı döner

## 📁 Proje Yapısı

docker-flask-app/
│
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md


## 🧩 Kurulum ve Çalıştırma






### 1. Docker İmajını Oluştur

```bash
docker build -t flask-docker-demo .

docker run -d --name flask-docker-demo-container -p 5000:5000 flask-docker-demo


http://localhost:5000

🐳 Kullanılan Teknolojiler
Python 3.10+

Flask

Docker

GitHub





