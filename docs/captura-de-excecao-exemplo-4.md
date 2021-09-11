# Captura de exceção — Exemplo 4

```python
>>> try:
        a =  int(input("Entre com um numero "))
        b =  int(input("Entre com outro numero "))
        print(a, "/", b, "=", a/b)
    except ZeroDivisionError:
        print("Ooops, divisão por zero")
    except TypeError:
        print("Ooops, você não deu um número")
    except:
        print("Deu um bode qualquer")


Entre com um numero 2
Entre com outro numero fads2312
Deu um bode qualquer
```


