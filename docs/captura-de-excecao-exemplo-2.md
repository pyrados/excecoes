# Captura de exceção — Exemplo 2

```python
>>> try:
       a =  int(input("Entre com um numero "))
       b =  int(input("Entre com outro numero "))
       print(a, "/", b, "=", a/b)
    except (ZeroDivisionError,TypeError):
       print("Ooops, tente novamente!")

Entre com um numero 1
Entre com outro numero "a"
1 / a = Ooops, tente novamente!

```


