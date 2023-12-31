Цель: 

> **Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет**.

Задачи: 
1. Построить модели с предельно большим значением *F1*-меры.
2. Выбрать наилучшую модель.
3. Найти способы улучшить полученный результат.

Результаты: 
1. Перебрав модели **DT**, **LR**, **RF** выявили что наилучший результат демонстрирует модель **RF**. 
2. Обучить модель с **f1 = 0.6013071895424837**. Более того, нам удалось улучшить наш результат **достичь f1-меры не ниже 0.59** при помощи **upsampling**.
3. **AUC-ROC = 0.8453291504138961**, точность и плотность больше чем в половину выше чем у случайной модели.
