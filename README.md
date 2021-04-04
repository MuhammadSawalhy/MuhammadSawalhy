<div dir=rtl>


<div align=center>

![وقل ربي زدني علما](https://user-images.githubusercontent.com/42011920/113520880-3e6e9680-9596-11eb-9351-00d718c26fdc.png)

</div>


##  👨‍💻 محمد بن سمير الصوالحي

> طالب في كلية الهندسة جامعة الزقازيق، يحب البرمجة بل مولع بما فيها من جو المغامرة والمنافسة.

### بدايتي

كانت Visual Basic حينما أجبرت على تعلمها في الصف الثالث الإعدادي عندما كنت في السادسة عشر من عمري تقريبا، بدأت عمل آلة حاسبة دون معرفة البرمجة كائنية التوجه (ب.ك.ت OOP)، ومضيت في ذلك أياما وأياما طوالا، أحاول جاهدا أن أحاكي عمل الآلة الحاسبة الموجودة على نظام Win7، أبرمج بطريقة بدائية راميا بعض المتغيرات هنا وهناك دون تغليفها والعمل بمبدأ الـ encapsulation. كانت حينها باللغة الإنجليزية، نما لدي شعور الانتماء لأمتي والشعور بأهمية اللغة العربية فجعلتها برموز عربية فإني كنت أدرس الرياضيات باللغة العربية في التعليم ما قبل الجامعي. أضفت لها كثير من الميزات مثل حساب الفرق بين تاريخين لمعرفة العمر مثلا، وإجراء عملية جمع (سيجما)، وكان من أهم الأجزاء والذي كان مشروعا لم أتصور أن يكون همي الشاغل وأن يستمر معي إلى الآن، وأظنه سيرافقني معي طويلا، الرسم البياني للدوال الرياضية الصريحة (explicit function).

### الرسم البياني

كان في البداية جزءا من الآلة الحاسبة والذي لم يمضِ كثير من الوقت حتى كان به من التعقيد والخصائص ما دفعني لعزله في مشروع كامل بالـ VB.net تحت اسم GraphMaker. بعدها ، ولا أذكر ما السبب الرئيسي لذلك، حولت الكود بالكامل للغة <span dir=ltr>C#</span>، بعدما رأيت [هذا المشروع](https://www.codeproject.com/Articles/1191440/Graphing-Calculator-in-Csharp-with-LES) الذي كان مصدرا للإلهام حينها. تعرفت في ذلك المشروع على ما يسمى بالمحلل أو السابر (parser) الذي لي معه قصة مثيرة أيضا لا يتسع المقال لسردها. وخلال هذه الرحلة من VB.net إلى C#.net ثم نشر البرنامج على Microsfot Store، بدأت مغامرة جديدة.

### تطوير المواقع

خمن ماذا حصل، مشروع الرسم البياني 🙃، بدأت بعمل نسخة متواضعة ثم صارت تتحسن شيئا فشيئا أيضا بتخبط كما كنت، إذ أنني لم أتعلم الأدوات التي أعرفها الآن بفضل الله، مثل المُحَزِّمات bundlers، والمضمدات linters، والمنسقات formatters. أدي تطويري للمشروع بطريقة بدائية إلى الوقوف عاجزا فقد كان لابد من استعمال ما يسمى بالوحدات modules المنفصلة والتي يعتمد بعضها على بعض بالاستيراد والتصدير. استعملت Gulp ليقوم ببعض المهام المؤتمتة، وsass بدلا من css وpugjs بعد أن أصبح التعديل على لغة الوسوم التشعبية (ل.و.ت html) أمرا مزعجا، للاستفادة من مبدأ التقسيم والاعتمادية بين وحدات صغيرة ومخصصة، لصبح معي في النهاية [منتجا جاهزا للنشر](https://plotto.netlify.app/)، ليس أفضل ما يكون لكن كان أفضل ما عندي حينها. آها، تذكرت أني قد نشرت [موقعا](https://graphmaker.netlify.app/) قبل ذلك لأتدرب على ما تعلمته.

### الآن

أنا الآن مشتت بين الكلية وتعلم <span dir=ltr>C/C++</span>، التعمق في linux وخباياه، التبحر أكثر في عالم تطوير المواقع وما به من كم هائل من التقنيات والطرق المتشعبة، وكانت قد راودتني نفسي أيضا بتعلم الذكاء الاصطناعي واللغة اليافعة الشابة Rust، أسأل الله أن يزيدنا من علمه ويرزقنا التواضع.

<div dir=ltr>

```
    ███╗░░░███╗░█████╗░██╗░░██╗░█████╗░███╗░░░███╗███╗░░░███╗███████╗██████╗░
    ████╗░████║██╔══██╗██║░░██║██╔══██╗████╗░████║████╗░████║██╔════╝██╔══██╗
    ██╔████╔██║██║░░██║███████║███████║██╔████╔██║██╔████╔██║█████╗░░██║░░██║
    ██║╚██╔╝██║██║░░██║██╔══██║██╔══██║██║╚██╔╝██║██║╚██╔╝██║██╔══╝░░██║░░██║
    ██║░╚═╝░██║╚█████╔╝██║░░██║██║░░██║██║░╚═╝░██║██║░╚═╝░██║███████╗██████╔╝
    ╚═╝░░░░░╚═╝░╚════╝░╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░░░░╚═╝╚═╝░░░░░╚═╝╚══════╝╚═════╝░

                    ░██████╗░█████╗░███╗░░░███╗██╗██████╗░
                    ██╔════╝██╔══██╗████╗░████║██║██╔══██╗
                    ╚█████╗░███████║██╔████╔██║██║██████╔╝
                    ░╚═══██╗██╔══██║██║╚██╔╝██║██║██╔══██╗
                    ██████╔╝██║░░██║██║░╚═╝░██║██║██║░░██║
                    ╚═════╝░╚═╝░░╚═╝╚═╝░░░░░╚═╝╚═╝╚═╝░░╚═╝

░█████╗░██╗░░░░░░░░░░░░██████╗░█████╗░░██╗░░░░░░░██╗░█████╗░██╗░░░░░██╗░░██╗██╗░░░██╗
██╔══██╗██║░░░░░░░░░░░██╔════╝██╔══██╗░██║░░██╗░░██║██╔══██╗██║░░░░░██║░░██║╚██╗░██╔╝
███████║██║░░░░░█████╗╚█████╗░███████║░╚██╗████╗██╔╝███████║██║░░░░░███████║░╚████╔╝░
██╔══██║██║░░░░░╚════╝░╚═══██╗██╔══██║░░████╔═████║░██╔══██║██║░░░░░██╔══██║░░╚██╔╝░░
██║░░██║███████╗░░░░░░██████╔╝██║░░██║░░╚██╔╝░╚██╔╝░██║░░██║███████╗██║░░██║░░░██║░░░
╚═╝░░╚═╝╚══════╝░░░░░░╚═════╝░╚═╝░░╚═╝░░░╚═╝░░░╚═╝░░╚═╝░░╚═╝╚══════╝╚═╝░░╚═╝░░░╚═╝░░░
```

