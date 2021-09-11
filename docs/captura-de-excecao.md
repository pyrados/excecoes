# Capturando Exceções

- Para capturar uma exceção possivelmente levantada por um trecho de
  código, pode­-se usar a construção `try/except`:
    ```python
    try:
        Código
    except Exceções:
        Código de tratamento da exceção
    ```

- Sendo que Exceções pode ser:
    - Classe
    - Classe as var
    - (Classe1,...,ClasseN)
    - (Classe1,...,ClasseN) as var

- Onde:
    - `Classe`, `Classe1` e `ClasseN` são nomes de [classes de exceção](classes-de-excecao.md)
    - `var` é uma variável à qual é atribuída um [objeto de exceção](objetos-de-excecao.md)

## Referências

- [Instruções compostas — the try statement — documentação Python](https://docs.python.org/pt-br/3/reference/compound_stmts.html?highlight=try#the-try-statement)



