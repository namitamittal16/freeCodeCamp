---
title: Use Bracket Notation to Find the Last Character in a String
localeTitle: استخدم Bracket Notation لإيجاد الحرف الأخير في سلسلة
---
## استخدم Bracket Notation لإيجاد الحرف الأخير في سلسلة

خذ بعين الاعتبار السلسلة التالية:

 `var str = "Coding"; 
` 

يبلغ طول هذه السلسلة 6 أحرف ، لذا إذا استخدمت .length على السلسلة ، فستعطيك 6. لكن تذكر أن الحرف الأول في الموضع الصفري. الحرف الثاني هو في الموضع الأول. الحرف الثالث هو في الموضع الثاني.

استمر في العمل ، وستحصل في النهاية على الحرف السادس (الذي ، استنادًا إلى السلسلة أعلاه ، هو 'g') في المركز الخامس. هذا هو السبب في حصولك على آخر حرف لسلسلة ، مع:

 `var lastChar = str[str.length - 1]; // This is 6 - 1, which is 5 
` 

هذا سيكون "ز".