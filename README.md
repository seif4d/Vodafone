
<div align="center">
  <h1>🔴 V-Cash Pro | Premium Fintech</h1>
  <img src="https://www.vodafone.com/~/media/Images/V/vodafone/corp/logo/logo-dark.svg" alt="Vodafone Logo" width="100" />
  <br/>
  <h3>أداة ذكية لتحليل وإدارة السجلات المالية لـ فودافون كاش</h3>
  
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/seif4d/Vodafone/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
</div>

---

## 📌 عن المشروع (About)

**V-Cash Pro** هو تطبيق ويب من صفحة واحدة (SPA) يعمل بالكامل على متصفحك. يقوم التطبيق بقراءة ملفات النصوص (`.txt`) التي تحتوي على رسائل فودافون كاش الخاصة بك، ويقوم بتحليلها باستخدام "Parser" مخصص لتحويل النصوص العشوائية إلى لوحة تحكم مالية (Dashboard) احترافية وعصرية.

> **🔒 الخصوصية أولاً:** لا يوجد أي خادم (Server) خلفي. يتم معالجة جميع رسائلك المالية محلياً بنسبة 100% داخل متصفحك (Client-side) لضمان السرية التامة وحماية بياناتك.

## ✨ المميزات (Features)

*   **💳 واجهة مستخدم احترافية (Premium UI):** تصميم عصري يعتمد على الـ *Glassmorphism* مع بطاقة بنكية رقمية تفاعلية.
*   **📊 تحليل شامل للنفقات (Analytics):** تقسيم تلقائي لعملياتك إلى:
    *   سحب كاش (ATM/فروع).
    *   إيداع رصيد.
    *   شحن الموبايل والفواتير.
    *   مدفوعات الأونلاين (كروت VCN).
    *   حساب دقيق لـ **رسوم فودافون** المخصومة.
*   **👥 سجل الأشخاص (Contacts Net Balance):** تتبع دقيق لصافي الحسابات بينك وبين أي رقم (تعرف ليك كام وعليك كام).
*   **📈 حركة الأموال (Cash Flow):** شريط تقدم يوضح نسبة الدخل (Inflow) مقابل الإنفاق (Outflow).
*   **🔍 فلترة متقدمة (Smart Filtering):** تصفية العمليات بضغطة زر (وارد، صادر، سحب، إيداع، الكل).
*   **📱 متوافق مع الهواتف (Mobile First):** واجهة مصممة خصيصاً لتعمل كأنها تطبيق هاتف أصلي (PWA Ready).

## 🛠️ التقنيات المستخدمة (Tech Stack)

*   **Front-end:** HTML5, Vanilla JavaScript.
*   **Styling:** Tailwind CSS (عبر الـ CDN مع تخصيص الألوان لـ `voda-red`).
*   **Icons:** FontAwesome 6.4.
*   **Typography:** Google Fonts (`Cairo` للنصوص العربية، `Space Grotesk` للأرقام لتبدو كبطاقات البنوك).

## 🚀 طريقة الاستخدام (How to Use)

نظراً لأن التطبيق لا يحتاج إلى سيرفر، يمكنك تشغيله فوراً:

1. قم بتحميل المستودع (Clone the repo):
   ```bash
   git clone https://github.com/seif4d/Vodafone.git
   ```
2. افتح ملف `index.html` مباشرة في أي متصفح ويب حديث.
3. **كيفية استخراج البيانات:**
   * قم بتصدير رسائل فودافون كاش الخاصة بك من هاتفك بصيغة ملف نصي `.txt` (يمكن استخدام تطبيقات تصدير الرسائل SMS Backup).
   * اضغط على زر **"مزامنة السجلات الآن"** في التطبيق وارفع الملف.
4. استمتع برؤية تحليلاتك المالية الدقيقة! ⚡

## 📸 نظرة عامة على الواجهة (Screenshots)

*(يمكنك إضافة صور للتطبيق هنا لاحقاً عن طريق رفعها للمستودع وإضافة مساراتها)*

| الواجهة الرئيسية (Dashboard) | سجل العمليات (Transactions) | تفاصيل الأشخاص (Contacts) |
| :---: | :---: | :---: |
| ![Home](https://placehold.co/200x400/141414/E60000?text=Dashboard+Preview) | ![Transactions](https://placehold.co/200x400/141414/E60000?text=Transactions+Preview) | ![Contacts](https://placehold.co/200x400/141414/E60000?text=Contacts+Preview) |

## 🤝 المساهمة (Contributing)

نرحب بجميع المساهمات! إذا كان لديك فكرة لتطوير الـ Parser ليقرأ أنماط رسائل جديدة، أو تحسين في واجهة المستخدم:

1. قم بعمل Fork للمشروع.
2. أنشئ Branch جديد (`git checkout -b feature/AmazingFeature`).
3. قم بعمل Commit لتعديلاتك (`git commit -m 'Add some AmazingFeature'`).
4. ارفع التعديلات (`git push origin feature/AmazingFeature`).
5. افتح Pull Request.

## ⚠️ إخلاء مسؤولية (Disclaimer)

هذا المشروع هو أداة مفتوحة المصدر تم تطويرها بشكل مستقل ولا تتبع شركة فودافون (Vodafone) أو أي من شركاتها التابعة بأي شكل من الأشكال. تم إنشاء هذا التطبيق لغرض شخصي ولتسهيل قراءة البيانات المالية للمستخدمين. جميع العلامات التجارية المذكورة هي ملك لأصحابها.

---
<div align="center">
  صُنع بـ ❤️ بواسطة <a href="https://github.com/seif4d">Seif4D</a>
</div>
