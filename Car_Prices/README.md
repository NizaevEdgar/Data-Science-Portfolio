# Проект по построению модели определения стоимости автомобилей

Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля.

## Цель исследования

Необходимо построить модель для определения стоимости.  

В модели важными критериями являются:

- качество предсказания (*RMSE* ниже 2500);
- скорость предсказания;
- время обучения.

В нашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей.

## В данном исследовании были реализованы следующие этапы работ:

1. Загрузили и провели предподготовку данных.
2. Подготовили выборки для обучения моделей.
3. Обучили разные модели. Для каждой модели подобрали гиперпараметры.
4. Проанализировали время обучения, время предсказания и качество моделей.
5. Опираясь на критерии, выбрали лучшую модель, проверили её качество на тестовой выборке.
6. Написали общие выводы.

## Используемые библиотеки

- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- catboost
- lightgbm
- datetime
- warnings
- time