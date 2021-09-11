# Captura de exceção — Exemplo 5

```python
>>> try:
       a =  int(input("Entre com um numero "))
       b =  int(input("Entre com outro numero "))
       print(a, "/", b, "=", a/b)
    except (ZeroDivisionError,TypeError) as e:
       print("Ooops, deu erro:",e)
    except Exception as e:
       print("Deu bode não previsto:",e)
       raise

Entre com um numero a
Entre com outro numero
Deu bode não previsto: EOF when reading a line

Traceback (most recent call last):
  File "<pyshell#52>", line 3, in -toplevel-
    b =  int(input("Entre com outro numero "))
EOFError: EOF when reading a line

```


