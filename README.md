**Проект для Бюро Добрых Дел.**

**Данные.**

Данные, которыми располагает заказчик, включают в себя историю платежей жертвователей и 
какую-то дополнительную информацию за несколько лет по четырём тысячам жертвователей.
         
**Задача.**

Основная цель заказчика заключается в том, чтобы из пула тех клиентов, 
которые жертвовали за последний год, выявить клиентов, которые могут увеличить частоту или размер пожертвований.

**Используемые библиотеки.**

- *pandas*
- *numpy*
- *sklearn*
- *sklearn.tree*
- *lightgbm*
- *catboost*
- *matplotlib*
- *time*

**Выводы**

Провели исследовательский анализ данных, оформили данные в 4 класса, обучили модель на данных, самой лучшей моделью стала LGBMClassifier с 98% совпадений.
