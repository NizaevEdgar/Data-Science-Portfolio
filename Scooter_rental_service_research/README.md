# Исследование сервиса аренды самокатов GoFast

## Цель исследования:

1. Понять тратят ли пользователи с подпиской больше времени на поездки?
2. Можно ли сказать, что расстояние, которое проезжают пользователи с подпиской за одну поездку, меньше оптимальных 3130 метров?
3. Будет ли выручка от пользователей с подпиской выше, чем выручка от пользователей без подписки?
4. Снизилось ли количество обращений в техподдержку после обновления сервера?
5. Выяснить, какое минимальное количество промокодов нужно разослать, чтобы вероятность не выполнить план была примерно 5%.
6. Оценить вероятность того, что разосланные 1 млн push уведомлений откроют не более 399,5 тыс. пользователей.

## Вводные данные проекта

В основных данных есть информация о пользователях, их поездках и подписках.

## В данном исследовании были реализованы следующие этапы работ:

- Обзор данных.
- Предобработка данных.
- Описание и визуализация общей информации о пользователях и поездках.
- Объединение данных о пользователях, поездках и подписках в один датафрейм.
- Подсчёт выручки.
- Проверка гипотез из целей исследования.
- Написание общего вывода по полученным данным.

## Используемые библиотеки

- pandas
- matplotlib
- seaborn
- numpy
- scipy.stats
- math