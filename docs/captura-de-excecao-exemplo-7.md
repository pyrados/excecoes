# Captura de exceção — Exemplo 7

```python
>>> try:
     try:
        x =  int(input("Entre com um número: "))
     finally:
        print("Restabelecendo um valor para x")
        x = None
   except:
       print("Deu bode")

Entre com um número: 2xx
Restabelecendo um valor para x
Deu bode
```
