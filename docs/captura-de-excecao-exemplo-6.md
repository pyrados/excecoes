# Captura de exceção — Exemplo 6

```python
>>> while True:
     try:
        a =  int(input("Entre com um numero "))
        b =  int(input("Entre com outro numero "))
        print(a, "/", b, "=", a/b)
     except Exception as e:
        print("Deu bode:", e)
        print("Tente novamente")
     else:
        break

Entre com um numero 1
Entre com outro numero xxx
Deu bode: name 'xxx' is not defined
Tente novamente
Entre com um numero 1
Entre com outro numero 2
1 / 2 = 0

```
