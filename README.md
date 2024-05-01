# Python_Task_9_Attestation_Pandas

## ЗАДАНИЕ 

В ячейке представлен код, генерирующий DataFrame, который состоит всего из 1 столбца:

import random

lst = ['robot'] * 10

lst += ['human'] * 10

random.shuffle(lst)

data = pd.DataFrame({'whoAmI'lst})

data.head() 


Задача состоит в том, чтобы перевести его в one hot вид. 

Не предполагается использование get_dummies.

---
