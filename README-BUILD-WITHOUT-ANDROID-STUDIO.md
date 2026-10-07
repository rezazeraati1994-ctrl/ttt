# ساخت APK بدون Android Studio

این پروژه برای Build شدن روی GitHub Actions آماده شده است.

## روش استفاده

1. در GitHub یک Repository جدید بسازید.
2. تمام فایل‌های این پروژه را داخل Repository آپلود کنید.
3. وارد بخش **Actions** شوید.
4. Workflow با نام **Build Android APK** را انتخاب کنید.
5. روی **Run workflow** بزنید.
6. بعد از پایان Build، وارد اجرای موفق Workflow شوید.
7. در قسمت **Artifacts** فایل `RepairReports-debug-apk` را دانلود کنید.
8. داخل فایل ZIP، `app-debug.apk` قرار دارد.

این روش برای ساخت APK به Android Studio نیاز ندارد.
