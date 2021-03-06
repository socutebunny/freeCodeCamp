---
title: Iterate with JavaScript for Loops
localeTitle: تكرّر مع JavaScript لـ Loops
---
ويسمى النوع الأكثر شيوعا من جافا سكريبت حلقة ل `for loop` لأنه يعمل `for` عدد معين من المرات.

 `var ourArray = []; 
 for(var i = 0; i < 5; i++) { 
  ourArray.push(i); 
 } 
` 

سيحتوي ourArray الآن \[0،1،2،3،4\]

## المزيد عن الحلقات

 `for(var i = 0; i < 5; i++) {  // There are 3 parts here 
` 

هناك ثلاثة أجزاء للحلقة. يتم فصلها بواسطة فواصل منقوطة.

1.  التهيئة: `var i = 0;` - يعمل هذا الرمز مرة واحدة فقط في بداية الحلقة. عادة ما يتم استخدامه لتعريف متغير العداد (مع `var` ) وتهيئة العداد (في هذه الحالة يتم تعيينه إلى 0).
    
2.  الشرط: `i < 5;` - سيتم تشغيل الحلقة طالما أن هذا `true` . وهذا يعني أنه بمجرد `i` يساوي 5، وحلقة تتوقف حلقات. لاحظ أن داخل حلقة لن ترى `i` الى 5 لأنها سوف تتوقف قبل ذلك الحين. إذا كان هذا الشرط `false` البداية ، فلن يتم تنفيذ الحلقة أبدًا.
    
3.  الزيادة: `i++` - يتم تشغيل هذا الرمز في نهاية كل حلقة. عادة ما تكون الزيادة البسيطة ( `++` operator) ، ولكن يمكن أن يكون أي تحول رياضي. يتم استخدامه لنقل العداد ( `i` ) إلى الأمام (أو إلى الوراء ، أو أيا كان.