# Исследование сервиса аренды самокатов GoFast
***Цель исследования:***
1. Описать и визуализировать общую информацию о пользователях и поездках.
2. Визуализировать информацию о расстоянии и времени поездок для пользователей каждой из категорий пользователей (с подпиской и без).
3. Подсчитать выручку.
4. Проверить гипотезы: 4.1 Тратят ли пользователи с подпиской больше времени на поездки? 4.2 Можно ли сказать, что расстояние, которое проезжают пользователи с подпиской за одну поездку, не превышает оптимальное с точки зрения износа самоката? 4.3 Будет ли помесячная выручка от пользователей с подпиской по месяцам выше, чем выручка от пользователей без подписки?
5. Выяснить, какое минимальное количество промокодов нужно разослать в ходе маркетинговой акции, чтобы вероятность не выполнить план была примерно 5% (план 10% на основании предыдущей акции)
***Ход исследования:***
Данные о пользователях сервиса я получу из нескольких файлов: '/datasets/users_go.csv', '/datasets/rides_go.csv', '/datasets/subscriptions_go.csv'. О качестве данных ничего не известно, поэтому прежде чем приступать к анализу, понадобится обзор данных.

Я проверю данные на ошибки, дубликаты, оценю влияние пропусков на ход исследования, преобразую необходимые столбцы в нужный тип. Далее поведу необходимы объединения таблиц и приступлю к исследованию данных.

***Таким образом мое исследование пройдет в несколько этапов:***

- Обзор данных.
- Предобработка данных.
- Исследовательский анализ данных.
- Объединение данных.
- Подсчет выручки.
- Проверка гипотез.
- Исследования для проведения маркетинговой акции.