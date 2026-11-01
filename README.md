# Mehmet Veysel Delibaş

Bilgisayar Mühendisi · CBS yazılım geliştirici · Sakarya

2013'ten beri kamuda **coğrafi bilgi sistemleri (CBS)** yazılımları geliştiriyorum: Silverlight ve JavaScript ile başlayan yol, bugün baştan sona kendi geliştirdiğim bir kurumsal CBS platformuna ve ona bağlı yapay zekâ özelliklerine dönüştü. Yan projelerimde Türkçe için açık, yerelde çalışan ses teknolojileri geliştiriyorum ve Türkiye'nin ulusal yapay zekâ platformu **EVREN**'e gönüllü olarak açık veri ve model katkısı yapıyorum.

## Odak

- **Kurumsal CBS platformu** (2023–): web harita portalı (12 widget, 10 yerleşik CBS aracı), servis yönetim paneli ve OGC uyumlu harita/feature sunucusu; bağlı servis, rapor ve laboratuvar uygulamaları. *Kurum içi yazılım, kaynak kodu açık değil.*
- **Yapay zekâ entegrasyonu:** sohbetle harita ve widget üretimi, Türkçe harita komutlarını anlama, yönetim asistanı; yerli (EVREN) ve yerel LLM'ler.
- **Meridian:** WebGPU tabanlı 3B dünya ve harita motoru (geliştirme aşamasında).
- **GeoStudio:** yapay zekâ destekli masaüstü CBS editörü (erken aşama).

## Açık kaynak: [seslen-tr](https://github.com/seslen-tr) — Türkçe ses sentezi

| Proje | Ne yapar | Kurulum |
|---|---|---|
| [seslen-tts](https://github.com/seslen-tr/seslen-tts) | İşlemcide çalışan, 6 ses × 9 duygulu, Türkçe vurguyu ve soru ezgisini doğru okuyan açık ses modeli (ONNX) | `pip install seslen-tts` |
| [turkce-normalize](https://github.com/seslen-tr/turkce-normalize) | Sayı, tarih, saat, para ve kısaltmaları Türkçe okunuşa çevirir | `pip install turkce-normalize` |
| [turkce-vurgu](https://github.com/seslen-tr/turkce-vurgu) | Türkçe G2P ve sözcük vurgusu (espeak'siz) | `pip install turkce-vurgu` |
| [turkce-tts-sinav](https://github.com/seslen-tr/turkce-tts-sinav) | Türkçe G2P, vurgu ve normalizasyon için açık sınav verisi | `pip install turkce-tts-sinav` |
| [turkce-duygu](https://github.com/seslen-tr/turkce-duygu) · [turkce-uslup](https://github.com/seslen-tr/turkce-uslup) | Cümle tonu ve metin üslubu seçimi | `pip install turkce-duygu turkce-uslup` |
| [turkce-plbert](https://github.com/seslen-tr/turkce-plbert) | Türkçe PL-BERT fonem dil modeli | — |

Modeller: [huggingface.co/seslen-tr](https://huggingface.co/seslen-tr) · Kod MIT lisanslı.

## EVREN (gönüllü)

[EVREN profilim](https://evren.ssyz.org.tr/users/u43bd0650c87e): 24 açık veri seti (3,7 milyon+ öğe) ve 31 model; katkı sıralamasında ilk 5.

- Türkçe Açık Külliyat: 2,8 milyon paragraf (Vikipedi, Vikikaynak, Vikihaber, Tatoeba, yürürlükteki mevzuat)
- ~128 saatlik gerçek Türkçe konuşma verisi
- Türkçe LLM değerlendirme setleri: TR-Mevzuat-SC (21 bin soru), TR-CBS-Komut (10 bin örnek)

## Teknolojiler

TypeScript · Next.js · NestJS · Node.js · Python · MongoDB · PostgreSQL/PostGIS · Oracle Spatial · ArcGIS Enterprise · Leaflet · WebGPU · ONNX

[LinkedIn](https://www.linkedin.com/in/mveyseldelibas) · [Hugging Face](https://huggingface.co/mvdelibas) · [EVREN](https://evren.ssyz.org.tr/users/u43bd0650c87e)
