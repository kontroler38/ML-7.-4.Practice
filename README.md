# Практическая работа к ML-7. Оптимизация гиперпараметров модели
## Подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации для моделей "Логистическая регрессия" и "Случайный лес" на примере задачи "ПРОГНОЗИРОВАНИЕ БИОЛОГИЧЕСКОГО ОТВЕТА (HW-3)"

## Оглавление
[1. Описание проекта](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Описание-проекта)

[2. Какой кейс решаем?](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Какой-кейс-решаем?)

[3. Краткая информация о данных](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Этапы-работы-над-проектом)

[5. Результат](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Результат)

### Описание проекта


:arrow_up: [к оглавлению](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Оглавление)

### Какой кейс решаем?
Необходимо обучить две модели: логистическую регрессию и случайный лес. Далее нужно сделать подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации. Важно использовать все четыре метода (GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna) хотя бы по разу, максимальное количество итераций не должно превышать 50.

:arrow_up: [к оглавлению](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Оглавление)

**Метрика качества**
В качестве метрики будем использовать F1-score.

:arrow_up: [к оглавлению](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Оглавление)

**Что практикуем**
Главная задача — добиться максимальной точности модели

:arrow_up: [к оглавлению](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Оглавление)

**Краткая информация о данных**
Практика основана на соревновании Kaggle: [Predicting a Biological Response](https://www.kaggle.com/c/bioresponse) (Прогнозирование биологического ответа)
Данные представлены в формате CSV.  Каждая строка представляет молекулу.
- Первый столбец Activity содержит экспериментальные данные, описывающие фактический биологический ответ [0, 1]; 
- Остальные столбцы D1-D1776 представляют собой молекулярные дескрипторы — это вычисляемые свойства, которые могут фиксировать некоторые характеристики молекулы, например размер, форму или состав элементов.

Ссылка на страницу с данными в виде csv: (https://lms.skillfactory.ru/assets/courseware/v1/9f2add5bca59f8c4df927432d605fff3/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/_train_sem09__1_.zip)

:arrow_up: [к оглавлению](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Оглавление)

### Этапы работы над проектом
- Обучение модели Логистическая регрессия, 
- Обучение модели Случайный лес,
- Подбор гиперпараметров с помощью базовых методов оптимизации.
- Подбор гиперпараметров с помощью продвинутых методов оптимизации.

:arrow_up: [к оглавлению](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Оглавление)

### Результат
Jupyter Notebook с выполненными заданиями и выводами: (https://github.com/kontroler38/ML-7.-4.Practice/blob/main/DSPR-93%20ФедоровАВ%20ML-7.%20Практика.%20прогнозирование%20биологического%20ответа%20(HW-3).ipynb)

:arrow_up: [к оглавлению](https://github.com/kontroler38/ML-7.-4.Practice/blob/main/README.md#Оглавление)
