# Lib-Python-for-data-analytics
Домашки

Домашнее задание № 1

Задание 1
Для датафрейма log из материалов занятия создайте столбец source_type по правилам:

если источник traffic_source равен Yandex или Google, то в source_type ставится organic;
для источников paid и email из России ставим ad;
для источников paid и email не из России ставим other;
все остальные варианты берём из traffic_source без изменений.

Задание 2
В файле URLs.txt содержатся URL страниц новостного сайта. Вам нужно отфильтровать его по адресам страниц с текстами новостей. Известно, что шаблон страницы новостей имеет внутри URL конструкцию: /, затем 8 цифр, затем дефис. Выполните действия:

Прочитайте содержимое файла с датафрейм.
Отфильтруйте страницы с текстом новостей, используя метод str.contains и регулярное выражение в соответствие с заданным шаблоном.

Задание 3
Используйте файл с оценками фильмов ml-latest-small/ratings.csv. Посчитайте среднее время жизни пользователей, которые выставили более 100 оценок. Под временем жизни понимается разница между максимальным и минимальным значениями столбца timestamp для данного значения userId.

Задание 4
Дана статистика услуг перевозок клиентов компании по типам (см. файл “Python_13_join.ipynb” в разделе «Материалы для лекции “Продвинутый pandas”» ---- Ноутбуки к лекции «Продвинутый pandas»).
Нужно сформировать две таблицы:

таблицу с тремя типами выручки для каждого client_id без указания адреса клиента;
аналогичную таблицу по типам выручки с указанием адреса клиента.
Обратите внимание, что в процессе объединения таблиц данные не должны теряться.
