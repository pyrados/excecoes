# Captura de exceção — Exemplo 1


```python
>>> try:
       a =  int(input("Entre com um numero: "))
       b =  int(input("Entre com outro numero: "))
       print(a, "/", b, "=", a/b)
    except ZeroDivisionError:
       print("Ooops, segundo numero não pode ser zero!")


Entre com um numero 1
Entre com outro numero 0
1 / 0 = Ooops, segundo numero não pode ser zero!

```


