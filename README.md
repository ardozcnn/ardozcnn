# Arda Özcan

**Modelleri uçuşa, kadroya ve karara bağlayan yazılımlar.**

Ankara, TR · 2020’den beri · Python / TypeScript / C++

Kendi açık kaynak işlerim İHA uçuş planı, fizik tabanlı yörünge, fantezi lig optimizasyonu, uyarlanabilir SAT ajanı ve ESP32 üzerinde GSR prototipi arasında gidip geliyor. Fork’lar değil: aşağıdaki kartlar yazdığım orijinal repolar.

Site: **[ardozcnn.github.io/website](https://ardozcnn.github.io/website/)** · LinkedIn: **[mustafa-arda-ozcan](https://www.linkedin.com/in/mustafa-arda-ozcan)**

---

## Seçilmiş işler

Bir problemi önce kısıtlarıyla kuruyorum: bütçe, fizik, pil, SAT müfredatı, maç fikstürü. Sonra o kısıtın içinden bir sonraki hamleyi üreten bir model veya ajan çıkarıyorum.

### Havacılık

| Proje | Dil | Ne işe yarıyor |
| --- | --- | --- |
| **[AeroPlan AI](https://github.com/ardozcnn/aero-plan-ai)** | Python | İHA için uçtan uca uçuş planı ve görev analitiği. Lawnmower tarama izi, RandomForest ile süre/pil tahmini, QGroundControl görev dosyası. |
| **[AeroOrbit](https://github.com/ardozcnn/aero-orbit)** | Python | Hava sürtünmesi, kütle ve yerçekimini diferansiyel denklemlerle işleyen 2B yörünge simülasyonu. SciPy + Matplotlib. |
| **[Uçuş Kontrol](https://github.com/ardozcnn/drone-flight)** | Python | Open-Meteo hava durumunu drone / İHA limitlerine bağlayan Flask aracı. Çıktı: uçabilir, dikkatli ol veya uçma. |

### Spor

| Proje | Dil | Ne işe yarıyor |
| --- | --- | --- |
| **[TFF Fantezi Lig Optimizer](https://github.com/ardozcnn/tff-fantezi-lig-optimizer)** | Python | 100 milyon TL bütçeye uyan 15 kişilik kadroyu fiyat, form, xG ve fikstürle seçen tamsayı programı. Diziliş, kaptan ve otomatik yedek aynı modelden çıkar. |
| **[PitchValue](https://github.com/ardozcnn/pitch-value)** | TypeScript | AQX Data Bowl 3.0 için futbol piyasası analitiği. Ücret, piyasa değeri ve saha üretimini (xG, progressive aksiyon) aynı panoda birleştirir. |

### Öğrenme

| Proje | Dil | Ne işe yarıyor |
| --- | --- | --- |
| **[AceSAT](https://github.com/ardozcnn/ace-sat)** | TypeScript | Sohbet botu değil: beceri boşluğunu teşhis eden, Khan tarzı tek-beceri görevleri yürüten uyarlanabilir SAT ajanı. Çekirdek döngü çevrimdışı çalışır. |
| **[Grace Exit](https://github.com/ardozcnn/grace-exit)** | TypeScript | Infinity Hacks 2026. Aşırı uyaranlı bir mekândan tuhaf durmadan çıkmak için kısa script’ler, yerel gürültü ölçümü, tek güvenli kişi. Hesap yok, sunucu yok. |

### Donanım

| Proje | Dil | Ne işe yarıyor |
| --- | --- | --- |
| **[GSR yalan dedektörü](https://github.com/ardozcnn/gsr-yalan-dedektoru)** | C++ | XIAO ESP32-S3 + Grove GSR. Cilt direncindeki mikro değişimleri kişisel baza göre okur. [Canlı notlar](https://ardozcnn.github.io/gsr-yalan-dedektoru/). |

---

## Nasıl çalışıyorum

AceSAT bir sohbet botu değil; TFF aracı rastgele kadro da değil. Python ile simülasyon ve optimizasyon, TypeScript ile ürün arayüzleri, C++ ile gömülü prototipler yazıyorum. SymPy, Ray, Lark gibi büyük fork’lar portföy kartı değil; kendi kodum ayrı duruyor.

`Python · SciPy · PuLP · Streamlit` · `TypeScript · React · Next.js · Vite` · `C++ · ESP32` · `Flask · MAVLink`
