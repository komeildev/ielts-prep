IELTS Prep — GitHub Pages / iPad

فایل‌های اصلی:
- index.html
- vocabulary.html
- collocation.html
- manifest.webmanifest
- sw.js
- apple-touch-icon.png
- icons/

نصب روی GitHub Pages:
1) یک Repository جدید بساز.
2) تمام محتویات این پوشه را در ریشه Repository آپلود کن.
3) Settings > Pages
4) Source را روی Deploy from a branch بگذار.
5) Branch: main و Folder: /(root)
6) Save و چند دقیقه صبر کن.
7) لینک GitHub Pages را با Safari در iPad باز کن.
8) Share > Add to Home Screen.

ذخیره پیشرفت:
- Vocabulary در localStorage با کلید ielts-prep-vocabulary-v1 ذخیره می‌شود.
- Collocation در localStorage با کلید ielts-collocation-lab-v1 ذخیره می‌شود.
- در همان دامنه/آدرس GitHub Pages، فردا و روزهای بعد پیشرفت باقی می‌ماند.
- آپدیت کردن فایل‌های Repository پیشرفت را پاک نمی‌کند.
- پاک کردن Website Data/Safari data یا تغییر دامنه می‌تواند داده را جدا/پاک کند.
- از صفحه اصلی می‌توان از هر دو بخش با یک فایل JSON پشتیبان گرفت و بعداً بازیابی کرد.

آفلاین:
Service Worker فایل‌های اصلی را cache می‌کند؛ بعد از اولین بازدید آنلاین، برنامه در حالت عادی آفلاین هم باز می‌شود.
