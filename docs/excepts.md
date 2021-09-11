# Mais except

- É possível tratar diferentemente as diversas exceções
  usando duas ou mais cláusulas `except`
- Se quisermos nos prevenir contra qualquer tipo de erro,
  podemos usar uma cláusula `except` sem nome de classe
     - Outra opção é usar a classe `Exception`, que é base para
       todas as exceções e portanto casa com qualquer exceção
- Se não quisermos tratar um erro em uma cláusula
  `except`, podemos passá­-la adiante usando o [comando `raise`](raise.md)
   - Nesse caso, podemos usar um [raise](raise) sem argumentos ou
       passar explicitamente um [objeto de exceção](objetos-de-excecao.md)



