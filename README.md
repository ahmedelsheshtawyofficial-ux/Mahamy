# مهامي — Android APK project

مشروع Android WebView يضم تطبيق مهامي داخل APK مستقل، مع الاحتفاظ بواجهة RTL والتخزين المحلي للمهام.

## Build

يتطلب Android SDK Platform 35 وJDK 17 وGradle 8.9:

```bash
gradle assembleDebug
```

الناتج: `app/build/outputs/apk/debug/app-debug.apk`

## GitHub Actions

ارفع هذا المشروع إلى مستودع GitHub ثم شغّل workflow المسمى **Build Mahamy APK** من تبويب Actions. سيظهر ملف APK كـ Artifact قابل للتنزيل.

ملاحظة: هذا بناء debug للتثبيت والاختبار الشخصي، وليس إصدار متجر Play موقّع بمفتاح نشر خاص.
