# Защита персональных данных клиентов

## Описание исследования

Нам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуем корректность его работы.

Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.

## Исходные данные

Нам предоставленны 5000 строк с личной информацией и данными по страховым выплатам за 5 лет.

## Итоги исследования

Мы выбрали алгоритм скрытия персональных данных и обосновали его.

Применили наш алгоритм. Обучили модель линейной регрессии на необработанных данных и на скрытых.

Убедились что метрика R2 совпадает для обоих случаев.

## Используемый стек

Jupyter Notebook

Python - pandas, numpy, os, pandas_profiling, sklearn