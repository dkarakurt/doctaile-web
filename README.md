# doctaile-web

doctaile Android uygulamasının tanıtım sitesi. Sitenin tamamı tek dosyada: `index.html`. Derleme adımı yok; tarif motoru da sayfanın içinde.

## Yayına alma
Depoyu olduğu gibi herhangi bir statik barındırmaya bağla:
- **Cloudflare Pages / Vercel / Netlify:** Projeyi bu depodan oluştur. Framework olarak "None" seç, build komutunu boş bırak, çıktı klasörü olarak `/` (kök dizin) gir. Ardından alan adını panelden ekle.
- **GitHub Pages:** Settings → Pages → Branch: `main` / `/ (root)`. Alan adı için aynı sayfadaki "Custom domain" alanını kullan.

## Dosyalar
- `index.html`: sitenin tamamı. Yazı tipleri Google Fonts'tan yüklenir.
- `favicon.svg`: sekme simgesi.

APK indirme düğmesi her zaman en son sürümü indirir:
`https://github.com/dkarakurt/dkarakurt-doctaile-android/releases/latest/download/doctaile.apk`
