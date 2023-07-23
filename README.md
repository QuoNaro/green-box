# Green Box 
#### Простой модуль для получения информации из Google Таблиц.

## Установка
**GitHub**
```
pip install git+https://github.com/QuoNaro/green-box.git
```
**PyPi**
```
pip install green-box
```

## **Использование**
Из всей ссылки берется только ID!
>https://docs.google.com/spreadsheets/d/***1O174ca048KT5YMYkDADzQvzIJEWUMADj_0ciLAQOt34***


```python
from green_box import Table

table = Table('1O174ca048KT5YMYkDADzQvzIJEWUMADj_0ciLAQOt34','Лист1').rows

```
```
['Фамилия', 'Имя', 'Отчество', 'Адрес']
['Сидорова', 'Елена', 'Евгеньевна', 'пр. Победы, 10']
['Петров', 'Иван', 'Александрович', 'ул. Солнечная, 5']
['Васильева', 'Ирина', 'Александровна', 'ул. Парковая, 3']
['Суворова', 'Елена', 'Ивановна', 'ул. Центральная, 1']
['Смирнова', 'Екатерина', 'Дмитриевна', 'ул. Солнечная, 5']
['Смирнов', 'Петр', 'Алексеевич', 'пр. Ленина, 20']
['Петров', 'Петр', 'Петрович', 'пр. Ленина, 20']
['Васильева', 'Мария', 'Артемьева', 'ул. Парковая, 3']
['Сидорова', 'Анна', 'Евгеньевна', 'пр. Победы, 10']
```
## Зависимости
- [openpyxl](https://github.com/shshe/openpyxl)
- [numpy](https://github.com/numpy/numpy)
- [requests](https://github.com/psf/requests)