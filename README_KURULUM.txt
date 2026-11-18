REVORA MOTO RESMI WEB SITESI - KURULUM
=====================================

SAYFALAR
index.html        Ana sayfa
oyun.html         Oyun tanitimi
ozellikler.html   Ozellikler
indir.html        PC / Mobil indirme merkezi
iletisim.html     Iletisim
gizlilik.html     Web sitesi bilgilendirme / hukuki taslak

YAYINA ALMA
1. ZIP arsivini acin.
2. REVORA_MOTO_WEBSITE klasorunun ICINDEKI dosyalari Netlify sitesine surukleyin.
3. Alan adini Netlify panelinden baglayin.
4. assets/js/config.js dosyasini gercek sosyal medya adresleri ve destek e-postasiyla guncelleyin.
5. assets/images klasorundeki tanitim gorsellerini dilerseniz gercek oyun ici ekran goruntuleriyle degistirin.

WINDOWS EXE INDIRME
1. Windows kurulum dosyasi gercekten hazir oldugunda adi REVORA-MOTO-Setup.exe olacak sekilde dosyayi downloads/ klasorune koyun.
2. EXE'nin guvenilirliginden emin olun; zararlilara karsi kontrol, surum ve SHA-256 dogrulamasi yapin. Windows SmartScreen uyarilari icin kod imzalama dusunun.
3. assets/js/config.js: release.windows.available = true ve release.windows.file = 'downloads/REVORA-MOTO-Setup.exe' yapin. Size/date/version/sha256 alanlarini doldurun.
4. Buyuk EXE dosyalari icin CDN veya nesne depolama kullanmak daha verimli olabilir. Bu durumda file alanina dogrulanmis HTTPS indirme URL'si yazin; ayni dosyaya ait gercek link oldugundan emin olun.
5. Config dosyasi acikca dosya durumunu yonetir; EXE eklenmedigi surece sitede indirme butonu pasif kalir.
6. Kurulum paketi bu ZIP icerisinde YOKTUR. Ayrica eklenmesi gerekir.

ILETISIM
- assets/js/config.js icinde contactEmail alanini gercek destek adresiyle doldurun.
- Iletisim formu backend kullanmaz; mailto: uzerinden kullanicinin e-posta uygulamasini acar. Bos emailde form gondermez.

NOTLAR
- Sitede Google Fonts dis servisi kullanilir; tam offline hosting isterseniz fontlari degistirin.
- APK / App Store bağlantıları gerçek resmî mağaza adresleri çıkınca eklenmeli.
- Gizlilik politikasi sayfasi bir web bilgilendirme taslagidir, yasal inceleme gerektirir.
- Görseller daha önce bu sohbet için oluşturulmuş REVORA MOTO tanıtım varlıklarından kırpılmıştır; gerçek oyun ekran görüntüsü değildir.
- Yayina almadan once uygulama hakkindaki iddialari gercek surumle uyumlu tutun.

SOSYAL MEDYA GUNCELLEMESI (17.11.2026)
TikTok: https://www.tiktok.com/@hardcorerider11
Telegram: https://t.me/+flix45VnpHE5ZTc0
Iletisim formu kaldirildi; dogrudan sosyal medya kartlari eklendi. Instagram baglantisi verilmedigi icin gizlendi.
