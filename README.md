# Mehmet Veysel Delibaş

Bilgisayar Mühendisi · CBS yazılım geliştirici · Sakarya

2013'ten beri kamuda **coğrafi bilgi sistemleri (CBS)** yazılımları geliştiriyorum. Kendi zamanımda açık kaynak araçlar üretiyorum: harita verisini yapay zekâya güvenle açan araçlar, Türkçe için ölçüm setleri ve herkesin tarayıcıda kullanabileceği kamu yararı araçları.

## CBS + yapay zekâ

| Proje | Ne yapar |
|---|---|
| [mapsql-mcp](https://github.com/mveyseldelibas/mapsql-mcp) | PostGIS ve Oracle Spatial için güvenli MCP sunucusu: yapay zekâ asistanı veritabanını salt okunur sorgular, sonucu haritayla anlatır. `uvx mapsql-mcp` |
| [turkce-adres](https://github.com/mveyseldelibas/turkce-adres) | Dağınık Türkçe adresleri ayrıştırır ve düzeltir; 66 bin mahalle ve köyle doğrular, internetsiz yaklaşık konum verir, tekrarları bulur, KVKK için genelleştirir. `pip install turkce-adres` |
| [TR-CBS-Komut](https://huggingface.co/datasets/mvdelibas/tr-cbs-komut) | Türkçe harita komutlarını anlama için açık değerlendirme seti (11,7 bin örnek) · [ölçüm tablosu](https://huggingface.co/spaces/mvdelibas/tr-cbs-olcum) |
| [Trafik levhası demosu](https://huggingface.co/spaces/mvdelibas/turk-trafik-levha-demo) | Türkiye trafik levhalarını tanıyan model, tarayıcıda |

## Hugging Face'te açık modeller ve veri setleri

4 model, 18 veri seti ve 8 tarayıcı demosu: [huggingface.co/mvdelibas](https://huggingface.co/mvdelibas). Konulara göre:

| Koleksiyon | İçinde |
|---|---|
| [Türkiye CBS ve coğrafi yapay zekâ](https://huggingface.co/collections/mvdelibas/turkish-gis-and-geospatial-ai-6af0d91a87f725ebce84965b) | Trafik levhası, araç-yaya, bina ve uydu tesis tespit modelleri; adres ve harita komutu setleri |
| [LiDAR nDSM ve bina yüksekliği](https://huggingface.co/collections/mvdelibas/lidar-ndsm-and-building-height-6af3915d716ed5b858c73a6b) | Hollanda AHN4 gerçek ve 81 il sentetik nDSM karoları, bina envanteri |
| [Robot görme ve Türkçe robot komutları](https://huggingface.co/collections/mvdelibas/robot-vision-sim-and-turkish-robot-commands-6af3915e6ed8c7bb928e07a1) | Simülasyon bölütleme, yönlü kutu ve anahtar nokta setleri; gerçek fotoğraf test seti |
| [Ay/Mars gezgini ve gökyüzü taraması](https://huggingface.co/collections/mvdelibas/lunar-mars-rover-and-sky-survey-synthetic-6af39160abd9b1da269411b1) | Gezgin tehlike bölütleme ve yol planlama; uydu izi ve hareketli cisim setleri |
| [Türkçe dil modeli sınamaları](https://huggingface.co/collections/mvdelibas/turkish-llm-benchmarks-6af39161f9a91556f5398122) | Harita komutu, netleştirme sorusu, mevzuat soru-cevap, robot talimatı |

## Kamu yararı araçları

Üçü de tarayıcıda çalışır; yazdığınız metin bir sunucuya gitmez.

| Araç | Ne yapar |
|---|---|
| [KVKK Maske](https://huggingface.co/spaces/mvdelibas/kvkk-maske) | Ad, T.C. kimlik, IBAN, telefon ve adresi yapay zekâya göndermeden önce maskeler, cevapta geri açar |
| [Mevzuat Arama](https://huggingface.co/spaces/mvdelibas/tr-mevzuat-arama) | 1,19 milyon mevzuat ve Resmî Gazete paragrafında arama, her sonuçta resmî metnin bağlantısı |
| [Erişilebilirlik Denetleyici](https://huggingface.co/spaces/mvdelibas/erisilebilirlik-denetleyici) | HTML'deki erişilebilirlik sorunlarını WCAG maddesi ve çözüm önerisiyle Türkçe gösterir |

## Türkçe ses: [seslen-tr](https://github.com/seslen-tr)

| Proje | Ne yapar | Kurulum |
|---|---|---|
| [seslen-tts](https://github.com/seslen-tr/seslen-tts) | İşlemcide çalışan, 6 ses × 9 duygulu, Türkçe vurguyu ve soru ezgisini doğru okuyan açık ses modeli (ONNX) | `pip install seslen-tts` |
| [turkce-normalize](https://github.com/seslen-tr/turkce-normalize) | Sayı, tarih, saat, para ve kısaltmaları Türkçe okunuşa çevirir | `pip install turkce-normalize` |
| [turkce-vurgu](https://github.com/seslen-tr/turkce-vurgu) | Türkçe G2P ve sözcük vurgusu (espeak'siz) | `pip install turkce-vurgu` |
| [turkce-tts-sinav](https://github.com/seslen-tr/turkce-tts-sinav) | Türkçe G2P, vurgu ve normalizasyon için açık sınav verisi | `pip install turkce-tts-sinav` |
| [turkce-duygu](https://github.com/seslen-tr/turkce-duygu) · [turkce-uslup](https://github.com/seslen-tr/turkce-uslup) | Cümle tonu ve metin üslubu seçimi | `pip install turkce-duygu turkce-uslup` |
| [turkce-plbert](https://github.com/seslen-tr/turkce-plbert) | Türkçe PL-BERT fonem dil modeli | — |

Kod MIT, model ağırlıkları CC BY-SA 4.0 · Modeller: [huggingface.co/seslen-tr](https://huggingface.co/seslen-tr)

## EVREN (gönüllü)

Türkiye'nin ulusal yapay zekâ platformu [EVREN](https://evren.ssyz.org.tr/users/u43bd0650c87e)'e 24 açık veri seti ve 31 model katkısı: Türkçe LLM değerlendirme setleri (TR-CBS-Komut, TR-Mevzuat-SC), Türkiye'ye özgü coğrafi görüntü setleri, Türkçe Açık Külliyat ve ~128 saatlik gerçek Türkçe konuşma verisi.

## Teknolojiler

TypeScript · Node.js · Python · PostgreSQL/PostGIS · Oracle Spatial · Leaflet · WebGPU · ONNX · MCP

[LinkedIn](https://www.linkedin.com/in/mveyseldelibas) · [Hugging Face](https://huggingface.co/mvdelibas)
