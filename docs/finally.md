# A cláusula finally

- A cláusula `finally` pode ser usada para se assegurar que
  mesmo que ocorra algum erro, uma determinada
  seqüência de comandos vai ser executada
     - Pode ser usada para restabelecer alguma variável para um
       valor padrão (_default_), por exemplo
- A cláusula `finally` e cláusulas `except` são mutuamente
  exclusivas
   - Exceções nesse caso não são tratadas
   - É possível combinar ambas usando comandos `try`
       aninhados, mas normalmente não há muito uso para isso


