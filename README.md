# GoSak – Sakarya Ulaşım Teknolojisi Projesi

GoSak, Sakarya özelinde otobüs, minibüs, banliyö ve tramvay hatlarını tek bir akıllı model altında birleştirmeyi hedefleyen, rota üretimi ve senaryo analizi odaklı bir ulaşım teknolojisi projesidir.

Bu repository, projenin statik tanıtım sitesi ve ilerleyen dönemde paylaşılacak dokümantasyon için kullanılmaktadır.

---

## Proje Vizyonu

- **Şehir odaklı yaklaşım:**  
  Sakarya’nın gerçek ulaşım dinamiklerini (minibüs esnekliği, otobüs ve tramvay sabit hatları, topografya vb.) modelleyebilen bir çekirdek tasarlamak.

- **Canlı veri zorunluluğu olmadan analiz:**  
  Gerçek zamanlı veriye bağlı kalmadan, senaryo tabanlı “what-if” analizleri yapabilen bir yapı kurgulamak.

- **Çok modlu ulaşım modeli:**  
  Otobüs, minibüs, banliyö ve tramvayı tek bir graf yapısı ve rota motoru ile yönetilebilir hale getirmek.

- **API-first mimari:**  
  Çekirdek rota motoru etrafında REST/GraphQL tabanlı bir katman ile mobil ve web istemcilere açık bir ekosistem oluşturmak.

---

## Bu Repository Ne İçin?

- `index.html` ile yayınlanan **tanıtım / konsept landing page**
- İlerleyen dönemde:
  - Teknik dokümantasyon
  - API taslakları
  - Veri modeli ve mimari notlar
  için kaynak depo olarak kullanılacaktır.

Özel domain hedefi: `https://gosak.com.tr`

> Not: Domain yönlendirme ve HTTPS yapılandırması GitHub Pages ve domain sağlayıcısı üzerinden yönetilecektir.

---

## Özellikler (Planlanan)

Tanıtım sitesi tarafında:

- Modern, tek sayfalık landing page
- Proje vizyonu, hedef kitlesi ve teknik yol haritasının özet sunumu
- Geliştirme sürecine katılım ve geri bildirim için call-to-action alanları

Projenin teknik çekirdeği tarafında (hedeflenen):

- Çok modlu ulaşım graf modeli (otobüs, minibüs, tramvay, banliyö)
- Topolojiye duyarlı maliyet fonksiyonları (yokuş, köprü, kavşak vb.)
- Senaryo tabanlı rota üretimi
- API-first yaklaşım (REST/GraphQL taslakları)

---

## Teknolojiler

Şu an için:

- **Frontend:**  
  - Saf HTML5, CSS3, minimal JavaScript  
  - Statik site (framework bağımlılığı yok)

- **Hosting:**  
  - GitHub Pages (statik site barındırma)
  - İlerleyen aşamalarda custom domain: `gosak.com.tr`

Planlanan (backend / rota motoru):

- **Dil / Stack (taslak):**
  - Go veya benzeri yüksek performanslı bir dil
  - REST/GraphQL API katmanı
  - Harita / graf kütüphaneleri ile entegrasyon

---