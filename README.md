# Seretan Co-Pilot · harita paketleri

Seretan Co-Pilot uygulamasının indirdiği yol verisi paketleri. Uygulamanın kodu burada değildir.

- `index.json`: paket listesi. Her karonun boyutu ve yedi coğrafi bölgenin (Marmara, Ege, Akdeniz, İç Anadolu,
  Karadeniz, Doğu Anadolu, Güneydoğu Anadolu) hangi karolardan oluştuğu.
- `tiles/<y>_<x>.scp`: 0,5° × 0,5° karolar. Her biri o alandaki yolları, virajları, eğimleri ve yüzey bilgisini içerir.

Uygulama önce `index.json` dosyasını okur, sonra seçilen bölgenin ya da planlanan rotanın karolarını indirir.

## Kaynak ve lisans

Yol verisi © OpenStreetMap katkıcıları; [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/)
ile lisanslıdır. Bu paketler OpenStreetMap verisinden türetilmiş bir veritabanıdır ve aynı lisansla paylaşılır.
Yükseklik verisi: SRTM (NASA / USGS, kamu malı).
