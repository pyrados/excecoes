# A cláusula else

- É possível completar um comando `try` com uma cláusula `else` que introduz um trecho de código que só é executado quando nenhuma exceção ocorre:

```python
   try:
      Código
   except Exceções:
      Código de tratamento da exceção
   else:
      Código executado se não ocorrem exceções
```

No contexto do bloco `try-except`, o comando `else` deve ser interpretado em português como se fosse **"e mais"**, como na expressão em inglês:

- _What else?_ (Tradução: "O que mais?")

