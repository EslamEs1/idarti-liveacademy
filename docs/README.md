# دليل الوثائق - مشروع IDARTI Live Academy

## نظرة عامة
هذا المشروع عبارة عن منصة أكاديمية للتعليم المباشر والمسجل. نعمل حاليًا على **Frontend Only** - تصميم الواجهات فقط باستخدام Bootstrap من مجلد `assets` المحلي.

## 🎯 الملفات الأساسية للقراءة (بالترتيب)

### أولاً: للنظام الداخلي (System)
1. **docs/system/01-idea.md** - الفكرة الأساسية للنظام والأدوار والكيانات
2. **docs/system/02-design-steps.md** - خطة تنفيذ التصميم، الصفحات، القواعد
3. **docs/system/03-progress.md** - ⚠️ **يجب قراءته أولاً!** - ملف التقدم (يُحدّث عند كل خطوة)

### ثانياً: للموقع الخارجي (Website)
1. **docs/website/01-idea.md** - فكرة الموقع التسويقي والصفحات
2. **docs/website/02-progress.md** - ⚠️ **يجب قراءته أولاً!** - ملف التقدم (يُحدّث عند كل خطوة)

## 📝 ملفات المفاتيح للتحرير
**ملاحظة هامة:** هذه هي الملفات التي **يجب** تحديثها عند كل خطوة تقدم:
- ⚠️ `docs/system/03-progress.md` - سجل التقدم للنظام (اقرأه أولاً!)
- ⚠️ `docs/website/02-progress.md` - سجل التقدم للموقع (اقرأه أولاً!)

## الملفات الثابتة المستخدمة
- `assets/css/bootstrap.min.css` - Bootstrap الأساسي
- `assets/css/bootstrap.rtl.min.css` - Bootstrap للاتجاه RTL
- `assets/css/custom_*.css` - تخصيصات إضافية (يحمل خط JF-Flat-Regular)
- `assets/js/bootstrap.min.js` - Bootstrap JS
- `assets/js/popper.min.js` - Popper.js للـ Tooltips/Popovers
- `assets/js/custom_*.js` - سكريبتات مخصصة
- `assets/fonts/JF-Flat-Regular.ttf` - خط عربي مريح
- `assets/img/` - مجلد الصور (فارغ حاليًا)

## القواعد الأساسية ⚠️ مهم جداً!
1. Bootstrap من مجلد `assets` فقط - لا CDN
2. **Frontend Only - تصميم HTML ثابت فقط** - لا باك إند
3. لا نستخدم CSS/JS مخصص إذا كان متاحًا في Bootstrap
4. اتجاه RTL افتراضيًا وخط JF-Flat-Regular للـ body (محمل في `custom_*.css`)
5. **تصميم احترافي جدًا يجب أن يبهر المستخدمين** 😍

## الملفات الثابتة الجاهزة
- ✅ `assets/css/bootstrap.min.css`
- ✅ `assets/css/bootstrap.rtl.min.css`
- ✅ `assets/css/custom_*.css` (يحتوي على خط JF-Flat-Regular)
- ✅ `assets/js/bootstrap.min.js`
- ✅ `assets/js/popper.min.js`
- ✅ `assets/js/custom_*.js`
- ✅ `assets/fonts/JF-Flat-Regular.ttf`

## الهدف الحالي
تصميم الواجهات (HTML + Bootstrap) للنظام الداخلي والموقع التسويقي.

## 🚀 عند البدء في تصميم صفحة جديدة
1. اقرأ `docs/README.md` (هذا الملف) أولاً
2. اقرأ `docs/system/03-progress.md` أو `docs/website/02-progress.md` حسب التوجه
3. اقرأ الملف المناسب من `01-idea.md` أو `02-design-steps.md`
4. قم بتصميم الصفحة باستخدام Bootstrap فقط
5. حدّث ملف `03-progress.md` أو `02-progress.md` لتسجيل ما تم إنجازه

