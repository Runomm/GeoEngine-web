# GeoEngine

[Türkçe](README.tr.md)

Documents for GeoEngine, a proof of concept that tries to guess where a photo was taken by combining OCR, a vision-language model (Gemini) and an image geolocation model (PLONK). The code is in [GeoEngine-Backend](https://github.com/Runomm/GeoEngine-Backend).

## Files

- `GeoEngine.pdf` / `GeoEngine.docx`: the project proposal (Turkish), covering the planned tech stack, APIs, build order and a schedule for March to June 2026.
- `Çok Modlu OSINT Konum Tahmin Sistemleri ve GeoAI.pdf` / `.docx`: a literature review (Turkish) on image geolocation (PIGEON, GeoCLIP, StreetCLIP), agent-based approaches, shadow and terrain analysis, probability polygons, and privacy and ethics.
- `2412.06781v1.pdf`: *Around the World in 80 Timesteps: A Generative Approach to Global Visual Geolocation* (Dufour et al.), the paper behind PLONK, which the backend uses. It's kept here for reference; the original is [arXiv:2412.06781](https://arxiv.org/abs/2412.06781).
- `preziSunum.txt`: link to the Prezi presentation.

Not everything in the proposal was built. The backend README lists what actually works.

## Related repos

- [GeoEngine-Backend](https://github.com/Runomm/GeoEngine-Backend): FastAPI backend and Flutter client
- [GeoEngine-app](https://github.com/Runomm/GeoEngine-app): the first, minimal client
