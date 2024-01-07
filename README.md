Задание 2. Создание приложения для проверки введённой строки на соответствие формату номера мобильного телефона



Что нужно сделать
Возьмите за основу приложение по работе с регулярными выражениями, рассмотренное на уроке. Измените в нём регулярное выражение так, чтобы оно проверяло строку на соответствие следующему правилу: строка начинается со знака «+», и за ним указано ровно 11 цифр (то есть напоминает номер мобильного телефона).



Критерии оценки
Приложение отображает одно окно, в котором есть поле ввода и цветная надпись. Надпись может быть в двух состояниях: зеленый текст «Ок»  и красный «Not Ok» (или любые две другие надписи, по которым можно понять, истина перед нами или ложь).

Если в поле ввода ввести номер мобильного телефона в формате +11111111111 ( знак «+» и любые 11 цифр), то цветная надпись должна показывать истину. Для других форматов строк должна быть надпись «Not Ok». 



Не забудьте экранировать знак «+» при помощи \

Чтобы указать допустимый набор символов, можно использовать интервалы вида [a–c] для букв a,b,c (для цифр аналогично). Чтобы указать количество символов, используйте запись {х}, где х — то самое количество. Для указания того, что строка должна начинаться на указанный символ, надо записать ^x , где х — символ.

