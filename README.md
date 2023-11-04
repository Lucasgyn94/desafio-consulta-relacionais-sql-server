# desafio-consulta-relacionais-sql-server
Resolução do desafio sobre consultas relacionais no SQL Server lançada pelo Professor durante as aulas ministradas pela DIO.

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de banco de dados, da trilha .NET da DIO.

## Contexto
Você é responsável pelo banco de dados de um site de filmes, onde são armazenados dados sobre os filmes e seus atores. Sendo assim, foi solicitado para que você realize uma consulta no banco de dados com o objetivo de trazer alguns dados para análises.

## Proposta
Você precisará realizar 12 consultas ao banco de dados, cada uma retornando um tipo de informação. O seu banco de dados está modelado da seguinte maneira:

![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/065d11c0-cfbf-4fef-b5de-ec98a7545b75)


## As tabelas sao descritas conforme a seguir:

* Filmes

Tabela responsável por armazenar informações dos filmes.

* Atores

Tabela responsável por armazenar informações dos atores.

* Generos

Tabela responsável por armazenar os gêneros dos filmes.

* ElencoFilme

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e atores, ou seja, um ator pode trabalhar em muitos filmes, e filmes podem ter muitos atores.

* FilmesGenero

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e gêneros, ou seja, um filme pode ter mais de um gênero, e um genêro pode fazer parte de muitos filmes.

## Objetivo
Você deverá criar diversas consultas, com o objetivo de retornar os dados a seguir. Abaixo de cada pedido tem o retorno esperado. O seu retorno deve ser igual ao da imagem.

1 - Buscar o nome e ano dos filmes
[Exercicio 1](https://github.com/digitalinnovationone/trilha-net-banco-de-dados-desafio/blob/main/Imagens/1.png)

2 - Buscar o nome e ano dos filmes, ordenados por ordem crescente pelo ano
[Exercicio 2](https://github.com/digitalinnovationone/trilha-net-banco-de-dados-desafio/blob/main/Imagens/2.png)

3 - Buscar pelo filme de volta para o futuro, trazendo o nome, ano e a duração
[Exercicio 3](https://github.com/digitalinnovationone/trilha-net-banco-de-dados-desafio/blob/main/Imagens/3.png)

4 - Buscar os filmes lançados em 1997
[Exercicio 4](https://github.com/digitalinnovationone/trilha-net-banco-de-dados-desafio/blob/main/Imagens/4.png)

5 - Buscar os filmes lançados APÓS o ano 2000
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/9cbf840a-587d-4b7a-9cc4-7ae60040d668)

6 - Buscar os filmes com a duracao maior que 100 e menor que 150, ordenando pela duracao em ordem crescente
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/4a722aea-4f39-4790-84a9-ea4768f0a5af)

7 - Buscar a quantidade de filmes lançadas no ano, agrupando por ano, ordenando pela duracao em ordem decrescente
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/c200c3c9-10d7-41a5-a385-a10d5b2e5219)


8 - Buscar os Atores do gênero masculino, retornando o PrimeiroNome, UltimoNome
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/2e907bac-0f4e-4c32-bc7b-24ae680bea82)


9 - Buscar os Atores do gênero feminino, retornando o PrimeiroNome, UltimoNome, e ordenando pelo PrimeiroNome
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/a4727c6c-e20d-40a0-bc31-9dcece04d39b)


10 - Buscar o nome do filme e o gênero
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/1096e572-79a7-4950-ad19-f8f205f251eb)


11 - Buscar o nome do filme e o gênero do tipo "Mistério"
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/a1ce64c4-a6c3-4402-9fc0-cbc9d147b37a)


12 - Buscar o nome do filme e os atores, trazendo o PrimeiroNome, UltimoNome e seu Papel
![image](https://github.com/Lucasgyn94/desafio-consulta-relacionais-sql-server/assets/91031320/2ce7b8e0-b586-4afd-9036-9b5d4db76440)
