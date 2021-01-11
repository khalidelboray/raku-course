---
title: How to install Rakudo
---

{% include menu.html %}

لتشغيل برنامج في لغة Raku, ستحتاج الي مترجم مثبت. زُر  [the website of Rakudo](https://rakudo.org) لكي  تحمل النسخة المناسبة لنظام تشغيلك. 

يوجد نوعين اساسين. يمكنك تثبيت المترجم نفسه او تثبيت حزمة Rakudo Star, Rakudo Star يتضمن مدير حزم وبعض الحزم المفيدة.

## Sources

يمكنك تحميل أداة التثبيت المناسبة لنظامك من [rakudo.org/downloads](https://rakudo.org/downloads). يوجد نسخ لكل انظمة التشغيل الرئيسية : ويندوز , نظام ماك ولينكس. ويوجد ايضا مصادر مفتوحة يمكنك تحميعها بنفسك.

## Rakudo Star

يمكن ايضا تثبيت الحزمة، Rakudo Star، عن طريق تشغيل اداة التثبيت التي تحصل عليها من<a href="https://rakudo.org/star" target="_blank">rakudo.org/star</a>. تاكد من رقم النسخة قبل التثبيت. يمكنك ايضا رؤية صفحة <a href="https://rakudo.org/star/third-party" target="_blank">3rd-Party Rakudo Star Bundle Packages</a>  للمزيد من الخيارات.

## Docker images

و Rakduo Star متاح ك docker image. يمكنك استخدامه لتشغيل البرامج واختبار البرامج النصية البسيطة في واجهة REPL. كل التعليمات متاحة في <a href="https://github.com/Raku/docker" target="_blank">github.com/Raku/docker</a>

## Version numbers

نظام ترقيم نسخ Rakudo ينسق رقم النسخة كرقم مكون من جزئين: سنة وشهر تاريخ الإصدار. يمكنك رؤية مدي مواكبة نسختك من المترجم بكل سهولة. نفذ هذا الأمر في سطر الأوامر لعرض رقم النسخة:


```console
$ raku -v
Welcome to 𝐑𝐚𝐤𝐮𝐝𝐨™ v2020.10.
Implementing the 𝐑𝐚𝐤𝐮™ programming language v6.d.
Built on MoarVM version 2020.10.
```

يمكنك رؤية ثلاثة أرقام اصداؤ هنا. الأول هة نسخة مترجم Rakudo نفسه: `v2020.10`. ثم يأتي اصدار لغة Raku: `v6.4`. التحديثات حاليا سوف تحصل علي الحرف الجديد كجزء اصدار فرعي، مثلا ، `v6.e` ، الخ. واخيرا، نري اسم الآلة الافتراضيى المستخدمة في المترجم: MoarVM version `2020.10`


{% include nav.html %}
