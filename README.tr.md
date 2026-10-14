# GeoEngine

[English](README.md)

GeoEngine'in dokümanları. GeoEngine, OCR'ı, bir görsel-dil modelini (Gemini) ve bir görüntüden konum tahmin modelini (PLONK) birleştirerek bir fotoğrafın nerede çekildiğini tahmin etmeye çalışan bir kavram kanıtı. Kod [GeoEngine-Backend](https://github.com/Runomm/GeoEngine-Backend) reposunda.

## Dosyalar

- `GeoEngine.pdf` / `GeoEngine.docx`: proje öneri dokümanı. Planlanan teknolojiler, API'ler, geliştirme sırası ve Mart–Haziran 2026 iş takvimi burada.
- `Çok Modlu OSINT Konum Tahmin Sistemleri ve GeoAI.pdf` / `.docx`: literatür taraması. Görüntüden konum tahmini (PIGEON, GeoCLIP, StreetCLIP), ajan tabanlı yaklaşımlar, gölge ve arazi analizi, olasılık poligonları ile gizlilik ve etik konularını içeriyor.
- `2412.06781v1.pdf`: backend'in kullandığı PLONK'un makalesi, *Around the World in 80 Timesteps: A Generative Approach to Global Visual Geolocation* (Dufour vd.). Referans olarak burada duruyor; aslı [arXiv:2412.06781](https://arxiv.org/abs/2412.06781).
- `preziSunum.txt`: Prezi sunumunun linki.

Önerideki her şey yapılmadı; gerçekte neyin çalıştığı backend'in README'sinde yazıyor.

## İlgili repolar

- [GeoEngine-Backend](https://github.com/Runomm/GeoEngine-Backend): FastAPI backend'i ve Flutter istemcisi
- [GeoEngine-app](https://github.com/Runomm/GeoEngine-app): ilk ve en basit istemci
