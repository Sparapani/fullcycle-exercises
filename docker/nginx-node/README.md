Nesse desafio iremos colocar em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação Node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados Mysql, cadastrando um nome na tabela people

O retorno da aplicação Node.js para o nginx deverá ser: <h1>Full Cycle Rocks!</h1>
