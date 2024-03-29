# Оценка параметра в статистических моделях

Этот проект представляет собой реализацию эксперимента по оценке параметра в различных статистических моделях с использованием различных методов оценки.

## Как это работает

1. **Генерация данных**: Используются четыре модели для генерации данных с различными типами шума.
2. **Оценка параметра**: Для каждой модели и размера выборки проводится серия экспериментов, в результате которых вычисляются оценки параметра с использованием четырех различных методов: выборочное среднее, полусумма максимума и минимума, выборочная медиана и среднее арифметическое с отбросом крайних значений.
3. **Вычисление ошибок**: Для каждой модели, размера выборки и метода оценки вычисляется средняя относительная ошибка.
4. **Визуализация результатов**: Полученные оценки параметра визуализируются на графиках, где по оси X отображается размер выборки, а по оси Y - значения оценок параметра.

