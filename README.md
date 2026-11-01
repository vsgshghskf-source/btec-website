# موقع مدرسة البلقاء الثانوية الشاملة المختلطة | نظام BTEC

## التشغيل
1. افتح المجلد في VS Code (File ▸ Open Folder).
2. ثبّت إضافة **Live Server** (ستظهر كاقتراح تلقائي).
3. اضغط بالزر الأيمن على `index.html` ▸ **Open with Live Server**.
(يعمل أيضًا بفتح `index.html` مباشرة في المتصفح.)

## البنية
```
index.html          الصفحة (كل الأقسام والمحتوى)
css/                الأنماط، مرتبة بنفس ترتيب الـ cascade الأصلي
  variables.css  base.css  gate.css  navigation.css  hero.css
  components.css  specs.css  pages.css  game.css  footer.css
  luxe.css          الهوية اللونية الفاخرة
  devices.css       التوافق مع الهواتف والتابلت واللابتوب والشاشات الكبيرة
  gate2.css         بوابة الدخول
  pro.css           الخلفية الشفقية والبطاقات المتوهجة وشريط المهارات
  responsive.css    التجاوب مع الهاتف والأجهزة اللوحية
  polish.css        اللمسات الاحترافية (احذف رابطه من index.html للرجوع للشكل الأصلي)
js/
  data.js           بيانات التخصصات وأسئلة اللعبة (عدّل المحتوى من هنا)
  specs.js          تبويبات التخصصات
  gate.js           بوابة الدخول
  theme.js          الوضع الداكن/الفاتح
  game.js           لعبة تحدّي BTEC
  router.js         التنقل بين الصفحات (#hash)
  effects.js        وهج البطاقات وعدّاد الأرقام
  main.js           شريط التقدم، السنة، ظهور العناصر
images/             نسخ SVG مستقلة من الشعار
icons/  fonts/      مجلدات جاهزة لإضافة موارد
```
**ملاحظة:** ترتيب ملفات CSS و JS في `index.html` مهم، فلا تغيّره.
