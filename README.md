# Mahmoud Tash - Interactive 3D Developer Portfolio 🚀

موقع البورتفوليو التفاعلي ثلاثي الأبعاد للمطور **محمود طاش (Mahmoud Tash)** — مطور ويب متكامل ومتخصص في أتمتة الذكاء الاصطناعي (Full-Stack Developer & AI Automation Specialist).

الموقع مبني بتقنيات **Three.js** و **React Three Fiber** و **Next.js**، ويحتوي على غرفة ثلاثية الأبعاد تفاعلية كاملة مع مؤثرات إضاءة، وضع النهار والليل، تفاعل مع القطة، مشغل موسيقى أسطوانات، شاشة حاسوب لعرض المشاريع، وجولة تفاعلية من 6 خطوات.

---

## 🌟 مميزات المشروع (Features)

- 🎮 **غرفة ثلاثية الأبعاد تفاعلية بالكامل (Interactive 3D Room)**: تحكم كامل بالكاميرا وزوايا الرؤية.
- 📦 **مشهد البداية (Interactive Unboxing)**: التمرير أو النقر لفتح الصندوق وبدء الجولة.
- 🌓 **وضع النهار والليل (Day / Night Mode)**: تبديل فوري للإضاءة مع محاكاة حركة الشمس والقمر.
- 💡 **مصباح الغرفة (Interactive Lamp)**: تشغيل وإطفاء إضاءة الغرفة بالنقر المباشر على المصباح في المشهد.
- 🐱 **القطة التفاعلية (Interactive Cat)**: استجابة للنقر (Pet the cat) مع حركات وأصوات ومسارات تنقل داخل الغرفة.
- 🖥️ **شاشة الحاسوب (PC Screen Display)**: عرض حي للمشاريع، وإضاءة RGB تفاعلية لكيس الكمبيوتر.
- 🎶 **مشغل الأسطوانات (Turntable)**: تشغيل وإيقاف الأسطوانة بحركات واقعية.
- 🧭 **جولة توجيهية (6-Step Guided Tour)**:
  1. `Welcome` - البداية والترحيب.
  2. `The Room` - استعراض الغرفة.
  3. `About and Tools` - النبذة التعريفية والمهارات والتقنيات.
  4. `Projects` - المشاريع وأعمال الأتمتة.
  5. `How I Build` - منهجية العمل والتطوير.
  6. `Contact` - بيانات التواصل وروابط المنصات.
- 📱 **صفحات مخصصة**:
  - `/projects` - أرشيف المشاريع الكامل مع عروض GIF وروابط المعاينة.
  - `/contact` - نموذج المراسلة المباشرة وبيانات الاتصال.

---

## 👨‍💻 بيانات المطور (Developer Info)

- **الاسم:** Mahmoud Tash (محمود طاش)
- **المسمى الوظيفي:** Full-Stack Developer & AI Automation Specialist
- **البريد الإلكتروني:** [mahmoudtash3@gmail.com](mailto:mahmoudtash3@gmail.com)
- **رقم الهاتف:** `+201285845497`
- **الموقع:** Tanta, Gharbia, Egypt (طنطا، الغربية، مصر)
- **فيسبوك:** [Facebook Profile](https://www.facebook.com/profile.php?id=61577182824601)

---

## 🚀 التشغيل محلياً (Run Locally)

المشروع جاهز تماماً للتشغيل الفوري بدون الحاجة لتثبيت حزم خارجية إضافية:

```bash
# 1. الدخول لمجلد المشروع
cd mahmoud-tash-portfolio

# 2. تشغيل السيرفر المحلي
npm start
# أو مباشرة:
node server.js
```

افتح المتصفح على: **http://localhost:3000**

---

## ☁️ الرفع والنشر (Deployment)

### 1. النشر على Vercel (الأسهل والأفضل مجاناً ⭐⭐⭐)
1. ارفع هذا المستودع إلى حسابك على GitHub.
2. ادخل على [Vercel](https://vercel.com) واضغط **"Add New Project"**.
3. اختر مستودع `mahmoud-tash-portfolio` من حسابك على GitHub.
4. اضغط **"Deploy"** مباشرة (الملف `vercel.json` مجهز للتعامل مع الروابط والـ Caching تلقائياً وبدون أي إعدادات إضافية).

### 2. النشر على GitHub Pages
1. أنشئ مستودعاً على GitHub باسم: `YOUR_USERNAME.github.io` (أو أي اسم مع تفعيل GitHub Pages).
2. ارفع ملفات هذا المجلد للفرع `main`.
3. ادخل على **Settings** > **Pages** > اختر الفرع **main** والمجلد **/ (root)**.
4. (الملف `.nojekyll` موجود مسبقاً لضمان تحميل مجلد `_next` بدون أي مشاكل).

### 3. النشر على Render أو Railway
- يعمل كـ Web Service باستخدام الأمر: `node server.js`.

---

## 📂 بنية المشروع (Project Structure)

```
mahmoud-tash-portfolio/
├── index.html            # الصفحة الرئيسية والمشهد التفاعلي 3D
├── server.js             # سيرفر Node.js محلي وسحابي خفيف وسريع
├── package.json          # تعريف المشروع والأوامر
├── vercel.json           # إعدادات النشر المباشر على Vercel
├── .nojekyll             # دعم GitHub Pages لمجلدات _next
├── .gitignore            # الملفات المستثناة من Git
├── favicon.ico           # أيقونة الموقع
├── fonts/                # خطوط Space Grotesk المخصصة
├── projects/             # صفحة الأرشيف وعروض المشاريع
├── contact/              # صفحة التواصل المخصصة
└── _next/                # حزم React Three Fiber و Three.js و Webpack
```

---

## 📜 الترخيص (License)
MIT License - مفتوح المصدر للاستخدام والتطوير.
