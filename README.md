# 🏛️ مديرية بلدية الكرمة — نظام إدارة المعاملات

<div align="center">

![Version](https://img.shields.io/badge/version-3.0-gold)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![License](https://img.shields.io/badge/license-Private-red)

**نظام إلكتروني متكامل لإدارة معاملات مديرية بلدية الكرمة — محافظة الأنبار**

[🌐 العرض المباشر](https://your-site.netlify.app) • [📋 admin](https://your-site.netlify.app/admin.html)

</div>

---

## 📁 هيكل المشروع

```
baladiya-karma/
│
├── index.html          ← الصفحة الرئيسية (روابط النظام)
├── citizen.html        ← بوابة المواطن (تقديم الطلبات)
├── admin.html          ← لوحة الإدارة (للموظفين)
├── vonage-sms.html     ← أداة اختبار SMS
│
├── netlify.toml        ← إعدادات Netlify
└── README.md           ← هذا الملف
```

---

## ✨ المميزات الرئيسية

### 🏠 بوابة المواطن
- تقديم طلبات لـ 6 أقسام: البيئة / تنظيم المدن / الحدائق / إجازة البناء / الطرق / الصحة البيئية
- رفع صور مرفقة (حتى 5 صور)
- استعلام عن حالة الطلب برقم المرجع

### ⚙️ لوحة الإدارة
- **3 مستويات صلاحية:** مدير / مشرف / موظف
- إدارة كاملة للطلبات (اعتماد / رفض / أرشفة)
- **6 قوالب طباعة:** رسمي / إيصال / مذكرة داخلية / ملخص مدير / متابعة / أرشفة
- إرسال SMS تلقائي عند تغيير الحالة (Vonage / Twilio / Custom API)
- إحصائيات وتقارير تفصيلية (Chart.js)
- استنساخ المعاملات
- تصدير CSV
- سجل أحداث أمني

### 🔐 الأمان
- تشفير كلمات المرور SHA-256
- قفل تلقائي بعد محاولات فاشلة
- انتهاء الجلسة تلقائياً
- سجل أحداث كامل

---

## 🔑 بيانات الدخول (للاختبار)

> ⚠️ **يجب تغيير كلمات المرور قبل الاستخدام الرسمي**

| المستخدم | كلمة المرور | الصلاحية |
|---------|------------|---------|
| `admin` | `Admin@2025` | مدير النظام |
| `supervisor` | `Super@2025` | مشرف |
| `employee` | `Emp@2025` | موظف |

---

## 🚀 طريقة الرفع على Netlify

### الطريقة السريعة (Drag & Drop):
1. افتح [app.netlify.com/drop](https://app.netlify.com/drop)
2. اسحب مجلد المشروع كاملاً
3. ✅ جاهز خلال ثوانٍ

### من GitHub (تلقائي):
1. ارفع المشروع على GitHub
2. ادخل [app.netlify.com](https://app.netlify.com)
3. اضغط **"Import from Git"**
4. اختر المستودع — سيُنشر تلقائياً ✅

---

## 📲 إعداد SMS (Vonage)

1. سجّل حساباً في [vonage.com](https://vonage.com)
2. من لوحة التحكم انسخ **API Key** و **API Secret**
3. في الإدارة: الإعدادات ← SMS ← اختر Vonage ← أدخل البيانات

```
API Key:    xxxxxxxx
API Secret: xxxxxxxxxxxxxxxx
From:       Vonage APIs
```

---

## 🛠️ التقنيات المستخدمة

| التقنية | الاستخدام |
|--------|---------|
| HTML5 / CSS3 | الهيكل والتصميم |
| JavaScript ES6 | المنطق البرمجي |
| LocalStorage | تخزين البيانات |
| Chart.js 4.4 | الرسوم البيانية |
| SubtleCrypto | تشفير SHA-256 |
| Vonage REST API | إرسال SMS |
| Google Fonts (Cairo/Tajawal) | الخطوط العربية |

---

## 📞 التواصل

**مديرية بلدية الكرمة — محافظة الأنبار — الجمهورية العراقية**

---

<div align="center">
نظام إدارة المعاملات الإلكترونية © 2025
</div>
