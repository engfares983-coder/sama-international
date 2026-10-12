# موقع سما إنترناشونال

## رفع الموقع على GitHub Pages

1. ادخل على github.com واعمل حساب لو مش عندك.
2. دوس **New repository** واكتب اسم، مثلًا `sama-international`، وخليه **Public**، ودوس **Create repository**.
3. في صفحة الـ repository دوس **uploading an existing file**.
4. اسحب **كل اللي جوه فولدر `sama-site`**: ملف `index.html` وفولدر `assets` (مش الفولدر نفسه، اللي جواه).
5. دوس **Commit changes**.
6. روح **Settings ← Pages**. تحت **Branch** اختار `main` و `/ (root)` ودوس **Save**.
7. استنى دقيقة أو اتنين. الموقع هيبقى على:
   `https://اسم-حسابك.github.io/sama-international/`

## تعديل البيانات

افتح `index.html` بأي محرر نصوص (Notepad أو VS Code)، وانزل لجزء **الإعدادات: عدّل هنا بس** في أول الـ `<script>`:

- `PHONE`: رقم الواتساب (دولي من غير +).
- `MAIL`: الإيميل.
- `MAP_QUERY` و `MAP_LABEL`: عنوان الخريطة. ممكن تحط الإحداثيات من خرائط جوجل، مثلًا `'25.4052,55.5136'`.
- `OFFERS`: العروض. اكتب `price` و `old` بالدرهم عشان يظهر السعر.
- `OFFERS_END`: تاريخ نهاية العروض عشان العداد التنازلي يظهر، مثلًا `'2026-11-30T23:59:00+04:00'`.
- `STORIES`: الفيديوهات والكلام اللي عليها.

بعد التعديل ارفع `index.html` تاني على GitHub (Add file ← Upload files) وهيتحدث لوحده.

## إضافة فيديو جديد

حط الفيديو (mp4، أقل من 25 ميجا) وصورة منه (jpg) في فولدر `assets`، وزوّد عنصر في `STORIES` بنفس شكل اللي موجودين.
