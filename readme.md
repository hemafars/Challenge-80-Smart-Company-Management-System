# 🏆 Challenge 80 Smart Company Management System
##  📝 فكرة المشروع

`  إنشاء نظام متكامل لإدارة بيانات الموظفين وحساب مستحقاتهم.`
##  📥 المدخلات
-  اسم الموظف.
-  الراتب الأساسي.
-  عدد ساعات العمل الإضافية.
-  أجر الساعة الإضافية.
-  سنوات الخبرة.
-  القسم.
-  هل الموظف مدير؟ (Yes / No)
##  📌 المطلوب خطوة بخطوة
-  احسب قيمة العمل الإضافي.
-  احسب الراتب قبل الزيادات.
-  إذا كانت الخبرة:
-  10 سنوات أو أكثر → زيادة 20%.
-  5 سنوات أو أكثر → زيادة 10%.
-  إذا كان الموظف مديرًا:أضف بدل إدارة قدره 5000 جنيه.
-  إذا تجاوز الراتب النهائي 50000 جنيه: خصم ضريبة 8%.
- احسب الراتب النهائي بعد جميع العمليات.
- اعرض تقريرًا كاملًا.
##  ⚠️ الشروط
-  جميع الحقول مطلوبة.
-  لا تقبل القيم السالبة.
-  ساعات العمل الإضافية يمكن أن تكون صفرًا.
##  📤 المخرجات المطلوبة
-  Employee Name
-  Department
-  Basic Salary
-  Overtime
-  Experience Bonus
-  Management Allowance
-  Tax
-  Final Salary
##  💡 مثال عملي

###  Input

-  Employee: Hema
-  Salary: 40000
-  Overtime Hours: 20
-  Hour Rate: 250
-  Experience: 11
-  Department: IT
-  Manager: Yes

###  Output

-  Basic Salary: 40000
-  Overtime: 5000
-  Experience Bonus: ...
-  Management Allowance: 5000
-  Tax: ...
-  Final Salary: ...

`  🚫 بدون الحل. حاول تصميم كل مشروع بنفسك كما لو كنت تبنيه لعميل حقيقي، مع واجهة HTML وحقول إدخال ورسائل واضحة، ثم اكتب`
`  منطق JavaScript خطوة بخطوة. بعد إنهاء هذه المجموعة ستكون جاهزًا للانتقال إلى تحديات تتطلب استخدام Functions لتنظيم`
`  الكود بشكل احترافي.`

ممتاز. بما أنك تريد أن يكون **Challenge 80** نفسه تدريبًا على **ECMAScript 6+ + TypeScript + React**، فأنا أقترح ألا نغيّر فكرة التحدي، بل نرفع مستواه تدريجيًا.

### 🏆 Challenge 80 — Smart Company Management System

**المستوى 1 — JavaScript ES6+**

* `const / let`
* Template Literals
* Arrow Functions عند الحاجة
* Destructuring عند الحاجة
* `const` و`let` بدل `var`
* `??` و`?.` إذا كان لها استخدام منطقي
* التحقق من المدخلات
* الحسابات والشروط
* DOM + Events
* بدون `var` وبدون syntax قديم.

**المستوى 2 — TypeScript**
بعد نجاح نسخة JavaScript، أعد **نفس المشروع** مع:

* `string`
* `number`
* `boolean`
* `type` أو `interface`
* تحديد أنواع المدخلات والنتائج
* تحديد نوع دوال الحسابات
* منع الأخطاء التي يمكن اكتشافها أثناء التطوير.

**المستوى 3 — React + TypeScript**
حوّل المشروع إلى تطبيق React:

* `EmployeeForm`
* `SalaryReport`
* `App`
* `useState`
* Props
* Event Handling
* Conditional Rendering
* TypeScript interfaces/types
* حساب الراتب بطريقة منظمة.
* لا تستخدم DOM مثل `document.getElementById()` داخل React.

### 🔥 ترتيب التنفيذ الذي أنصحك به

```text
Challenge 80
      │
      ▼
HTML + CSS
      │
      ▼
JavaScript ES6+
      │
      ▼
TypeScript
      │
      ▼
React
      │
      ▼
React + TypeScript
```

**والأهم:** لا أعطيك الحل في أي مرحلة. أنت تحاول أولًا، ثم ترسل لي الكود، وأنا أعمل لك **تقييم + تصحيح + شرح سطر بسطر + هل الكود متوافق مع ES6/TypeScript/React**.

وبما أنك طلبت أن تكون التحديات مثل مشروع حقيقي، سأعتبر **Challenge 80** من الآن تحديًا متعدد المراحل، وليس مجرد تمرين JavaScript.
