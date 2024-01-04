# Защита персональных данных клиентов

## Цель исследования

Защитить данные клиентов страховой компании. 

## Задача исследования

Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию и обосновать корректность работы данного метода.

Необходимо защитить данные таким образом, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.


**Признаки:** пол, возраст и зарплата застрахованного лица, количество членов его семьи.

**Целевой признак:** количество страховых выплат клиенту за последние 5 лет.

## В данном исследовании были реализованы следующие этапы работ:

1. Загрузили и провели предподготовку данных.
2. Признаки умножили на обратимую матрицу. Ответили на вопрос: изменится ли качество Линейной регрессии?
3. Предложили алгоритм преобразования данных для решения задачи.
4. Проверили, что качество Линейной регрессии не отличается до и после преобразования.
6. Написалим общие выводы.

## Используемые библиотеки

- pandas
- numpy
- matplotlib
- sklearn