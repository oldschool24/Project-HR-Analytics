# проект по методам ИИ в АД: Канаметов, Пузач, Байшев

## Этап 1

На первом этапе решается задача предсказания ухода сотрудников. Датасет: https://www.kaggle.com/vjchoudhary7/hr-analytics-case-study?select=general_data.csv

### Актуальность
Последствия ухода сотрудников:
1. нарушения дедлайнов проектов
2. дополнительные затраты на найм сотрудников
3. временное снижение эффективности

### Постановка задачи
Бинарная классификация, метрика f1_score.

### Применяемые методы
Метод опорных векторов, случайный лес, градиентный бустинг. 

### Навигация
В папке first stage вы можете найти: данные, юпитер тетрадку(Data and Notebook); полученные модели(Models) и презентацию 1 этапа.

## Этап 2
На втором этапе необходимо решить задачу классификации первого этапа и предсказать значения выбранного временного ряда. 

Датасет для классификации: https://www.kaggle.com/vjchoudhary7/hr-analytics-case-study?select=general_data.csv

Датасет для временных рядов: ---

### Применяемые методы

### Навигация
В папке second stage содержится: готовые данные с 1-го этапа, юпитер тетрадка, нейросетевая модель(classification); временной ряд, юпитер тетрадка(timeseries). 
