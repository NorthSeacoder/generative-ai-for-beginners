<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "7f8f4c11f8c1cb6e1794442dead414ea",
  "translation_date": "2025-07-09T08:47:25+00:00",
  "source_file": "03-using-generative-ai-responsibly/README.md",
  "language_code": "ar"
}
-->
# استخدام الذكاء الاصطناعي التوليدي بمسؤولية

[![استخدام الذكاء الاصطناعي التوليدي بمسؤولية](../../../translated_images/03-lesson-banner.1ed56067a452d97709d51f6cc8b6953918b2287132f4909ade2008c936cd4af9.ar.png)](https://aka.ms/gen-ai-lesson3-gh?WT.mc_id=academic-105485-koreyst)

> _انقر على الصورة أعلاه لمشاهدة فيديو هذا الدرس_

من السهل أن تنجذب إلى الذكاء الاصطناعي وخاصة الذكاء الاصطناعي التوليدي، لكن من الضروري أن تفكر في كيفية استخدامه بمسؤولية. عليك أن تأخذ في الاعتبار أمورًا مثل ضمان أن تكون النتائج عادلة وغير ضارة وأكثر من ذلك. يهدف هذا الفصل إلى تزويدك بالسياق المذكور، وما يجب مراعاته، وكيفية اتخاذ خطوات فعالة لتحسين استخدامك للذكاء الاصطناعي.

## المقدمة

سيغطي هذا الدرس:

- لماذا يجب أن تعطي أولوية للذكاء الاصطناعي المسؤول عند بناء تطبيقات الذكاء الاصطناعي التوليدي.
- المبادئ الأساسية للذكاء الاصطناعي المسؤول وكيف ترتبط بالذكاء الاصطناعي التوليدي.
- كيفية تطبيق هذه المبادئ من خلال الاستراتيجية والأدوات.

## أهداف التعلم

بعد إتمام هذا الدرس ستعرف:

- أهمية الذكاء الاصطناعي المسؤول عند بناء تطبيقات الذكاء الاصطناعي التوليدي.
- متى تفكر وتطبق المبادئ الأساسية للذكاء الاصطناعي المسؤول عند بناء تطبيقات الذكاء الاصطناعي التوليدي.
- الأدوات والاستراتيجيات المتاحة لك لتطبيق مفهوم الذكاء الاصطناعي المسؤول عمليًا.

## مبادئ الذكاء الاصطناعي المسؤول

الحماس تجاه الذكاء الاصطناعي التوليدي لم يكن أعلى من أي وقت مضى. هذا الحماس جذب العديد من المطورين الجدد، والاهتمام، والتمويل لهذا المجال. وبينما هذا أمر إيجابي جدًا لأي شخص يسعى لبناء منتجات وشركات باستخدام الذكاء الاصطناعي التوليدي، من المهم أيضًا أن نتحرك بمسؤولية.

خلال هذا المساق، نركز على بناء شركتنا الناشئة ومنتجنا التعليمي للذكاء الاصطناعي. سنستخدم مبادئ الذكاء الاصطناعي المسؤول: العدالة، الشمولية، الموثوقية/السلامة، الأمان والخصوصية، الشفافية والمساءلة. من خلال هذه المبادئ، سنستكشف كيف ترتبط باستخدامنا للذكاء الاصطناعي التوليدي في منتجاتنا.

## لماذا يجب أن تعطي أولوية للذكاء الاصطناعي المسؤول

عند بناء منتج، اتباع نهج يركز على الإنسان مع وضع مصلحة المستخدم في الاعتبار يؤدي إلى أفضل النتائج.

ما يميز الذكاء الاصطناعي التوليدي هو قدرته على إنشاء إجابات مفيدة، ومعلومات، وإرشادات، ومحتوى للمستخدمين. يمكن تحقيق ذلك دون الحاجة إلى العديد من الخطوات اليدوية، مما يؤدي إلى نتائج مبهرة جدًا. لكن بدون تخطيط واستراتيجيات مناسبة، قد يؤدي ذلك للأسف إلى نتائج ضارة للمستخدمين، وللمنتج، وللمجتمع ككل.

لننظر إلى بعض (وليس كل) هذه النتائج الضارة المحتملة:

### الهلوسات

الهلوسات هو مصطلح يُستخدم لوصف حالة عندما ينتج نموذج اللغة الكبير محتوى إما غير منطقي تمامًا أو معروف أنه خاطئ بناءً على مصادر معلومات أخرى.

على سبيل المثال، إذا بنينا ميزة في شركتنا الناشئة تسمح للطلاب بطرح أسئلة تاريخية على نموذج. يسأل طالب السؤال `من كان الناجي الوحيد من تيتانيك؟`

ينتج النموذج ردًا مثل التالي:

![موجه يقول "من كان الناجي الوحيد من تيتانيك"](../../../03-using-generative-ai-responsibly/images/ChatGPT-titanic-survivor-prompt.webp)

> _(المصدر: [Flying bisons](https://flyingbisons.com?WT.mc_id=academic-105485-koreyst))_

هذا جواب واثق وشامل جدًا. للأسف، هو غير صحيح. حتى مع بحث بسيط، سيكتشف المرء أن هناك أكثر من ناجٍ واحد من كارثة تيتانيك. بالنسبة لطالب يبدأ للتو في البحث عن هذا الموضوع، قد يكون هذا الجواب مقنعًا بما يكفي لعدم التشكيك فيه واعتباره حقيقة. يمكن أن تؤدي عواقب ذلك إلى جعل نظام الذكاء الاصطناعي غير موثوق به ويؤثر سلبًا على سمعة شركتنا الناشئة.

مع كل إصدار جديد لأي نموذج لغة كبير، شهدنا تحسنًا في تقليل الهلوسات. ومع هذا التحسن، لا يزال علينا كمطوري تطبيقات ومستخدمين أن نكون واعين لهذه القيود.

### المحتوى الضار

تحدثنا في القسم السابق عن الحالات التي ينتج فيها نموذج اللغة الكبير ردودًا غير صحيحة أو غير منطقية. هناك خطر آخر يجب أن نكون على دراية به وهو عندما يرد النموذج بمحتوى ضار.

يمكن تعريف المحتوى الضار على أنه:

- تقديم تعليمات أو تشجيع على إيذاء النفس أو إيذاء مجموعات معينة.
- محتوى كريه أو مهين.
- توجيه تخطيط أي نوع من الهجمات أو الأفعال العنيفة.
- تقديم تعليمات حول كيفية العثور على محتوى غير قانوني أو ارتكاب أفعال غير قانونية.
- عرض محتوى جنسي صريح.

بالنسبة لشركتنا الناشئة، نريد التأكد من وجود الأدوات والاستراتيجيات المناسبة لمنع ظهور هذا النوع من المحتوى أمام الطلاب.

### نقص العدالة

تعرف العدالة بأنها "ضمان أن يكون نظام الذكاء الاصطناعي خاليًا من التحيز والتمييز وأن يعامل الجميع بعدل ومساواة." في عالم الذكاء الاصطناعي التوليدي، نريد التأكد من أن وجهات النظر الاستبعادية تجاه المجموعات المهمشة لا يتم تعزيزها من خلال مخرجات النموذج.

هذه الأنواع من المخرجات ليست فقط مدمرة لبناء تجارب منتج إيجابية لمستخدمينا، بل تسبب أيضًا ضررًا اجتماعيًا إضافيًا. كمطوري تطبيقات، يجب أن نضع دائمًا في اعتبارنا قاعدة مستخدمين واسعة ومتنوعة عند بناء حلول باستخدام الذكاء الاصطناعي التوليدي.

## كيفية استخدام الذكاء الاصطناعي التوليدي بمسؤولية

بعد أن حددنا أهمية الذكاء الاصطناعي التوليدي المسؤول، دعونا نلقي نظرة على 4 خطوات يمكننا اتخاذها لبناء حلول الذكاء الاصطناعي بمسؤولية:

![دورة التخفيف](../../../translated_images/mitigate-cycle.babcd5a5658e1775d5f2cb47f2ff305cca090400a72d98d0f9e57e9db5637c72.ar.png)

### قياس الأضرار المحتملة

في اختبار البرمجيات، نختبر الأفعال المتوقعة للمستخدم على التطبيق. وبالمثل، اختبار مجموعة متنوعة من الموجهات التي من المرجح أن يستخدمها المستخدمون هو طريقة جيدة لقياس الأضرار المحتملة.

نظرًا لأن شركتنا الناشئة تبني منتجًا تعليميًا، سيكون من الجيد إعداد قائمة بموجهات متعلقة بالتعليم. قد تغطي موضوعًا معينًا، حقائق تاريخية، وموجهات عن حياة الطلاب.

### التخفيف من الأضرار المحتملة

حان الوقت الآن لإيجاد طرق يمكننا من خلالها منع أو تقليل الضرر المحتمل الناجم عن النموذج وردوده. يمكننا النظر إلى هذا في 4 طبقات مختلفة:

![طبقات التخفيف](../../../translated_images/mitigation-layers.377215120b9a1159a8c3982c6bbcf41b6adf8c8fa04ce35cbaeeb13b4979cdfc.ar.png)

- **النموذج**. اختيار النموذج المناسب للحالة المناسبة. النماذج الأكبر والأكثر تعقيدًا مثل GPT-4 قد تسبب مخاطر أكبر من المحتوى الضار عند تطبيقها على حالات استخدام أصغر وأكثر تحديدًا. استخدام بيانات التدريب الخاصة بك لضبط النموذج يقلل أيضًا من خطر المحتوى الضار.

- **نظام السلامة**. نظام السلامة هو مجموعة من الأدوات والتكوينات على المنصة التي تخدم النموذج وتساعد في التخفيف من الضرر. مثال على ذلك هو نظام تصفية المحتوى في خدمة Azure OpenAI. يجب أن تكتشف الأنظمة أيضًا هجمات كسر الحماية والنشاط غير المرغوب فيه مثل الطلبات من الروبوتات.

- **الميتابرومبت**. الميتابرومبت والتأصيل هي طرق يمكننا من خلالها توجيه أو تقييد النموذج بناءً على سلوكيات ومعلومات معينة. قد يكون ذلك باستخدام مدخلات النظام لتحديد حدود معينة للنموذج. بالإضافة إلى ذلك، تقديم مخرجات أكثر صلة بنطاق أو مجال النظام.

يمكن أيضًا استخدام تقنيات مثل التوليد المعزز بالاسترجاع (RAG) لجعل النموذج يستمد المعلومات فقط من مجموعة مختارة من المصادر الموثوقة. هناك درس لاحق في هذا المساق حول [بناء تطبيقات البحث](../08-building-search-applications/README.md?WT.mc_id=academic-105485-koreyst)

- **تجربة المستخدم**. الطبقة النهائية هي حيث يتفاعل المستخدم مباشرة مع النموذج من خلال واجهة تطبيقنا بطريقة ما. بهذه الطريقة يمكننا تصميم واجهة المستخدم/تجربة المستخدم لتقييد المستخدم على أنواع المدخلات التي يمكنه إرسالها إلى النموذج وكذلك النصوص أو الصور المعروضة للمستخدم. عند نشر تطبيق الذكاء الاصطناعي، يجب أن نكون شفافين أيضًا بشأن ما يمكن وما لا يمكن لتطبيق الذكاء الاصطناعي التوليدي القيام به.

لدينا درس كامل مخصص لـ [تصميم تجربة المستخدم لتطبيقات الذكاء الاصطناعي](../12-designing-ux-for-ai-applications/README.md?WT.mc_id=academic-105485-koreyst)

- **تقييم النموذج**. العمل مع نماذج اللغة الكبيرة يمكن أن يكون تحديًا لأننا لا نتحكم دائمًا في البيانات التي تم تدريب النموذج عليها. ومع ذلك، يجب علينا دائمًا تقييم أداء النموذج ومخرجاته. من المهم قياس دقة النموذج، التشابه، التأصيل، وملاءمة المخرجات. هذا يساعد في توفير الشفافية والثقة لأصحاب المصلحة والمستخدمين.

### تشغيل حل ذكاء اصطناعي توليدي مسؤول

بناء ممارسة تشغيلية حول تطبيقات الذكاء الاصطناعي هو المرحلة النهائية. يشمل ذلك التعاون مع أجزاء أخرى من شركتنا الناشئة مثل الشؤون القانونية والأمن لضمان الامتثال لجميع السياسات التنظيمية. قبل الإطلاق، نريد أيضًا وضع خطط حول التسليم، التعامل مع الحوادث، والتراجع لمنع أي ضرر قد ينشأ لمستخدمينا.

## الأدوات

على الرغم من أن تطوير حلول الذكاء الاصطناعي المسؤول قد يبدو عملاً كثيرًا، إلا أنه يستحق الجهد. مع نمو مجال الذكاء الاصطناعي التوليدي، ستتطور المزيد من الأدوات لمساعدة المطورين على دمج المسؤولية بكفاءة في سير عملهم. على سبيل المثال، يمكن لـ [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview?WT.mc_id=academic-105485-koreyst) المساعدة في اكتشاف المحتوى والصور الضارة عبر طلب API.

## اختبار المعرفة

ما هي بعض الأمور التي يجب أن تهتم بها لضمان استخدام الذكاء الاصطناعي بمسؤولية؟

1. أن يكون الجواب صحيحًا.
1. الاستخدام الضار، بحيث لا يُستخدم الذكاء الاصطناعي لأغراض إجرامية.
1. التأكد من أن الذكاء الاصطناعي خالٍ من التحيز والتمييز.

الإجابة: 2 و 3 صحيحتان. الذكاء الاصطناعي المسؤول يساعدك على التفكير في كيفية التخفيف من الآثار الضارة والتحيزات وأكثر.

## 🚀 التحدي

اقرأ عن [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview?WT.mc_id=academic-105485-koreyst) وانظر ما يمكنك اعتماده لاستخدامك.

## عمل رائع، واصل تعلمك

بعد إتمام هذا الدرس، اطلع على [مجموعة تعلم الذكاء الاصطناعي التوليدي](https://aka.ms/genai-collection?WT.mc_id=academic-105485-koreyst) لمواصلة تطوير معرفتك في الذكاء الاصطناعي التوليدي!

توجه إلى الدرس 4 حيث سنستعرض [أساسيات هندسة الموجهات](../04-prompt-engineering-fundamentals/README.md?WT.mc_id=academic-105485-koreyst)!

**إخلاء المسؤولية**:  
تمت ترجمة هذا المستند باستخدام خدمة الترجمة الآلية [Co-op Translator](https://github.com/Azure/co-op-translator). بينما نسعى لتحقيق الدقة، يرجى العلم أن الترجمات الآلية قد تحتوي على أخطاء أو عدم دقة. يجب اعتبار المستند الأصلي بلغته الأصلية المصدر الموثوق به. للمعلومات الهامة، يُنصح بالاعتماد على الترجمة البشرية المهنية. نحن غير مسؤولين عن أي سوء فهم أو تفسير ناتج عن استخدام هذه الترجمة.