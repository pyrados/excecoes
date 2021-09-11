# Criando uma Classe de Exceção

- Basta criar uma classe da forma habitual derivando­-a da classe `Exception`
- Não é preciso redefinir qualquer método
- Ex.:
    ```python
    >>> class MinhaExcecao(Exception): pass

    >>> raise MinhaExcecao("Deu bode!")

    Traceback (most recent call last):
      File "<pyshell#11>", line 1, in -toplevel-
        raise MinhaExcecao("Deu bode!")
    MinhaExcecao: Deu bode!
    ```



