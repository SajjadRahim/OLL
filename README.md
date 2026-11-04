# مكتبة أوربس للتعريبات · Orbis Localization Library

تطبيق لجهاز PS4 (مع GoldHEN) تتصفح فيه تعريبات الألعاب العربية وتثبّتها بضغطة زر.
هذا المستودع للتنزيل فقط: كل إصدار من التطبيق ينشر هنا كملف PKG جاهز للتثبيت.

## ⬇️ التنزيل

**[نزّل آخر إصدار](https://github.com/SajjadRahim/OLL/releases/latest)**: الملف `OLL-<الإصدار>.pkg`.

ملف `update.json` في صفحة الإصدار يستخدمه التطبيق في التحديث الذاتي، وما تحتاج تنزله.

## المتطلبات

- جهاز PS4 مهكّر وعليه **GoldHEN**.
- اتصال بالإنترنت لتصفح التعريبات وتنزيلها، أو فلاشة USB فيها ملفات التعريب.

## التثبيت

1. انسخ ملف `OLL-<الإصدار>.pkg` إلى فلاشة USB، أو إلى `/data/pkg` على الجهاز.
2. ثبّته من **Debug Settings > Package Installer** في GoldHEN، أو من أي أداة تثبيت PKG.
3. شغّل **مكتبة أوربس للتعريبات** من الشاشة الرئيسية.

## التحديث

التطبيق يتحقق بنفسه من الإصدارات الجديدة هنا. عند توفر تحديث، روح إلى
**الإعدادات > حول التطبيق > تحديث التطبيق**، فينزّل الإصدار الجديد ويتحقق من توقيعه
ويحفظه في `/data/pkg`، وبعدها ثبّته من Package Installer.

---

## English

A PS4 app (GoldHEN) for browsing and installing Arabic game translations.
This repository only hosts the released app; each version is published under
[Releases](https://github.com/SajjadRahim/OLL/releases/latest) as a
ready-to-install `OLL-<version>.pkg`.

**Install:** copy the pkg to a USB drive (or `/data/pkg`) and install it with
GoldHEN's Debug Settings > Package Installer.

**Update:** the app checks this repository's latest release
(Settings > About > App update), downloads the new pkg, verifies its signature,
and saves it to `/data/pkg` so you can install it from the Package Installer.
`update.json` in each release is that signed update file.
