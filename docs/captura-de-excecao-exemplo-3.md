# Captura de exceção — Exemplo 3

```python
>>> try:
       a =  int(input("Entre com um numero "))
       b =  int(input("Entre com outro numero "))
       print(a, "/", b, "=", a/b)
    except (ZeroDivisionError,TypeError) as e:
       print("Ooops, deu erro:", e)

Entre com um numero 1
Entre com outro numero "z"
1 / z = Ooops, deu erro: unsupported operand
  type(s) for /: 'int' and 'str'

```


