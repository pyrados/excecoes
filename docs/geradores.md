# Geradores

- Geradores são funções especiais que retornam iteradores
- Em resumo, uma função geradora é uma que contém o
  comando `yield valor`
- Uma função geradora normalmente é chamada para obter
  o iterador para um comando `for`
     - O comando `for` automaticamente iterará sobre todos os
       valores que `yield` “retorna”
     - Observe que o iterador produzido pela função geradora é
       tal que o código que gera os valores e o código dentro do `for`
       se sucedem alternadamente
- Geradores são especialmente úteis em códigos recursivos


