# practicum_projects
*Yandex Practicum DS+ projects*

Репозиторий с проектами выполненными в процессе обучения на курсе Data Science Plus от Yandex.

## Аналитика
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Яндекс.Музыка](analytics/big_city_music) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница)| Jupyter Notebook, Python - *pandas* |
| [Исследование надёжности заёмщиков](analytics/credit_scoring) | Проведение исследования зависимости риска возникновения задолженности от различных факторов. | Jupyter Notebook, Python - *pandas, numpy, seaborn, pymorphy2, os, collections* |
| [Исследование объявлений о продаже квартир](analytics/real_estate) | В нашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, matplotlib* |
| [Исследование данных о российском кинопрокате](analytics/russian_cinema) | Заказчик исследования — Министерство культуры Российской Федерации. Изучим рынок российского кинопроката, уделим внимание фильмам, которые получили государственную поддержку. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, matplotlib* |

## Статистика
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Определение перспективного тарифа для телеком-компании](statystic/cell_phone_tariffs) | Проведём аналитику для компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, matplotlib, math, scipy* |

## Классическое машинное обучение
| Название проекта | Описание | Стек | 
| :--- | --- | :--- |
| [Рекомендация тарифов](machine_learning/tariff_prediction) | Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, sklearn* |
| [Отток клиентов](machine_learning/bank_customer_churn) | Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, sklearn* |
| [Выбор локации для скважины](machine_learning/oil_well_location) | Мы работаем в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, pandas_profiling, sklearn* |
| [Прогнозирование оттока клиентов в сети отелей «Как в гостях»](machine_learning/hotel_customer_churn) | Заказчик исследования — сеть отелей «Как в гостях». Чтобы привлечь клиентов, сеть отелей добавила на свой сайт возможность забронировать номер без предоплаты. Eсли клиент отменяет бронирование - компания терпит убытки. Нам нужно разработать систему, которая предсказывает отказ от брони. | Jupyter Notebook, Python - *pandas, numpy, seaborn, os, tqdm, matplotlib, pandas_profiling, statsmodels, sklearn* |
| [Предсказание стоимости жилья в Калифорнии](machine_learning/spark_house_pricing) | В проекте нам нужно обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году используя фреймворк Spark для распределённых вычислений. | Jupyter Notebook, Python - *pandas, numpy, pyspark* |
| [Защита персональных данных клиентов](machine_learning/personal_data_protection) | Нам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуем корректность его работы. | Jupyter Notebook, Python - *pandas, numpy, os, pandas_profiling, sklearn* |
| [Определение стоимости автомобилей](machine_learning/car_price_boosting) | Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. Нам нужно построить модель для определения стоимости. | Jupyter Notebook, Python - *pandas, numpy, os, seaborn, pandas_profiling, sklearn, lightgbm, catboost* |
| [Оценка риска ДТП](machine_learning/car_accident_risk) | Нужно создать систему для каршеринговой компании, которая могла бы оценить риск ДТП по совокупности факторов. Как только водитель забронировал автомобиль, сел за руль и выбрал маршрут, система должна оценить уровень риска. Если уровень риска высок, водитель увидит предупреждение и рекомендации по маршруту. | Jupyter Notebook, Python - *pandas, numpy, plotly, matplotlib, pandas_profiling, snap, sklearn, sqlalchemy, lightgbm, catboost* |
