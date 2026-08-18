# KEAR GAMES — kurumsal sayfalar

Bu depo yalnızca **KEAR GAMES ana sayfasını ve oyunların gizlilik politikası
sayfalarını** barındırır. GitHub Pages ile `keargames.com` adresinde yayınlanır.

## Bu depoya ASLA girmeyecekler

- Oyun kaynak kodu (ayrı ve private depoda)
- Android proje dosyaları
- İmza anahtarı (`.jks`), `keystore.properties`, parolalar
- Herhangi bir gizli bilgi

Depo **public**'tir; buraya konan her şey herkes tarafından görülebilir.

## Yapı

| Dosya | Yayınlanan adres |
|---|---|
| `index.html` | `https://keargames.com/` |
| `gizlilik/index.html` | `https://keargames.com/gizlilik/` |
| `gizlilik/peron/index.html` | `https://keargames.com/gizlilik/peron/` |
| `CNAME` | Alan adı bağlantısı — silinmemeli |

## Yeni oyun eklerken

1. `gizlilik/` altında oyun adıyla klasör aç, `gizlilik/peron/index.html`
   dosyasını şablon olarak kullan.
2. `gizlilik/index.html` içindeki listeye satır ekle.
3. Kök `index.html` içindeki "Oyunlarımız" bölümüne kart ekle.

## Notlar

- Sayfalar hiçbir harici kaynak (yazı tipi, betik, izleyici) yüklemez.
  Bir gizlilik sayfası, üçüncü taraf izleyici çağırarak kendi metnini
  yalanlamamalıdır.
- `CNAME` dosyası `keargames.com` içerir; GitHub Pages özel alan adını
  buradan okur.
