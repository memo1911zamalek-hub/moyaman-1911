# HB GROUP — متجر إلكتروني تجريبي

متجر ثابت مبني بـ HTML وCSS وJavaScript، ومتوافق مع الهاتف والكمبيوتر وجاهز للنشر على GitHub Pages.

## المزايا
- أقسام للعلامات الخمس: Red Bull وRauch وNutella وFerrero Rocher وRaffaello.
- صور لعبوات منتجات فعلية مرتبطة بمصادرها في بطاقة المنتج.
- بحث وفلاتر حسب العلامة والقسم، وترتيب بالسعر والاسم.
- سلة مشتريات مع تعديل الكميات والحذف، محفوظة محلياً في المتصفح.
- نموذج بيانات عميل ينشئ ملخص طلب قابل للنسخ.

## تشغيل الموقع
افتح `index.html` في متصفح حديث. يتطلب اتصالاً بالإنترنت لتحميل الخطوط وصور المنتجات الخارجية.

## النشر على GitHub Pages
1. أنشئ Repository جديداً.
2. ارفع `index.html` و`style.css` و`script.js` وملف `README.md`.
3. من Settings → Pages اختر Deploy from a branch.
4. اختر `main` و`/(root)` ثم Save.

## تعديل المنتجات
افتح `script.js` وعدّل مصفوفة `products`. خصائص المنتج هي: `id`, `brand`, `name`, `size`, `category`, `price`, `image`, `source`.
الأسعار بالدولار تقديرية، عدّلها قبل الاستخدام التجاري وفق قائمة أسعارك الفعلية.

## ملاحظات تشغيلية وقانونية
- هذا نموذج واجهة متجر Front-end فقط. السلة محفوظة في `localStorage` على جهاز الزائر ولا تصل إلى إدارة المتجر.
- لا توجد بوابة دفع، مخزون، تسجيل دخول، قاعدة بيانات، أو إرسال طلبات إلى خادم. لا تستخدمه لقبول مدفوعات فعلية قبل إضافة Backend آمن وبوابة دفع مناسبة.
- الصور روابط خارجية لمتاجر وصفحات منتجات/علامات تجارية؛ قد تتغير أو تمنع hotlink. استبدلها بصور تملك حق استخدامها، ويفضل حفظ صور مرخصة داخل مجلد `assets`.
- صور المنتجات ومصادرها:
  - Red Bull original: https://www.liquorland.co.nz/red-bull-can-250ml-90162602
  - Red Bull Sugarfree: https://www.continente.pt/produto/bebida-energetica-em-lata-gaseificada-sem-acucar-red-bull-red-bull-2747592.html
  - Rauch Happy Day apricot: https://shop.orient.at/tr/product/happy-day-marille-1l--31932
  - Rauch Happy Day orange: https://acemarket.ph/products/happy-day-orange-juice-1l
  - Nutella 350g: https://www.iceland.co.uk/p/nutella-hazelnut-chocolate-spread-jar-350g/63272.html
  - Nutella Biscuits 304g: https://www.amuse-bouche.shop/products/nutella-biscuits-resealable-bag
  - Ferrero Rocher 8 pieces: https://www.ferrerorocher.com/int/en/our-products/ferrero-rocher
  - Ferrero Rocher 16 pieces: https://www.knuspr.de/1083-ferrero-rocher
  - Raffaello 15 pieces: https://www.migros.com.tr/raffaello-150-g-p-6b6cf0
  - Raffaello Confetteria: https://www.ferrero.com/sk/sk/nase-znacky/raffaello
- HB GROUP مستخدم هنا كاسم وهوية بناءً على طلب صاحب المشروع؛ لا يشكل هذا الموقع إثباتاً لملكية الاسم أو وجود تفويض أو شراكة مع العلامات المذكورة.
