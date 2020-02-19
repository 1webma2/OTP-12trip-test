# OTP-12trip-test
test for OTP bank

Тестовое задание:

https://boosters.pro/championship/onetwotrip_challenge/rating
Вот тут есть датасет
Задача:
1) проанализировать переменные
2) построить две/три альтернативные модели
3) проанализировать эти модели


Для решения использовался материал:
1. Курс аналитика данных Яндекс Практикума. (https://praktikum.yandex.ru/)

2. How to interpret almost perfect accuracy and AUC-ROC but zero f1-score, precision and recall (https://stackoverflow.com/questions/34698161/how-to-interpret-almost-perfect-accuracy-and-auc-roc-but-zero-f1-score-precisio)

3. Roc curve and cut off point. Python (https://stackoverflow.com/questions/28719067/roc-curve-and-cut-off-point-python)

4. ML bootcamp. Руководство для начинающих. (https://mlbootcamp.ru/article/tutorial/)


Вывод:
Все признаки в датасете числовые.
Классы сильно не сбалансированы. Соотношение примерно 44:1

Было построено 3 модели: Логистическая регрессия, случайный лес и градиентный бустинг.
Наилучшее значение roc_auc показал градиентный бустинг. Скор составил 0.68, для случайного леса 0.67, для логистической регрессии 0.66

Была совершена попытка нахождения наилучшего порога для улуччшения качества модели, но не получилось. 


