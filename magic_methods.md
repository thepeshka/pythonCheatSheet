# Магические методы классов

Название операции | Пример использования в операторе | Описание
--- | --- | ---
`__init__` | `Class()` | Конструктор класса
`__call__` | `obj()` | Вызов объекта
`__add__` | `obj + x` | Прибавление к объекту
`__sub__` | `obj - x` | Вычитание из объекта
`__mul__` | `obj * x` | Умножение объекта
`__truediv__` | `obj / x` | Деление объекта
`__floordiv__` | `obj // x` | Деление объекта без остатка
`__mod__` | `obj % x` | Остаток от деления объекта
`__pow__` | `obj ** x` | Возведение объекта в степень
`__getitem__` | `obj[x]` | Получение индекса, ключа или среза объекта
`__int__` | `int(obj)` | Преобразование объекта в число
`__bool__` | `bool(obj)` | Преобразование объекта в булево значение
`__str__` | `str(obj)` | Преобразование объекта в строку
`__eq__` | `obj == x` | Проверка равен ли объект другому значению
`__gt__` | `obj > x` | Проверка больше ли объект другого значения
`__lt__` | `obj < x` | Проверка меньше ли объект другого значения
`__le__` | `obj <= x` | Проверка больше или равен ли объект другому значению
`__ge__` | `obj >= x` | Проверка меньше или равен ли объект другому значению