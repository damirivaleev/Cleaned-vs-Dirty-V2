# Cleaned-vs-Dirty-V2

- Задача классифицировать чистые и грязные тарелки
- Обучающий набор состоит из 40 изображений тарелок, тестовый из 660
- Для увеличения обучающей выборки используется аугментация
- В качестве модели используется ResNet18 с оптимизатором Adam, функция потерь - бинарная кросс-энтропия
- Метрикой используется accuracy - доля правильных предсказаний положительного класса, дополнительно используется roc curve
- Строятся графики функции потерь и метрик на 100 эпохах
- На тестовой выборке получено качество в 87% правильных предсказаний
