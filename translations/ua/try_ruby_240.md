---
lang:   UA
title:  Порожній словник
answer: ^(splendid|quite_good|mediocre|quite_not_good|abysmal)$
load:   books = {}
ok:     Yes that's a new review
error:  Use one of splendid, quite_good, mediocre, quite_not_good, abysmal.<br/>Don't forget the colon
---

Ми створили порожній __словник (hash)__. Словник – це як масив, тільки у кожного елемента є ім'я.

>Примітка перекладача: в україномовному співтоваристві слово hash перекладається як словник. Якщо Array перекладають як масив, то Hash – словник, інколи просто >хеш. Назва hash походить від hash-функції, на основі якої працює словник, і яка дозволяє дуже швидко знаходити елемент за ключем (ім'ям). Але щоб використовувати словники, нам це знати не обов'язково.

Ми збираємося записати кілька мініатюрних відгуків в наш новий словник. Ось наша рейтингова система:

- :splendid &rarr; витвір мистецтва
- :quite\_good &rarr; так, сподобалося
- :mediocre &rarr; посередньо
- :quite\_not\_good &rarr; загалом погано
- :abysmal &rarr; жах

Щоб оцінити книгу, додай назву в квадратних дужках і постав оцінку після знака дорівнює. Наприклад:

    books["Фарбований Лис"] = :splendid

> Зараз, я вважаю за необхідне сказати, що всі уроки в TryRuby відокремлені один від одного.
>Тож якщо ти вирішив пофестивалити і зробити дуже багато відгуків, то використовувати їх ти зможеш тільки в цьому уроці.
>Якщо ж хочеш використати свої відгуки і в наступному уроці, то ти повинен скопіювати їх і вставити.
>Не турбуйся про це, в кожному уроці є багато запрограмованих речей для тебе щоб гратися.