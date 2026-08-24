# مريومتي — نسخة GitHub خفيفة

## الملفات
- `index.html` — الصفحة الرئيسية.
- `images/` — الصور المستخدمة في الصفحة.
- `videos/` — الفيديوهات المستخدمة في الصفحة.
- `audio/` — الموسيقى المستخدمة في الصفحة.

## إضافة فيديو جديد
1. ضع ملف الفيديو داخل `videos/`، مثل `videos/video3.mp4`.
2. افتح `index.html`.
3. داخل قسم الفيديوهات أضف:

```html
<video controls playsinline preload="metadata">
  <source src="videos/video3.mp4" type="video/mp4">
</video>
```

لا تضع الفيديو بصيغة Base64 داخل HTML؛ بهذه الطريقة يظل `index.html` خفيفًا.

## إضافة صورة جديدة
ضع الصورة داخل `images/` ثم استخدم:

```html
<img src="images/photo16.jpg" alt="">
```
