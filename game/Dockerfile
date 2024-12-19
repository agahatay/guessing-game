# Base image olarak Python kullanıyoruz
FROM python:3.10.8

# Çalışma dizini oluştur
WORKDIR /app

# Bağımlılıkları ekle
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Kod dosyasını kopyala
COPY guessing_game.py .

# Default çalışma komutunu tanımla
CMD ["python", "guessing_game.py"]
