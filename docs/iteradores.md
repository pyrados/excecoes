# Iteradores

- São maneiras genéricas de implementar iterações com
  classes
     - Permite o uso do comando `for`
     - É geralmente mais econômico do que usar uma lista pois
         não é preciso armazenar todos os valores, mas apenas
         computar um por vez
- Um iterador é uma classe que implementa o método
  mágico `__iter__`
     - É um método que, por sua vez, retorna um objeto que
       implementa um método chamado `next`

          - O método `next` deve retornar o “próximo” valor a ser iterado
          - Se não há próximo valor, `next` deve “levantar” a exceção `StopIteration`



