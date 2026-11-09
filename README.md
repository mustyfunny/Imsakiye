# İmsakiye – Ramazan tarihleri

Gizlilik politikası / Privacy policy: [PRIVACY.md](PRIVACY.md)

Bu depo yalnızca İmsakiye uygulamasının okuduğu **ülkelere göre Ramazan başlangıç
tarihlerini** barındırır: [`ramadan_schedule.json`](ramadan_schedule.json).

Uygulama dosyayı her açılışta şu adresten okur:

```
https://raw.githubusercontent.com/mustyfunny/Imsakiye/main/ramadan_schedule.json
```

## Güncelleme

1. `ramadan_schedule.json` dosyasını aç, kalem (Edit) simgesine bas.
2. Ülkenin `start` (ilk oruç günü) ve `days` (29/30) değerlerini yaz.
3. `updated` değerini **o anki tarih-saatle** değiştir (ör. `2027-02-07T20:30`).
   Daha eski ya da aynı `updated` değerli dosyayı uygulama yok sayar.
4. "Commit changes" ile kaydet. Değişikliğin herkese ulaşması birkaç dakika sürebilir.

Bozuk bir dosya uygulama tarafından reddedilir; kullanıcılar son geçerli
tabloyla devam eder. Ayrıntılar: uygulama projesindeki `docs/ramazan-tarihleri.md`.
