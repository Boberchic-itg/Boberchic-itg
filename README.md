

Этот проект решает задачу преобразования категориальных данных в формат one-hot encoding без использования встроенных функций, таких как `pd.get_dummies`.

import pandas as pd


data = {
    'robot': ['0', '1', '0'],
    'human': [1, 0, 1],
    '': ['1' , '2' , '3']
}

df = pd.DataFrame(data)

print(df)

