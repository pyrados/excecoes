# Geradores — Exemplo

```python
>>> def gerador():
       for i in range(10):
          print("i = ", i)
          yield i

>>> for j in gerador():
       print("j = ",j)

i =    0
j =    0
i =    1
j =    1
....
i =    9
j =    9

```