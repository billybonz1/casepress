CasePress - adaptive case managment system by WordPress
=========

[casepress.org](http://casepress.org/)

RU: Это глубокая альфа-версия и пробовать ее ставить без понимания алгоритмов пока бесполезно.

EN: This is a deep alpha version and try to put it without understanding the algorithms while useless

Рекомендуема тема https://github.com/casepress-studio/casepress-bootstrap


Лицензия [MIT](http://ru.wikipedia.org/wiki/%D0%9B%D0%B8%D1%86%D0%B5%D0%BD%D0%B7%D0%B8%D1%8F_MIT)


# Todo

## Р1. Орг.структура
1. Переименовать org_item в div
2. slug сделать structure


## Р2. ACF
1. Стилизовать ACF под alienship. Наработки можно взять от у https://github.com/fotonstep
2. Перетащить все секции на хук the_content

## Р3. Уведомления
1. Отладить уведомление о закрытии
2. Добавить уведомление об открытии дела на участников
3. Добавить уведомление о нарушении срока


## Р4. ACL
1. Интегрировать ACL


## Р5. Тема
1. Перетащить систему на Alienship
2. Изменить вывод постов на блог. С возможностью через хук добавлять различные поля в вывод.
3. Миниатюру сделать float:right
4. Отличать новые дела, от не новых. Через мету "list_readers" куда записывать ID пользователей, которые уже читали дело.
 

## Р6. Календарь
Интегрироваться с https://github.com/casepress-studio/calendar-wordpress-cp
