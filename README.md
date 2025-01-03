# Методы, средства и технологии мультимедиа
Лабораторные работы по предмету "Методы, средства и технологии мультимедиа", 7 семестр, 806 кафедра, МАИ

**ФИО**: Устинов Денис Александрович 

**Группа**: М8О-406Б-21

**Датасет для задачи классификации**: Human Activity Recognition Dataset (HAR) (https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones)

**Датасет для задачи регрессии**: CO2 Emission by Vehicles (https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)

**Сравнительная таблица метрик обучения моделей из всех ЛР**:

| Алгоритм              | Задача          | Бейзлайн                                                                 | Улучшенный бейзлайн                                                   | Самостоятельная имплементация                                       | Улучшенная самостоятельная имплементация                            |
|------------------------|-----------------|-------------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|
| KNN               | Классификация  | Accuracy = 0.9002 <br> Recall = 0.9002 <br> Precision = 0.9039 <br> F1 Score = 0.8993 | Accuracy = 0.9134 <br> Recall = 0.9134 <br> Precision = 0.9171 <br> F1 Score = 0.9126 | Accuracy = 0.9002 <br> Recall = 0.9002 <br> Precision = 0.9002 <br> F1 Score = 0.8993 | Accuracy = 0.9141 <br> Recall = 0.9177 <br> Precision = 0.9141 <br> F1 Score = 0.9133 |
|                        | Регрессия      | MAE: 3.93 <br> MSE: 76.53                     | MAE: 2.24 <br> MSE: 34.31                   | MAE: 3.50 <br> MSE: 76.6                  | MAE: 2.32 <br> MSE: 32.90                   |
| Линейные модели    | Классификация  | Accuracy = 0.9586 <br> Recall = 0.9586 <br> Precision = 0.9597 <br> F1 Score = 0.9584 | Accuracy = 0.9619 <br> Recall = 0.9619 <br> Precision = 0.9632 <br> F1 Score = 0.9618 | Accuracy = 0.1890 <br> Recall = 0.1890 <br> Precision = 0.0759 <br> F1 Score = 0.1081 | Accuracy = 0.1957 <br> Recall = 0.1957 <br> Precision = 0.0828 <br> F1 Score = 0.1155 |
|                        | Регрессия      | MAE: 13.13 <br> MSE: 377.79                     | MAE: 7.29 <br> MSE: 139.02                   | MAE: 13.18 <br> MSE: 384.77                   | MAE: 7.99 <br> MSE: 189.17                   |
| Решающее дерево    | Классификация  | Accuracy = 0.8429 <br> Recall = 0.8429 <br> Precision = 0.8434 <br> F1 Score = 0.8415 | Accuracy = 0.8626 <br> Recall = 0.8626 <br> Precision = 0.8636 <br> F1 Score = 0.8620 | Accuracy = 0.8575 <br> Recall = 0.8575 <br> Precision = 0.7821 <br> F1 Score = 0.8082 | Accuracy = 0.9104 <br> Recall = 0.9104 <br> Precision = 0.9136 <br> F1 Score = 0.9102 |
|                        | Регрессия      | MAE: 2.80 <br> MSE: 107.49                     | MAE: 2.43 <br> MSE: 64.43                   | MAE: 7.05 <br> MSE: 251.37                   | MAE: 4.16 <br> MSE: 172.70                   |
| Случайный лес      | Классификация  | Accuracy = 0.9250 <br> Recall = 0.9250 <br> Precision = 0.9261 <br> F1 Score = 0.9248 | Accuracy = 0.9416 <br> Recall = 0.9416 <br> Precision = 0.9431 <br> F1 Score = 0.9411 | Accuracy = 0.9169 <br> Recall = 0.9169 <br> Precision = 0.9193 <br> F1 Score = 0.9166 | Accuracy = 0.9240 <br> Recall = 0.9240 <br> Precision = 0.9274 <br> F1 Score = 0.9232 |
|                        | Регрессия      | MAE: 3.00 <br> MSE: 69.60                     | MAE: 2.64 <br> MSE: 33.98                   | MAE: 7.30 <br> MSE: 238.79                   | MAE: 6.88 <br> MSE: 202.25                   |
| Градиентный бустинг| Классификация  | Accuracy = 0.9237 <br> Recall = 0.9237 <br> Precision = 0.9241 <br> F1 Score = 0.9237 | Accuracy = 0.9376 <br> Recall = 0.9376 <br> Precision = 0.9388 <br> F1 Score = 0.9374 | Accuracy = 0.8297 <br> Recall = 0.8297 <br> Precision = 0.8540 <br> F1 Score = 0.8271 | Accuracy = 0.9013 <br> Recall = 0.9013 <br> Precision = 0.9089 <br> F1 Score = 0.9007 |
|                        | Регрессия      | MAE: 5.13 <br> MSE: 94.89                     | MAE: 3.20 <br> MSE: 38.18                   | MAE: 8.26 <br> MSE: 163.69                   | MAE: 3.30 <br> MSE: 52.01                   |
