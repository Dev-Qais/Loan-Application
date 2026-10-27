# Loan Application Form

واجهة React بسيطة لتقديم طلب الحصول على قرض من بنك. يملأ المستخدم بياناته الأساسية، ثم يتحقق التطبيق من العمر ورقم الهاتف ويعرض نتيجة إرسال الطلب داخل نافذة منبثقة.

> **تنبيه:** هذا المشروع واجهة أمامية تعليمية فقط. لا يتم إرسال البيانات إلى بنك أو خادم، ولا يمثل قراراً ائتمانياً حقيقياً. لا تستخدم بيانات شخصية حقيقية عند تجربة المشروع.

## المميزات

- نموذج لإدخال الاسم ورقم الهاتف والعمر.
- تحديد ما إذا كان مقدم الطلب موظفاً.
- اختيار شريحة الراتب.
- التحقق من أن العمر بين 18 و100 عاماً.
- التحقق من أن رقم الهاتف يتكون من 10 إلى 12 رقماً.
- عرض رسالة نجاح أو رسالة خطأ داخل نافذة منبثقة.
- تصميم متجاوب مناسب للتجربة على الشاشات المختلفة.

## التقنيات المستخدمة

- [React](https://react.dev/)
- [Vite](https://vite.dev/)
- JavaScript (JSX)
- CSS
- ESLint

## تشغيل المشروع محلياً

### المتطلبات

- Node.js إصدار 18 أو أحدث.
- npm.

### خطوات التشغيل

1. نزّل المشروع أو استنسخه من GitHub.
2. افتح مجلد المشروع في الطرفية.
3. ثبّت الحزم:

   ```bash
   npm install
   ```

4. شغّل خادم التطوير:

   ```bash
   npm run dev
   ```

5. افتح الرابط الذي يظهر في الطرفية، وغالباً يكون:
   `http://localhost:5173`

## أوامر مفيدة

```bash
# تشغيل بيئة التطوير
npm run dev

# فحص الكود باستخدام ESLint
npm run lint

# إنشاء نسخة الإنتاج
npm run build

# معاينة نسخة الإنتاج محلياً
npm run preview
```

## بنية المشروع

```text
requestingAloan/
├── public/                 # الملفات العامة والأيقونات
├── src/
│   ├── assets/             # الصور والموارد
│   ├── App.jsx             # المكوّن الرئيسي
│   ├── LoanForm.jsx        # نموذج طلب القرض والتحقق من البيانات
│   ├── Modal.jsx           # نافذة رسائل النجاح والأخطاء
│   ├── App.css             # تنسيقات التطبيق العامة
│   └── Loan.css            # تنسيقات النموذج والنافذة المنبثقة
├── index.html
├── package.json
└── vite.config.js
```


## English

**Loan Application Form** is a small React/Vite frontend for submitting a bank-loan request. It collects basic applicant information, validates the age and phone number, and displays the submission result in a modal.

This is an educational frontend demo. It does not send data to a bank or backend and must not be used with real personal information.
