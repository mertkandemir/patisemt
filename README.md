# Patisemt

Patisemt kedi ve köpek bakım stüdyosu için hazırlanmış, mobil uyumlu tek sayfalık tanıtım ve randevu sitesidir.

## Canlı site

[mertkandemir.github.io/patisemt](https://mertkandemir.github.io/patisemt/)

## Özellikler

- Mobil ve masaüstüne uyumlu tasarım
- Görünür alana geldiğinde otomatik başlayan bakım videoları
- Köpeği sevme etkileşimi
- Hizmet seçimi ve tarih bilgisiyle WhatsApp randevu mesajı oluşturma
- Patisemt'e özel renkler, tipografi ve pati logolu kimlik
- Konum haritası ve tek dokunuşla yol tarifi
- Düşük Güç Modu gibi otomatik oynatmanın engellendiği durumlarda hareketli görsel yedeği

## Yayınlama

Site GitHub Pages ile `main` dalından yayınlanır; `main`'e gönderilen her değişiklik birkaç dakika içinde canlıya çıkar.

Alan adı alındığında `index.html` içindeki `canonical`, `og:url`, `og:image` ve JSON-LD adreslerini yeni alan adıyla güncelleyin.

## Yerelde çalıştırma

Proje ek bir derleme adımı gerektirmez. Dosyaları indirdikten sonra klasörde basit bir statik sunucu başlatabilirsiniz.

```bash
python -m http.server 8000
```

Ardından tarayıcıdan `http://localhost:8000` adresini açın.

## Teknolojiler

HTML, CSS ve vanilla JavaScript.
