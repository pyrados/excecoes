# Avisos

- Existem condições excepcionais menos sérias que não  provocam o levantamento de um objeto de exceção, mas apenas são exibidas sob a forma de um aviso
- Por exemplo:

```python
>>> import warnings
>>> print("POO.")
# Exibe uma mensagem de aviso
>>> warnings.warn('Mensagem de aviso: POO vicia.')
>>> print('Programação orientada a objetos.')

Warning (from warnings module):
  File "<pyshell#36>", line 1
UserWarning: Mensagem de aviso: POO vicia!
```

- Neste caso, o intepretador informa uma que POO vicia
- Com avisos, o programa não falha, mas o programador fica ciente que provamelmente deve reescrever a parte de seu código que provocou o aviso

## Categorias de Aviso

No Python, há uma variedade de exceções integradas que refletem categorias de aviso, algumas delas são:

- **Classe Warning:** é a superclasse de todas as classes da categoria de aviso e uma subclasse da classe Exceção.
- **Classe UserWarning:** categoria padrão da função warn ().
- **Classe DeprecationWarning:** categoria base para alertas sobre recursos obsoletos quando esses avisos são para outros desenvolvedores (acionado por código em __main__ a menos que seja ignorado).
- **Classe SyntaxWarning:** classe base para avisos de atributos sintáticos suspeitos.
- **Classe RuntimeWarning:** classe base para avisos de atributos de tempo de execução suspeitos.
- **Classe FutureWarning:** classe base para avisos sobre recursos obsoletos quando certos avisos são destinados a usuários finais de programas escritos em Python.
- **Classe PendingDeprecationWarning:** classe base para avisos de um atributo desatualizado.
- **Classe ImportWarning:** classe base para avisos causados ​​durante o processo de importação de um módulo.
- **Classe UnicodeWarning:** classe base para avisos baseados em Unicode.
- **Classe BytesWarning:** classe base para avisos baseados em bytes e bytearray.
- **Classe ResourceWarning:** classe base para avisos relacionados a recursos.


## Referências:

- [warnings — Controle de avisos &#8212; documentação Python 3.9.7](https://docs.python.org/pt-br/3/library/warnings.html)
- [Warnings in Python - GeeksforGeeks](https://www.geeksforgeeks.org/warnings-in-python/)
- [Python warnings Example](https://www.demo2s.com/python/python-warnings-example.html)
