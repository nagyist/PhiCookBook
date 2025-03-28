<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "9f71f15fee9a73ecfcd4fd40efbe3070",
  "translation_date": "2025-03-27T02:34:33+00:00",
  "source_file": "CONTRIBUTING.md",
  "language_code": "ar"
}
-->
# المساهمة

هذا المشروع يرحب بالمساهمات والاقتراحات. معظم المساهمات تتطلب منك الموافقة على اتفاقية ترخيص المساهم (CLA) التي تُقر بأن لديك الحق في منحنا حقوق استخدام مساهمتك. للحصول على التفاصيل، قم بزيارة [https://cla.opensource.microsoft.com](https://cla.opensource.microsoft.com)

عند تقديم طلب سحب، سيقوم الروبوت الخاص بـ CLA تلقائيًا بتحديد ما إذا كنت بحاجة إلى تقديم CLA وسيضيف تعليقًا أو حالة تحقق على الطلب (مثلًا، فحص الحالة أو تعليق). ببساطة اتبع التعليمات المقدمة من الروبوت. ستحتاج إلى القيام بذلك مرة واحدة فقط عبر جميع المستودعات التي تستخدم CLA الخاص بنا.

## قواعد السلوك

هذا المشروع يتبع [قواعد السلوك المفتوحة المصدر من مايكروسوفت](https://opensource.microsoft.com/codeofconduct/). لمزيد من المعلومات، اقرأ [الأسئلة الشائعة حول قواعد السلوك](https://opensource.microsoft.com/codeofconduct/faq/) أو تواصل عبر [opencode@microsoft.com](mailto:opencode@microsoft.com) لأي أسئلة أو تعليقات إضافية.

## تحذيرات بشأن إنشاء القضايا

يرجى عدم فتح قضايا على GitHub لأسئلة الدعم العامة، حيث يجب استخدام قائمة GitHub لطلبات الميزات وتقارير الأخطاء. بهذه الطريقة يمكننا تتبع المشاكل أو الأخطاء الفعلية بسهولة وفصل المناقشات العامة عن الكود الفعلي.

## كيفية المساهمة

### إرشادات طلبات السحب

عند تقديم طلب سحب (PR) إلى مستودع Phi-3 CookBook، يرجى اتباع الإرشادات التالية:

- **استنساخ المستودع**: قم دائمًا باستنساخ المستودع إلى حسابك الخاص قبل إجراء التعديلات.

- **طلبات سحب منفصلة (PR)**:
  - قدم كل نوع من التغييرات في طلب سحب منفصل. على سبيل المثال، يجب تقديم إصلاحات الأخطاء وتحديثات الوثائق في طلبات سحب منفصلة.
  - يمكن دمج إصلاحات الأخطاء البسيطة وتحديثات الوثائق الصغيرة في طلب سحب واحد حيث يكون ذلك مناسبًا.

- **معالجة تعارضات الدمج**: إذا أظهر طلب السحب الخاص بك تعارضات في الدمج، قم بتحديث فرعك المحلي `main` ليعكس المستودع الرئيسي قبل إجراء التعديلات.

- **تقديم الترجمات**: عند تقديم طلب سحب للترجمة، تأكد من أن مجلد الترجمة يتضمن الترجمات لجميع الملفات في المجلد الأصلي.

### إرشادات الترجمة

> [!IMPORTANT]
>
> عند ترجمة النصوص في هذا المستودع، لا تستخدم الترجمة الآلية. تطوع فقط للترجمة في اللغات التي تجيدها.

إذا كنت تجيد لغة غير الإنجليزية، يمكنك المساعدة في ترجمة المحتوى. اتبع الخطوات التالية لضمان دمج مساهماتك بشكل صحيح:

- **إنشاء مجلد ترجمة**: انتقل إلى المجلد المناسب للقسم وقم بإنشاء مجلد ترجمة للغة التي تساهم فيها. على سبيل المثال:
  - بالنسبة لقسم المقدمة: `PhiCookBook/md/01.Introduce/translations/<language_code>/`
  - بالنسبة لقسم البدء السريع: `PhiCookBook/md/02.QuickStart/translations/<language_code>/`
  - استمر بهذا النمط للأقسام الأخرى (03.Inference، 04.Finetuning، إلخ).

- **تحديث المسارات النسبية**: عند الترجمة، قم بتعديل هيكل المجلد عن طريق إضافة `../../` إلى بداية المسارات النسبية داخل ملفات Markdown لضمان عمل الروابط بشكل صحيح. على سبيل المثال، قم بالتغيير كما يلي:
  - تغيير `(../../imgs/01/phi3aisafety.png)` إلى `(../../../../imgs/01/phi3aisafety.png)`

- **تنظيم الترجمات**: يجب وضع كل ملف مترجم في مجلد الترجمة الخاص بالقسم المقابل. على سبيل المثال، إذا كنت تترجم قسم المقدمة إلى الإسبانية، ستقوم بإنشاء ما يلي:
  - `PhiCookBook/md/01.Introduce/translations/es/`

- **تقديم طلب سحب كامل**: تأكد من تضمين جميع الملفات المترجمة لقسم معين في طلب سحب واحد. لا نقبل الترجمات الجزئية لقسم. عند تقديم طلب سحب للترجمة، تأكد من أن مجلد الترجمة يتضمن الترجمات لجميع الملفات في المجلد الأصلي.

### إرشادات الكتابة

لضمان التناسق عبر جميع الوثائق، يرجى اتباع الإرشادات التالية:

- **تنسيق الروابط**: ضع جميع الروابط في أقواس مربعة متبوعة بأقواس دائرية، بدون أي مسافات إضافية حولها أو داخلها. على سبيل المثال: `[example](https://www.microsoft.com)`.

- **الروابط النسبية**: استخدم `./` للروابط النسبية التي تشير إلى ملفات أو مجلدات في الدليل الحالي، و`../` لتلك الموجودة في دليل رئيسي. على سبيل المثال: `[example](../../path/to/file)` أو `[example](../../../path/to/file)`.

- **تجنب المواقع الخاصة بالدول**: تأكد من أن روابطك لا تحتوي على مواقع خاصة بالدول. على سبيل المثال، تجنب `/en-us/` أو `/en/`.

- **تخزين الصور**: قم بتخزين جميع الصور في مجلد `./imgs`.

- **أسماء الصور الوصفية**: قم بتسمية الصور بشكل وصفي باستخدام الأحرف الإنجليزية والأرقام والشرطات. على سبيل المثال: `example-image.jpg`.

## تدفقات العمل على GitHub

عند تقديم طلب سحب، سيتم تشغيل تدفقات العمل التالية للتحقق من التغييرات. اتبع التعليمات أدناه لضمان نجاح طلب السحب الخاص بك في فحص تدفقات العمل:

- [فحص المسارات النسبية المكسورة](../..)
- [فحص الروابط التي لا تحتوي على مواقع](../..)

### فحص المسارات النسبية المكسورة

يتأكد هذا التدفق من أن جميع المسارات النسبية في ملفاتك صحيحة.

1. للتأكد من أن روابطك تعمل بشكل صحيح، قم بتنفيذ المهام التالية باستخدام VS Code:
    - مرر المؤشر فوق أي رابط في ملفاتك.
    - اضغط على **Ctrl + Click** للانتقال إلى الرابط.
    - إذا نقرت على رابط ولم يعمل محليًا، فسوف يؤدي ذلك إلى تشغيل التدفق ولن يعمل على GitHub.

1. لإصلاح هذه المشكلة، قم بتنفيذ المهام التالية باستخدام اقتراحات المسارات المقدمة من VS Code:
    - اكتب `./` أو `../`.
    - سيقوم VS Code بتقديم خيارات متاحة بناءً على ما كتبته.
    - اتبع المسار بالنقر على الملف أو المجلد المطلوب للتأكد من صحة المسار.

بمجرد إضافة المسار النسبي الصحيح، قم بالحفظ ودفع التغييرات.

### فحص الروابط التي لا تحتوي على مواقع

يتأكد هذا التدفق من أن أي رابط ويب لا يتضمن موقعًا خاصًا بالدولة. نظرًا لأن هذا المستودع متاح عالميًا، من المهم ضمان أن الروابط لا تحتوي على مواقع بلدك.

1. للتحقق من أن روابطك لا تحتوي على مواقع الدول، قم بتنفيذ المهام التالية:

    - تحقق من نص مثل `/en-us/`، `/en/`، أو أي موقع لغة آخر في الروابط.
    - إذا لم تكن موجودة في الروابط، فسوف تجتاز هذا الفحص.

1. لإصلاح هذه المشكلة، قم بتنفيذ المهام التالية:
    - افتح مسار الملف الذي تم تحديده بواسطة التدفق.
    - قم بإزالة الموقع الخاص بالدولة من الروابط.

بمجرد إزالة الموقع الخاص بالدولة، قم بالحفظ ودفع التغييرات.

### فحص الروابط المكسورة

يتأكد هذا التدفق من أن أي رابط ويب في ملفاتك يعمل ويعيد رمز الحالة 200.

1. للتحقق من أن روابطك تعمل بشكل صحيح، قم بتنفيذ المهام التالية:
    - تحقق من حالة الروابط في ملفاتك.

2. لإصلاح أي روابط مكسورة، قم بتنفيذ المهام التالية:
    - افتح الملف الذي يحتوي على الرابط المكسور.
    - قم بتحديث الرابط إلى الرابط الصحيح.

بمجرد إصلاح الروابط، قم بالحفظ ودفع التغييرات.

> [!NOTE]
>
> قد تكون هناك حالات حيث يفشل فحص الرابط على الرغم من أن الرابط قابل للوصول. يمكن أن يحدث هذا لعدة أسباب، بما في ذلك:
>
> - **قيود الشبكة**: قد تحتوي خوادم GitHub Actions على قيود شبكة تمنع الوصول إلى بعض الروابط.
> - **مشاكل المهلة**: الروابط التي تستغرق وقتًا طويلًا للاستجابة قد تؤدي إلى خطأ مهلة في التدفق.
> - **مشاكل الخادم المؤقتة**: توقف الخادم المؤقت أو الصيانة يمكن أن يجعل الرابط غير متاح بشكل مؤقت أثناء التحقق.

**إخلاء المسؤولية**:  
تم ترجمة هذه الوثيقة باستخدام خدمة الترجمة بالذكاء الاصطناعي [Co-op Translator](https://github.com/Azure/co-op-translator). على الرغم من أننا نسعى لتحقيق الدقة، يرجى العلم أن الترجمات الآلية قد تحتوي على أخطاء أو معلومات غير دقيقة. يجب اعتبار الوثيقة الأصلية بلغتها الأصلية المصدر الموثوق. للحصول على معلومات حاسمة، يُوصى بالاستعانة بترجمة بشرية احترافية. نحن غير مسؤولين عن أي سوء فهم أو تفسير خاطئ ينشأ عن استخدام هذه الترجمة.