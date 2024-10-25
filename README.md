# Fundamentos de SQL

Este documento resume os conceitos fundamentais de SQL, incluindo operadores de agregação, joins, operadores lógicos, subconsultas, funções de agregação com GROUP BY, indexação, transações e procedimentos armazenados.

## 1. Operadores de Agregação

Os operadores de agregação em SQL permitem realizar cálculos em conjuntos de dados. Os principais operadores incluem:

- **SUM**: Calcula a soma total de uma coluna.
- **AVG**: Calcula a média dos valores de uma coluna.
- **COUNT**: Conta o número de registros em uma coluna (ou em um conjunto).
- **MIN**: Retorna o menor valor de uma coluna.
- **MAX**: Retorna o maior valor de uma coluna.

Estes operadores são frequentemente usados com a cláusula **GROUP BY** para agrupar resultados.

## 2. Joins em SQL

Os joins são utilizados para combinar registros de duas ou mais tabelas com base em uma condição relacionada. Os principais tipos de joins incluem:

- **INNER JOIN**: Retorna apenas os registros que têm correspondências em ambas as tabelas.
- **LEFT JOIN**: Retorna todos os registros da tabela da esquerda e as correspondências da tabela da direita (ou NULL se não houver correspondência).
- **RIGHT JOIN**: Retorna todos os registros da tabela da direita e as correspondências da tabela da esquerda (ou NULL se não houver correspondência).
- **FULL OUTER JOIN**: Retorna todos os registros quando há correspondência em uma das tabelas, incluindo NULLs onde não há correspondência.

## 3. Operadores Lógicos

Os operadores lógicos são utilizados para combinar condições em consultas SQL. Os principais incluem:

- **AND**: Retorna verdadeiro se ambas as condições forem verdadeiras.
- **OR**: Retorna verdadeiro se pelo menos uma das condições for verdadeira.
- **NOT**: Inverte o resultado de uma condição, retornando verdadeiro se a condição for falsa.

## 4. Subconsultas

Subconsultas são consultas aninhadas dentro de outra consulta. Elas podem ser utilizadas nas cláusulas:

- **SELECT**: Para retornar dados calculados a partir de outra consulta.
- **FROM**: Para usar o resultado de uma subconsulta como uma tabela.
- **WHERE**: Para filtrar dados com base em resultados de outra consulta.

## 5. Funções de Agregação com GROUP BY

A cláusula **GROUP BY** é utilizada em conjunto com funções de agregação para agrupar resultados com base em uma ou mais colunas. Isso é útil para calcular totais ou médias em grupos específicos de dados.

## 6. Indexação e Performance

**Indexação** é um mecanismo que melhora a velocidade das operações de busca em uma tabela. Um índice cria uma estrutura que permite acesso mais rápido a registros. No entanto, a indexação pode afetar a performance de operações de escrita, como:

- **INSERT**: Adicionar novos registros.
- **UPDATE**: Modificar registros existentes.
- **DELETE**: Remover registros.

## 7. Transações e Controle de Confiabilidade

**Transações** garantem que um conjunto de operações em um banco de dados seja executado de forma atômica. Isso significa que todas as operações devem ser concluídas com sucesso ou nenhuma delas deve ser aplicada. O controle de confiabilidade é alcançado através dos comandos:

- **COMMIT**: Confirma todas as operações realizadas na transação.
- **ROLLBACK**: Reverte todas as operações realizadas na transação em caso de erro.

## 8. Stored Procedures e Triggers

- **Stored Procedures**: Conjuntos de instruções SQL que podem ser armazenadas e executadas no banco de dados. Elas permitem encapsular lógica de negócio e podem ser chamadas quando necessário.
- **Triggers**: Procedimentos que são automaticamente executados em resposta a eventos específicos no banco de dados, como **INSERT**, **UPDATE** ou **DELETE**.
