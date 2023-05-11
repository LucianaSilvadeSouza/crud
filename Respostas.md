1. No contexto da programação orientada a objetos, explique o que é uma "interface". Como o que aparece no código do artigo:

As classes ajudam a definir um objeto e seu comportamento e as interfaces que auxiliam na definição dessas classes. As interfaces são formadas pela declaração de um ou mais métodos, os quais obrigatoriamente não possuem corpo.

2. O que são "traits" no PHP?

Traits são pedaços individuais de código que definem métodos que podem ser utilizados por diferentes classes para proporcionar uma funcionalidade adicional.

3. No código aparece o método "bindValue" do PDO para definir o valor que será utilizado na execução da instrução SQL. No PDO, também existe o método "bindParam". Qual(is) a(s) diferença(s) entre eles?

A grande diferença entre esses métodos é que o bindParam() recebe o valor do parâmetro por referência, sendo este realmente setado no momento em que o método execute() do prepared statment for chamado, o que pode gerar problemas em alguns casos, mas também pode facilitar em outros, sendo assim dê preferência ao bindValue() para os casos básicos.

