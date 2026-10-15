# AkSeC LogLab

AkSeC LogLab, web erişim günlüklerini tarayıcıda inceleyen çalışan bir erken prototiptir. [Tanıtım sayfası](https://lykes0.github.io/AkSeC/) ve [LogLab uygulaması](https://lykes0.github.io/AkSeC/app.html) GitHub Pages üzerinde yayımlanır.

## Neler yapar?

- Nginx/Apache access log ve JSON Lines biçimindeki kayıtları ayrıştırır.
- HTTP 4xx/5xx yanıtlarını, hassas yol isteklerini ve tekrarlanan giriş hatalarını öne çıkarır.
- Olaylarda arama ve öncelik filtresi sunar; sonuçları CSV olarak indirir.
- Kayıtlardaki kaynak IP, host ve istek yollarını listeler. Ağ taraması yapmaz.

Veriler yalnızca açık tarayıcı sekmesinde işlenir; sunucuya aktarılmaz. Örnek kayıtlar ve tanıtım görseli temsildir. Kurallar deneysel olduğu için sonuçlar uzman doğrulamasının yerini almaz. Dosya sınırı 2 MB, analiz sınırı 5.000 satırdır.

## Yerel çalıştırma

`index.html` veya doğrudan `app.html` dosyasını tarayıcıda açın. Dış bağımlılık ve kurulum gerektirmez.
