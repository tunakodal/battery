# Ladder Timer

Basit, tarayıcı tabanlı bir odaklanma zamanlayıcısı. Tek bir HTML dosyasından oluşur, kuruluma gerek yoktur — dosyayı açmak yeterlidir.

## Nasıl Çalışır

Toplam 60 dakikalık bir oturumu, kademeli olarak uzayan 6 çalışma bloğuna ve ardından gelen 5 dakikalık bir molaya böler:

**2 → 4 → 6 → 8 → 15 → 20 dakika (çalışma) → 5 dakika (mola)**

Ekranda her blok bir sütun olarak gösterilir; süre ilerledikçe sütun aşağıdan yukarıya dolar, böylece hem içinde bulunulan bloğun hem de oturumun genel ilerleyişi tek bakışta görülebilir.

## Kullanım

- **Start / Pause**: Zamanlayıcıyı başlatır veya duraklatır
- **Skip block**: Mevcut bloğu atlayıp bir sonrakine geçer
- **Reset**: Oturumu baştan başlatır
- **Boşluk tuşu**: Start/Pause için kısayol
- Herhangi bir sütuna tıklayarak doğrudan o bloğa atlanabilir

Sekme başlığı, o an kalan süreyi gösterecek şekilde güncellenir; böylece sekme arka planda bile olsa süre takip edilebilir.

## Teknik Notlar

- Harici bağımlılık yok, tek bir `.html` dosyası
- GitHub Pages üzerinden statik olarak yayınlanabilir
- Aileron yazı tipi, koyu tema
