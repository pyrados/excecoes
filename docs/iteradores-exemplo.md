# Iteradores — Exemplo

```python
>>> class MeuIterador:
       a = 0       
       def __iter__(self): 
           return self
       def next(self):
           if self.a>10: raise StopIteration
           self.a += 1
           return self.a

>>> iter = MeuIterador()
>>> for i in iter:
        print(i, end=" ")

1 2 3 4 5 6 7 8 9 10 11
```
