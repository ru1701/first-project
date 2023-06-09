# first-project
Отток клиентов

Описание проекта:
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Постройте модель с предельно большим значением *F1*-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно.

Дополнительно измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

Используемые модели: Случайный лес, Логистическая регрессия

Результат применения: 
Лучшей моделью для этого набора данных будет случайный лес, обученный на "увеличенной выборке".

Модель показала следующте результаты:
* Обучающая выборка:
        F1-мера = 0.865
        Площадь под ROC-кривой = 0.988
* Валидационная выборка:
        F1-мера = 0.595
        Площадь под ROC-кривой = 0.845
* Тестовая выборка:
        F1-мера = 0.619
        Площадь под ROC-кривой = 0.833
