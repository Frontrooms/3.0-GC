"ستحتاج إلى تنزيل هذين قبل أن تبدأ " <br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe <br>
https://www.mongodb.com/try/download/compass <br>
https://www.mongodb.com/try/download/community L<br>

## إعداد الخادم

1: انتقل إلى https://github.com/lassedds/3.0-GC/releases/tag/Release وقم بتنزيل إصدار GC3.0.
2: قم بتنزيل الموارد من هنا: https://github.com/lassedds/3.0-Resources
3: ضع الموارد داخل مجلد 3.0 GC // تذكر تغيير الاسم إلى "resources" تمامًا مثل ذلك.

4: انقر بزر الماوس الأيمن فوق ملف start_config.cmd وانقر فوق ** تحرير **. بعد ذلك ، يجب عليك العثور على المجلد "* bin *" الخاص بإصدار # java# المثبت لديك. يجب أن يكون في ** `C: \ Program Files \ Java \` ** ، هناك تفتح المجلد المسمى "* jdk-17.x.x.x *". ومن ثم فتح مجلد "* bin *" وانسخ مسار هذا الملف. يجب أن يبدو كالتالي: ** `C: \ Program Files \ Java \ jdk-17.x.x.x \ bin \` **. ثم ضع ذلك في ملف * start_config.cmd * كمتغير "* JAVA_PATH = *". 

5: يمكنك الآن فقط استخدام ملف * start.bat * لفتح الخادم.

6: ستحتاج الآن إلى الانتقال إلى مجلد 3.0 Genshin ووضع <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing"> هذا </a> في ملف كلا هذين الموقعين: <br>
1. "* مجلد اللعبة الخاص بك. / GenshinImpact_Data / Managed / Metadata *" <br>
2. "* مجلد اللعبة الخاص بك. / GenshinImpact_Data / Native / Data / Metadata *"

## دليل Fiddler

1: قم بتنزيل Fiddler classic <a href="https://www.telerik.com/download/fiddler"> هنا </a>.

2: بمجرد فتح Fiddler Classic ، انتقل إلى خيار ** Tools ** في الجزء العلوي من Fiddler وانقر على ** Options **.

3: في قائمة ** Options  ** سترى الكثير من القوائم الفرعية, ننتقل الآن الى ** HTTPS **. بمجرد النقر فوق ** HTTPS ** ، انقر فوق المربع الصغير بجوار النص "*Decrypt HTTPS traffic*". وقم بالضغط على نعم

4: بعد الخطوة الرابعة ، لا تغلق قائمة الخيارات ولكن اذهب إلى القائمة الفرعية ** Connections **. بمجرد دخولك إلى القائمة الفرعية ** Connections ** ، سترى نصًا يقول "* Fiddler Classiclistens onport *". بشكل افتراضي ، سيكون المنفذ "8888". سترغب في ** تغيير ** ذلك إلى أي شيء آخر ، أستخدم 8080.

5: يمكنك الآن النقر فوق ** موافق ** في قائمة الخيارات وابحث عن زر ** FiddlerScript **. بمجرد النقر فوق ذلك ، ستحصل على هذا البرنامج النصي <a href="https://github.lunatic.moe/fiddlerscript"> هنا </a>. الآن انسخ النص وارجع إلى Fiddler. استبدل النص الموجود بالنص الذي نسخته للتو ، ثم اضغط على الزر ** Save Script **.

6: الآن يمكنك تشغيل اللعبة ولكنك لم تنته بعد. بمجرد محاولة تسجيل الدخول ، ستحصل على بعض القوائم المنبثقة في Fiddler وتأكيدها جميعًا.

7: وهكذا تكون قد حصلت على إعداد Fiddler. أحسنت! إذا كان لديك أي أسئلة ، انضم إلى <a href="https://discord.gg/AYtB7Q2er8"> Discord </a>
