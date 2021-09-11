# O comando *raise*

- Para sinalizar a ocorrência de uma condição excepcional, pode-­se usar o comando `raise` que tem uma das formas:
     - raise *classe*
     - raise *classe (mensagem)*

- Onde classe é uma das classes de exceção definidas pelo Python
     - Para saber todos os tipos de exceção consulte o manual
     - Se quiser uma classe genérica use a classe Exception
     - Uma listagem pode ser obtida escrevendo
  
         ```python
         >>> import builtins
         >>> for nome in dir(builtins):
	               if nome.endswith('Error') or nome.endswith('Exception'):
		                  print(nome)
         ```



