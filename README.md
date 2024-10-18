# Fundamentos de SQL

Este documento resume os conceitos fundamentais de SQL, incluindo operadores de agregação, joins, operadores lógicos, subconsultas, funções de agregação com GROUP BY, indexação, transações e procedimentos armazenados.

## 1. Operadores de Agregação

Os operadores de agregação em SQL, como `SUM`, `AVG`, `COUNT`, `MIN` e `MAX`, permitem realizar cálculos em conjuntos de dados. Eles são frequentemente usados com a cláusula `GROUP BY` para agrupar resultados.

## 2. Joins em SQL

Os joins em SQL são usados para combinar registros de duas ou mais tabelas com base em uma condição relacionada. Os principais tipos de joins incluem:

- **INNER JOIN**: Retorna registros com correspondências em ambas as tabelas.
- **LEFT JOIN**: Retorna todos os registros da tabela da esquerda e correspondências da tabela da direita.
- **RIGHT JOIN**: Retorna todos os registros da tabela da direita e correspondências da tabela da esquerda.
- **FULL OUTER JOIN**: Retorna todos os registros quando há correspondência em uma das tabelas.

## 3. Operadores Lógicos

Os operadores lógicos, como `AND`, `OR` e `NOT`, são utilizados para combinar condições em consultas SQL. Eles permitem filtrar resultados de acordo com múltiplas condições.

## 4. Subconsultas

Subconsultas são consultas aninhadas dentro de outra consulta. Elas podem ser usadas nas cláusulas `SELECT`, `FROM` ou `WHERE`, permitindo a execução de consultas complexas e a filtragem de dados de forma mais eficaz.

## 5. Funções de Agregação com GROUP BY

A cláusula `GROUP BY` é utilizada em conjunto com funções de agregação para agrupar resultados com base em uma ou mais colunas. Isso é útil para calcular totais ou médias em grupos específicos de dados.

## 6. Indexação e Performance

Indexação é um mecanismo que melhora a velocidade das operações de busca em uma tabela. Um índice cria uma estrutura que permite acesso mais rápido a registros, mas pode afetar a performance de operações de escrita, como `INSERT`, `UPDATE` e `DELETE`.

## 7. Transações e Controle de Confiabilidade

Transações garantem que um conjunto de operações em um banco de dados seja executado de forma atômica, ou seja, todas as operações devem ser concluídas com sucesso ou nenhuma delas é aplicada. O controle de confiabilidade é alcançado através dos comandos `COMMIT` e `ROLLBACK`.

## 8. Stored Procedures e Triggers

Stored procedures são conjuntos de instruções SQL que podem ser armazenadas e executadas no banco de dados. Elas permitem encapsular lógica de negócio. Triggers são procedimentos que são automaticamente executados em resposta a eventos específicos no banco de dados, como `INSERT`, `UPDATE` ou `DELETE`.
