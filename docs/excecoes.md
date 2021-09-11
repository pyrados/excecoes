# Exceções

- Quando um programa encontra dificuldades não
  previstas, diz­-se que uma condição excepcional ou uma
  *exceção* ocorreu
     - Um erro é uma exceção mas nem toda exceção é um erro

- Para poder representar tais eventos, Python define os
  chamados objetos de exceção (*exception objects*)

- Se a condição excepcional não é prevista (e tratada), o
  programa termina com uma mensagem de rastreamento:

```python
>>> 1/0
Traceback (most recent call last):
  File "<pyshell#0>", line 1, in -toplevel-
    1/0
ZeroDivisionError: integer division or modulo by
  zero
```



