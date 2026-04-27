# 🛡️ ID-Shield - الهوية البديلة المؤقتة

![ID-Shield Logo](https://absher.sa/portal/individuals/assets/images/absher_logo.svg)

## 📋 نظرة عامة

**ID-Shield** هو نظام لإدارة الهوية البديلة المؤقتة، مصمم لتوفير حل آمن وسهل الاستخدام لإصدار والتحقق من الهويات المؤقتة. المشروع مستوحى من منصة أبشر ويوفر واجهة مستخدم عربية احترافية.

---

## ✨ الميزات الرئيسية

- 🔐 **تسجيل الدخول الآمن** — نظام مصادقة مع التحقق من صحة المدخلات  
- 🆔 **إنشاء هوية بديلة مؤقتة** — توليد أرقام عشوائية مع صلاحية زمنية  
- ⏱️ **عد تنازلي** — عرض الوقت المتبقي لصلاحية الهوية  
- ✅ **التحقق من الهوية** — التحقق من صحة وصلاحية الأرقام المؤقتة  
- 📋 **نسخ الرقم** — نسخ الرقم بسهولة إلى الحافظة  
- 📱 **تصميم متجاوب** — يعمل على جميع الأجهزة  

---

## 🚀 الصفحات

| الصفحة | المسار | الوظيفة |
|--------|--------|----------|
| تسجيل الدخول | `index.html` | واجهة المصادقة |
| الصفحة الرئيسية | `home.html` | لوحة التحكم |
| إنشاء هوية | `numberrandom.html` | توليد الهوية المؤقتة |
| التحقق | `verification.html` | التحقق من الهوية |

---

## 🛠️ التقنيات المستخدمة

- HTML5  
- CSS3  
- Bootstrap 5.3  
- Font Awesome 6  
- Bootstrap Icons  
- JavaScript  
- LocalStorage  

---

## 📦 التثبيت والتشغيل

### 1️⃣ استنساخ المشروع
```bash
git clone https://github.com/yourusername/id-shield.git
cd id-shield
```

### 2️⃣ تشغيل المشروع
- افتح ملف `index.html` مباشرة في المتصفح  
- أو استخدم Live Server في VS Code  

---

## 💻 الاستخدام

### 🔐 تسجيل الدخول
1. افتح `index.html`  
2. أدخل اسم المستخدم (3 أحرف على الأقل)  
3. أدخل كلمة المرور (6 أحرف على الأقل)  
4. اضغط "تسجيل الدخول"  

> ⚠️ ملاحظة: هذه محاكاة فقط (لا يوجد تحقق حقيقي)

---

### 🆔 إنشاء هوية بديلة
1. من الصفحة الرئيسية اختر **خدماتي**  
2. اضغط **الهوية البديلة المؤقتة**  
3. اختر **إنشاء رقم جديد**  
4. انسخ الرقم أو شاركه  

---

### ✅ التحقق من هوية
1. انتقل إلى **التحقق من الهوية**  
2. أدخل الرقم  
3. اضغط **تحقق**  

---

## 📁 هيكل المشروع

```
id-shield/
├── index.html
├── home.html
├── numberrandom.html
├── verification.html
├── style.css
└── README.md
```

---

## 🎨 التخصيص

### ⏱️ تغيير مدة الصلاحية
```javascript
const expire = new Date(now.getTime() + 60 * 60 * 1000);
```

---

### 🎨 تغيير الألوان
```css
:root {
  --primary-color: #00663d;
  --primary-dark: #007050;
  --light-bg: #f5f7f8;
}
```

---

## 🔒 الأمان

> ⚠️ هذا المشروع **تعليمي فقط**، ولا يجب استخدامه في بيئة حقيقية بدون:
- نظام Backend حقيقي  
- HTTPS  
- تشفير البيانات  
- حماية من XSS و CSRF  

---

## 🤝 المساهمة

1. Fork المشروع  
2. إنشاء فرع جديد  
```bash
git checkout -b feature/new-feature
```
3. إضافة التعديلات  
```bash
git commit -m "Add new feature"
```
4. رفع التغييرات  
```bash
git push origin feature/new-feature
```
5. فتح Pull Request  

---

## 📞 جهات الاتصال

- 📧 support@id-shield.com  
- 📞 920020405  
- 🐦 https://twitter.com  

---

## 📄 الترخيص

مرخص تحت **MIT License**  

---

## 🌐 English Overview

**ID-Shield** is a temporary identity management system that allows users to generate and verify temporary IDs securely.

### Features
- Secure login  
- Temporary ID generation  
- Expiration countdown  
- Verification system  
- Responsive UI  

---

💡 **Developed by ID-Shield Team © 2024**
