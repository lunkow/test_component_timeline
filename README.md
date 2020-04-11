# korus_timeline
Предварительное тестовое задание компании Корус


# Комментарий
Вёрстка компонента выполнена без применения javascript/jquery. Компонент подстраивается под ширину родительского элемента, для этого использован flex.

Т.к. для второй части задания не было дополнительных требований по реализации элементов управления - для их выполнения был выбран jQuery.


Ниже приведён текст задания.

# Часть 1
Необходимо сверстать таймлайн, как на макете, без использования изображений.

У таймлайна есть несколько состояний:
1. шаг не пройден (серый);
2. шаг в процессе (оранжевый);
3. шаг пройден (зеленый);

Лейбл может располагаться:
1. по центру чек-поинта (первый и последний лейблы выровнены по краю);
2. по центру прогресс-линии;
3. над таймлайном;
4. под таймлайном.

В идеале должен получиться универсальный компонент, который по переключению/добавлению класса будет выдавать нужный набор опций при одинаковой верстке.

От положения лейбла фактическое количество шагов меняться не должно (подумайте над тем, как убрать лишний шаг при переключении вида таймлайна). При удалении/добавлении шагов в верстке компонент не должен ломаться.

Таймлайн должен поддерживаться браузерами:
Firefox 50+, Google Chrome 59+, Safari 10+, IE 11+, Edge.

Можно использовать любые поддерживаемые свойства. Если действительно необходимо – то можно прибегнуть к помощи javascript/jquery. Но предпочтительнее чистая верстка «руками». Если получится без grid и flex – отлично.


#Часть 2 (не обязательная)
Заверстайте элементы управления таймлайном на той же странице. Переключение вида таймлайна и количества шагов.

Оцениваться будет:
- соответствие макету;
- валидность и чистота верстки;
- работоспособность компонента при изменении количества шагов, длины лейбла.
