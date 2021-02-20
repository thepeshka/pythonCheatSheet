# Обработка ошибок

# Синтаксис
```python
try:
    <блок кода, в котором может произойти ошибка>
except <тип ошибки> as <переменная для хранения ошибки>:
    <блок кода, который выполняется, если ошибка произошла>
```

# Пример
```python
try:
    raise ZeroDivisionError('infinity')
except ZeroDivisionError as e:
    print(e)
```