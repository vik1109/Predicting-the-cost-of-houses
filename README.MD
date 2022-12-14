## Предсказание стоимости жилья

**Цель проекта:** В проекте необходимо обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. На основе данных нужно предсказать медианную стоимость дома в жилом массиве — median_house_value. Обучить модель и сделать предсказания на тестовой выборке. Для оценки качества модели использовать метрики RMSE, MAE и R2.

**Результат проекта**
Целью данного проекта была необходимость обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. В ходе работы инициализировали локальную Spark-сессию, провели предобработку данных, используя методы pySpark,исследовали данные на наличие пропусков и избавились от них, заменив пропущенные значения на среднее.

Преобразовали колонку с категориальными значениями техникой One hot encoding.

Провели стандартизацию количественных признаков.

Построили две модели линейной регрессии на разных наборах данных:

- используя все данные из файла;

- используя только числовые переменные, исключив категориальные. На основе данных из двух наборов предсказали медианную стоимость дома в жилом массиве — median_house_value. Для оценки качества модели использовали метрики RMSE, MAE и R2. 

  
Лучшей показала себя модель, обученная на всех признаках.

**Используемые инструменты** Pandas, pyspark, , numpy, Seaborn, Matplotlib, pandas_profiling, scipy, машинное обучение