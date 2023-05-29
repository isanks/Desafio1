Foi utlizado o programa Dbeaver e database utlizada foi SQlite. Realizada a criação das tabelas através do arquivos csv.

Para fazer o diagrama utilizei o site https://app.diagrams.net

Tive algumas complicações durante o desenvolvimento dos arquivos, onde na primeira questão acabei pegando os 10 no geral, ao invés de só pegar
da categoria "Bicicletas".

1 -  Na primeira parte selecionei as 3 tabelas e combinei os registros com base na ProductKey de cada tabela.
     Utilizei a coluna da tabela Sales2015,  que tem a ProductKey(geral).
     Armazenei a contagem, fiz a estimativa individualmente e usei o LIMIT 10 para limitar a apenas 10 resultados como solicitado na questão.

2 - Combinei as tabelas, agrupei, através do Prefix, FirstName, LastName para contagem individual e limitei a apenas 1 resultado.

3 - utilizei a função "substr" para pegar a partir do 4º número que representa o mês. usei funções para calcular o numero de vendas e ordenar os resultados.

4 - Contagem de cada territorio, filtrado através do HAVING para comparar com a media e mostrados em ordem decrescente.

