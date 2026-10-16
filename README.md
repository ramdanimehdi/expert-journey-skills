# رحلة الخبير | Expert Journey

![رحلة الخبير](assets/gpt-icon.png)

مجموعة من 27 مهارة أعدّها **مهدي رمضاني (Mehdi Ramdani)**، مؤسس Cash From Skill، للمدربين والخبراء والمستشارين. ترافق المدرب من تشخيص المشروع وبناء عرضه إلى تخطيط البيع وكتابة الويبينار والمحتوى وتجهيز المواد التدريبية، ثم قياس التحويل وتصميم الاستمرارية عند ملاءمتها.

الحزمة متاحة للاستخدام دون رسم إضافي من الناشر، ولا تحتاج API key أو خادم MCP أو قاعدة بيانات أو اشتراك في خدمة خارجية. حساب أداة الذكاء الاصطناعي وميزاته وحدوده تبقى وفق شروط مزوّدها. لا تُرسل الحزمة أعمالك إلى مهدي أو إلى هذا المستودع.

## اختر طريقة الاستخدام

| بيئتك | الطريقة |
|---|---|
| ChatGPT لسطح المكتب أو Codex مع دعم المهارات المستقلة | ثبّت مجلدات المهارات معًا، مع مراجعها وملفاتها المساعدة |
| محادثة ChatGPT العادية على الويب | استخدم [برومبت البداية](WEB_CHAT_STARTER.md) وأرفق ملفات المهمة؛ هذه طريقة استخدام يدوي للمحتوى، وليست تثبيتًا تلقائيًا للمهارات |
| متجر البلاجن | المصدر الحالي 0.8.0 مهيأ ببنية مهارات وبلاجن، ولم يُرسل للمراجعة. المسودة السابقة 0.7.2 اجتازت فحوص 17 مهارة وبقي قيد قبول المهارات فقط عند تحقق سابق في 16 أكتوبر 2026؛ هذا لا يثبت فحص الإصدار الجديد أو قبول نشره |

فتح رابط GitHub لا يثبت المهارات تلقائيًا داخل حساب ChatGPT. إتاحة المهارات ورفع الملفات تختلف حسب الحساب والواجهة.

## التثبيت في Codex

1. نزّل المستودع من **Code → Download ZIP** ثم فك الضغط.
2. انسخ **جميع المجلدات داخل `skills/`** إلى مجلد المهارات الشخصي `~/.agents/skills/`، أو إلى `.agents/skills/` داخل مشروعك. إذا وجدت مهارة بالاسم نفسه، احتفظ بنسختها أولًا ولا تستبدلها دون مراجعة.
3. حافظ على أسماء المجلدات وعلى `references/` و`agents/` وأي ملفات مساعدة داخلها. المهارات مرتبطة ببعضها بمسارات نسبية، لذلك لا يكفي تثبيت مهارة فرعية وحدها.
4. ابدأ بطلب: «استخدم مهارة instructions من رحلة الخبير لمساعدتي في مشروع تدريبي». ثم اذكر المطلوب ومعلوماتك المتاحة.
5. إذا لم تظهر المهارات، أعد تشغيل جلسة Codex.

يمكن أيضًا أن تطلب من `$skill-installer` تثبيت مجلدات المهارات الـ27 من رابط هذا المستودع معًا. اترك له فحص الروابط والتعارضات قبل التثبيت.

لـChatGPT على سطح المكتب: افتح Skills واستخدم خيارات الإنشاء أو الاستيراد التي تعرضها نسختك. لا نفترض وجود زر استيراد واحد في جميع الحسابات. إذا تعذر الاستيراد، استخدم طريقة المحادثة اليدوية أدناه.

## الاستخدام داخل محادثة عادية

1. افتح [برومبت البداية](WEB_CHAT_STARTER.md) وانسخه في محادثتك.
2. نزّل وأرفق [التعليمات المشتركة](skills/instructions/SKILL.md) وملف `SKILL.md` للمهمة من الجدول أدناه.
3. إذا أحال ملف المهمة إلى مرجع، أرفق المرجع المطلوب معه عند الحاجة. أخبر المساعد أن الملفات المرفقة تعليمات عمل من اختيارك؛ تطبق ضمن إمكانات حسابك وتعليمات الأداة.
4. أكمل العمل في المحادثة نفسها. لبدء محادثة جديدة، اطلب ملخص المشروع ثم انسخه مع الملفات ذات الصلة. الحزمة لا توفر ذاكرة مستقلة أو تخزينًا دائمًا.

## المهارات

| المهمة | الملف |
|---|---|
| البداية والتوجيه بين المهارات | [instructions](skills/instructions/SKILL.md) |
| تشخيص المشروع | [expert-project-analysis](skills/expert-project-analysis/SKILL.md) |
| العرض وسلم القيمة | [expert-offer](skills/expert-offer/SKILL.md) |
| اختيار الفانل | [expert-funnel-selection](skills/expert-funnel-selection/SKILL.md) |
| جذب العملاء | [expert-lead-generation](skills/expert-lead-generation/SKILL.md) |
| خطة التسويق والميزانية | [expert-marketing-plan](skills/expert-marketing-plan/SKILL.md) |
| نصوص الصفحات | [expert-funnel-pages](skills/expert-funnel-pages/SKILL.md) |
| برومبت تصميم الصفحة | [expert-page-prompt](skills/expert-page-prompt/SKILL.md) |
| نص الإعلان | [expert-ad-copy](skills/expert-ad-copy/SKILL.md) |
| رسائل المتابعة | [expert-followup](skills/expert-followup/SKILL.md) |
| سكريبتات الريلز | [expert-reels](skills/expert-reels/SKILL.md) |
| ميمز تعليمية | [expert-meme-reels](skills/expert-meme-reels/SKILL.md) |
| التيليبرومبتر | [expert-teleprompter](skills/expert-teleprompter/SKILL.md) |
| الكاروسيل | [expert-carousel](skills/expert-carousel/SKILL.md) |
| الصورة الواحدة | [expert-single-post](skills/expert-single-post/SKILL.md) |
| المواد التدريبية وأوراق العمل | [expert-training-materials](skills/expert-training-materials/SKILL.md) |
| مراجعة الأسلوب | [expert-humanizer](skills/expert-humanizer/SKILL.md) |
| كتابة النصوص التسويقية | [write-expert-sales-copy](skills/write-expert-sales-copy/SKILL.md) |
| تخطيط الفانل وسلم القيمة | [plan-expert-sales-funnels](skills/plan-expert-sales-funnels/SKILL.md) |
| رسالة الخبير وقصته | [build-expert-message-webinar](skills/build-expert-message-webinar/SKILL.md) |
| بناء الويبينار المثالي | [craft-perfect-webinar](skills/craft-perfect-webinar/SKILL.md) |
| وصفات الفانل والصفحات | [assemble-expert-funnel-recipes](skills/assemble-expert-funnel-recipes/SKILL.md) |
| العضوية والاستمرارية | [design-expert-continuity](skills/design-expert-continuity/SKILL.md) |
| تحسين فانل الفيديو البيعي | [optimize-expert-vsl-funnel](skills/optimize-expert-vsl-funnel/SKILL.md) |
| تشخيص التحويل والمبيعات | [diagnose-expert-funnel-growth](skills/diagnose-expert-funnel-growth/SKILL.md) |
| جذب العملاء المناسبين | [attract-expert-dream-customers](skills/attract-expert-dream-customers/SKILL.md) |
| العرض المتكامل وعدسات القيمة | [grand-slam-offer](skills/grand-slam-offer/SKILL.md) |

## أمثلة للبدء

- «أنا مدرب تواصل في الجزائر. ساعدني على بناء عرض لأول ورشة مدفوعة، وميّز المقترحات عن المعلومات المؤكدة.»
- «حوّل هذه المادة إلى برومبتين لتصميم ورقة عمل عربية A4: للمشارك ثم للمدرب، مع وضع الحل في دليل المدرب فقط.»
- «اكتب 5 سكريبتات ريلز للتوعية، بهويتي ولهجتي ودون اختراع نتائج أو شهادات.»

تستخدم الحزمة اسمك وهويتك ولهجتك، ولا تضيف توقيع مهدي أو روابط شراء إلى أعمالك. صياغة برومبت تصميم لا تعني أن ملفًا أو فيديو أُنتج بالفعل. إنتاج الملفات والصور يحتاج أداة مستقلة متاحة في بيئتك، ولا يفرض عليك استخدام خدمة مدفوعة.

## ما أُضيف في الإصدار 0.8.0

أُبقيت المهارات السابقة الـ17 ومراجعها، وأُضيفت المنهجيات العشر المرفقة كمهارات فعلية لها أسماء ووصف استدعاء، مع ربطها بالمخرج المناسب. التفاصيل تُقرأ عند الحاجة حتى لا تفرض الحزمة منهجيات متعددة على كل طلب.

- [خريطة شمول المرفقات](ATTACHMENTS_COVERAGE.md): تبين موضع كل ملف وما جرى توضيحه في صياغته.
- [مصمم المواد التدريبية المفصل](skills/expert-training-materials/references/arabic-presentation-design.md): جميع قواعد الشرائح وA4 والتمارين ودليل المدرب، مع Cairo افتراضًا وهوية المستخدم أولًا.
- [دليل الويبينار التطبيقي الكامل](skills/craft-perfect-webinar/references/mehdi-webinar-workbook.md) و[ملفه الأصلي](skills/craft-perfect-webinar/assets/Perfect_Webinar_Practical_Guide_Mehdi_Ramdani.docx): القصص والتعليم والعرض والتذكير والبروفة والقياس وأوراق العمل.

مثلًا: «اكتب ويبينارًا من 60 دقيقة اعتمادًا على عرضي وهذه القصص، ثم جهّز برومبت شرائحه». أو «شخّص بيانات فانلي وحدّد أول تجربة». أو «قيّم هل أحتاج عضوية بعد برنامجي».

## المصادر والحدود

تتضمن الحزمة مراجع تعليمية مختارة من مواد مهدي الأصلية، ولا تتضمن الكتب الخارجية الكاملة. لا ترفع معلومات عملاء حساسة أو كلمات مرور أو رموز وصول. إرشادات التسويق تعليمية؛ النتائج تعتمد على التنفيذ والسوق ولا توجد ضمانات دخل أو مبيعات.

حقوق الإعداد والمراجع محفوظة لمهدي رمضاني. الإتاحة العامة لا تعني نقل ملكية المراجع أو منح ترخيص مفتوح شامل لإعادة توزيع الكتب. استخدم المخرجات في أعمالك باسمك. لم يُضف ترخيص يسمح بإعادة ترخيص الحزمة أو بيعها باسم آخر.

الدعم والتعريف: [صفحة رحلة الخبير](https://cashfromskill.online/expert-journey/index.html) — [الدعم](https://cashfromskill.online/expert-journey/support.html) — [الخصوصية](https://cashfromskill.online/expert-journey/privacy.html) — [الشروط](https://cashfromskill.online/expert-journey/terms.html).

## English

Expert Journey is a collection of 27 Arabic-first skills prepared by Mehdi Ramdani for trainers, experts, and consultants. It includes business planning, offers, funnels, marketing drafts, social content, and training-material design workflows. No MCP server, API key, or publisher subscription is required. Use the complete sibling skill set to preserve relative references. Standalone skill installation depends on the client; a GitHub link does not install a plugin in ordinary web chat. A manual chat starter is included. Publisher-authored references remain subject to their original rights; no blanket open-source license is granted.

Official setup reference: [Build skills](https://learn.chatgpt.com/docs/build-skills).
