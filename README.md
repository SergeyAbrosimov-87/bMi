В этой задаче мы считаем, что пользователь вводит корректные значения входных данных.

# Мы решили написать сервис, который рассчитывает индекс массы тела (body mass index).

Формулу расчёта bmi-индекса предстоит найти самостоятельно. Сервисный метод должен возвращать целое число. Чтобы дробное превратить в целое, можете использовать приведение типов: (int) index, где index имеет дробный тип.

_Пример для самопроверки: для роста 1.87 метра и веса 98 кг он будет 28._

## Создать класс BmiService с методом calculate:
- который принимает все нужные данные в параметрах;
- в названии параметров указаны единицы измерения, например, в метрах принимаем рост;
- метод возвращает посчитанный bmi-индекс в виде целого числа.

## Продемонстрировать в Main по аналогии с первой задачей:
- создание объекта;
- вызов метода calculate;
- печать в консоль результата, проверьте, что ваша программа считает правильно, сравнив его со своими примерами.