# Worfe Admin Panel Bulucu

Worfe Admin Panel Bulucu, bir web sitesinde yaygın admin panel yollarını otomatik olarak tarayan ve bulan Python tabanlı bir araçtır. Hem Türkçe hem İngilizce dil desteğiyle modern ve renkli bir terminal arayüzü sunar.

## Özellikler
- Binlerce admin panel yolu ile kapsamlı tarama
- Türkçe ve İngilizce dil desteği (program başında seçimli)
- Modern, renkli ve kutulu terminal çıktısı
- İlerleme çubuğu ve özet rapor
- Kolayca yeni admin yolları ekleyebilme

## Gereksinimler
- Python 3.7 veya üzeri

## Kurulum ve Kullanım

1. Projeyi GitHub'dan indir veya klonla:
   ```bash
   git clone https://github.com/Efekose7/Admin-Panel-Finder.git
   ```
2. Proje klasörüne gir:
   ```bash
   cd Admin-Panel-Finder
   ```
3. Aracı başlat:
   ```bash
   python3 admin_gırıs.py
   ```
4. Dil seçimini yap ve yönergeleri takip et.

## Admin Panel Yolları Nasıl Eklenir?
- `admin_gırıs.py` dosyasındaki `load_admin_paths()` fonksiyonuna yeni yolları ekleyebilirsin.
- Çok fazla yol eklemek tarama süresini uzatır.

## Notlar
- Termux ve Kali Linux üzerinde renkli terminal desteği için Python 3 yeterlidir.
- Araç, sadece HTTP/HTTPS üzerinden çalışan sitelerde çalışır.

## Sorumluluk Reddi
Bu araç sadece eğitim ve güvenlik testleri için geliştirilmiştir. İzinsiz sitelerde kullanmak yasal değildir. Tüm sorumluluk kullanıcıya aittir.

---

**Geliştirici:** Worfe 
