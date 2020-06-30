# Random-data

[![PyPi Package Version](https://img.shields.io/pypi/v/random_data.svg?style=flat-square)](https://pypi.python.org/pypi/random_data)
[![PyPi status](https://img.shields.io/pypi/status/random_data.svg?style=flat-square)](https://pypi.python.org/pypi/random_data)
[![Downloads](https://img.shields.io/pypi/dm/random_data.svg?style=flat-square)](https://pypi.python.org/pypi/random_data)
[![Supported python versions](https://img.shields.io/pypi/pyversions/random_data.svg?style=flat-square)](https://pypi.python.org/pypi/random_data)


## Установка и использование:
```sh 
pip install random-data
```

```python 
import random_data

print(random_data.russian.names.male()) # Получаем мужское имя
print(random_data.russian.surnames.male()) # Получаем мужскую фамилию

print(random_data.russian.names.female()) # Получаем женское имя
print(random_data.russian.surnames.male()) # Получаем женскую фамилию

print(random_data.etc.uuid()) # Генерируем uuid
print(random_data.etc.password()) # Пароль из букв и цифр. Можно указать нужную длину


```


# To do
- [X] Добавить больше русских мужских фамилий 30.06.20