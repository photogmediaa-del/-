# 📖 دليل رفع المشروع على GitHub

## الخطوة 1 — إنشاء حساب GitHub
- اذهب إلى: https://github.com
- اضغط **Sign up** وأنشئ حساباً مجانياً

---

## الخطوة 2 — إنشاء مستودع جديد
1. بعد الدخول اضغط زر **"+"** في الأعلى
2. اختر **"New repository"**
3. اسم المستودع: `baladiya-karma`
4. الوصف: `نظام إدارة معاملات مديرية بلدية الكرمة`
5. اختر **Public** (مجاني)
6. ✅ ضع علامة على **"Add a README file"** — لا، لأن عندنا واحد
7. اضغط **"Create repository"**

---

## الخطوة 3 — رفع الملفات (طريقة سهلة بدون Git)

### من المتصفح مباشرة:
1. في صفحة المستودع الجديد اضغط **"uploading an existing file"**
2. **اسحب وأفلت** هذه الملفات كلها:
   - `index.html`
   - `admin.html`
   - `citizen.html`
   - `vonage-sms.html`
   - `README.md`
   - `netlify.toml`
   - `.gitignore`
3. في خانة **"Commit changes"** اكتب: `رفع النظام الأولي`
4. اضغط **"Commit changes"** ✅

---

## الخطوة 4 — الربط مع Netlify (نشر تلقائي)

1. اذهب إلى: https://app.netlify.com
2. سجّل دخول بحساب GitHub
3. اضغط **"Add new site"** ← **"Import an existing project"**
4. اضغط **"GitHub"**
5. اختر مستودع `baladiya-karma`
6. الإعدادات تلقائية — اضغط **"Deploy site"**
7. بعد دقيقة سيظهر رابط مثل: `https://random-name.netlify.app`

### تغيير اسم الرابط:
- في Netlify: Site settings ← Site name ← غيّر الاسم
- مثال: `baladiya-karma.netlify.app`

---

## ✅ النتيجة النهائية

| الصفحة | الرابط |
|--------|--------|
| الرئيسية | `https://baladiya-karma.netlify.app` |
| بوابة المواطن | `https://baladiya-karma.netlify.app/citizen.html` |
| لوحة الإدارة | `https://baladiya-karma.netlify.app/admin.html` |
| SMS | `https://baladiya-karma.netlify.app/vonage-sms.html` |

---

## 🔄 تحديث الملفات لاحقاً

كل مرة تعدّل ملفاً:
1. افتح المستودع على GitHub
2. اضغط على الملف
3. اضغط أيقونة ✏️ **Edit**
4. عدّل وافظ **"Commit changes"**
5. Netlify يحدّث الموقع تلقائياً خلال ثوانٍ ✅
