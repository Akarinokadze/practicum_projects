# Определение перспективного тарифа для телеком-компании

## Описание исследования

Проведём аналитику для компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

## Цель исследования

Нам предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

## Исходные данные

В нашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год.

## Итоги исследования

В ходе данной работы мы подготовили исходные данные:

    привели к нужным типам;
    исправили ошибки.
    
Для каждого пользователя посчитали:

    количество сделанных звонков и израсходованных минут разговора по месяцам;
    количество отправленных сообщений по месяцам;
    объем израсходованного интернет-трафика по месяцам;
    помесячную выручку.

При анализе поведения клиентов оператора мы заметили:

    в целом, пользователи тарифа "smart" часто пользуются услугами сверх нормы по тарифу, и наоборот, клиенты тарифа "ultra" редко выходят за лимиты.
    Среднее количество звонков больше на тарифе `ultra`.
    Средний доход почти в два раза выше на тарифе `ultra`.
    Количество смс также существенно отличается, почти в 2 раза больше на тарифе `ultra`.
    Средний траффик отличается незначительно по тарифам.

Мы проверили две гипотезы.

Гипотеза о том что средняя выручка пользователей тарифов "Ультра" и "Смарт" различается подтвердилась. Так же это подтверждено средними значениями: 2049.75 и 1172.97 рублей в месяц соответственно.

Гипотеза о том что выручка пользователей из Москвы отличается от выручки пользователей из других регионов не подтвердилась. Средние значения вычисленные для Москвы: 1466.27, для других регионов: 1435.90 рублей в месяц.

**Таким образом, по полученной выборке, можно сделать вывод о том, что несмотря на то что пользователи тарифа "Смарт" намного чаще пользуются услугами сверх лимитов, тариф "Ультра" выгоднее для компании "Мегалайн", т.к. при вдвое меньшем количестве пользователей приносит почти такой же доход как и тариф "Смарт".**

## Используемый стек

Jupyter Notebook

Python - pandas, numpy, seaborn, os, matplotlib, math, scipy
