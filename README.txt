SP للهاتف — بناء ملف APK عبر GitHub (مرة واحدة، مجاناً)

1) أنشئ حساباً على github.com (إن لم يكن عندك)
2) New repository ← اكتب اسماً (مثلاً sp) ← Create repository
3) اضغط "uploading an existing file" ثم اسحب إليه محتويات هذا المجلد (ليس الزيب نفسه).
   مهم: يجب أن يصل المجلد المخفي .github مع الملف build.yml داخله.
   إن لم يظهر: Add file ← Create new file ← اكتب الاسم  .github/workflows/build.yml
   والصق فيه محتوى الملف build.yml من هذا المجلد، ثم Commit.
4) تبويب Actions ← Build SP Android ← Run workflow
5) بعد 5–10 دقائق ادخل على العملية الناجحة ← Artifacts ← SP-android ← نزّله وفك الضغط ← app-debug.apk
6) انقله للهاتف وثبّته (فعّل "التثبيت من مصادر غير معروفة").

النسخ الاحتياطية على الهاتف تُحفظ في: الملفات ← Documents ← SP
بيانات الهاتف منفصلة عن الحاسوب. لنقلها: انسخ ملف الزيب من SP-Data\backups إلى الهاتف ثم "استرجاع".
