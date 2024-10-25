# Guia de Banco de Dados

Este projeto aborda conceitos fundamentais de banco de dados, com foco em SQL, incluindo operadores de agregação, joins, operadores lógicos, subconsultas, funções de agregação, indexação, transações, stored procedures e triggers.

## Índice

- [Operadores de Agregação](#operadores-de-agregação)
  - [SUM, AVG, COUNT](#sum-avg-count)
  - [MIN e MAX](#min-e-max)
- [Joins em SQL](#joins-em-sql)
  - [INNER JOIN](#inner-join)
  - [LEFT JOIN e RIGHT JOIN](#left-join-e-right-join)
  - [FULL OUTER JOIN](#full-outer-join)
- [Operadores Lógicos](#operadores-lógicos)
  - [AND, OR, NOT](#and-or-not)
  - [Combinação de Operadores](#combinação-de-operadores)
- [Subconsultas](#subconsultas)
  - [Definição e Usos Práticos](#definição-e-usos-práticos)
  - [Subconsultas Correlacionadas](#subconsultas-correlacionadas)
- [Funções de Agregação com GROUP BY](#funções-de-agregação-com-group-by)
  - [Agrupamento de Resultados](#agrupamento-de-resultados)
  - [Combinação com HAVING](#combinação-com-having)
- [Indexação e Performance](#indexação-e-performance)
  - [Impacto da Indexação](#impacto-da-indexação)
  - [Quando Usar Índices](#quando-usar-índices)
- [Transações e Controle de Confiabilidade](#transações-e-controle-de-confiabilidade)
  - [Importância das Transações](#importância-das-transações)
  - [Cenários Práticos](#cenários-práticos)
- [Stored Procedures e Triggers](#stored-procedures-e-triggers)
  - [Definição e Utilização](#definição-e-utilização)
  - [Exemplos Práticos](#exemplos-práticos)

## Operadores de Agregação

### SUM, AVG, COUNT
Como calcular totais e médias em consultas SQL utilizando as funções `SUM()`, `AVG()` e `COUNT()`.

### MIN e MAX
Identificação de valores extremos em conjuntos de dados com as funções `MIN()` e `MAX()`.

## Joins em SQL

### INNER JOIN
Combinação de registros de duas tabelas usando `INNER JOIN`.

### LEFT JOIN e RIGHT JOIN
Inclusão de todos os registros de uma tabela, com correspondência da outra usando `LEFT JOIN` e `RIGHT JOIN`.

### FULL OUTER JOIN
Combinação de registros de ambas as tabelas, mesmo sem correspondência, usando `FULL OUTER JOIN`.

## Operadores Lógicos

### AND, OR, NOT
Uso de operadores lógicos para combinar condições em consultas SQL.

### Combinação de Operadores
Estruturação de consultas complexas com múltiplas condições.

## Subconsultas

### Definição e Usos Práticos
Como e quando utilizar subconsultas para resolver problemas específicos.

### Subconsultas Correlacionadas
Exemplos de subconsultas que dependem da consulta externa.

## Funções de Agregação com GROUP BY

### Agrupamento de Resultados
Uso do `GROUP BY` para categorizar dados e agregar resultados.

### Combinação com HAVING
Filtragem de resultados agregados utilizando a cláusula `HAVING`.

## Indexação e Performance

### Impacto da Indexação
Como índices melhoram a performance das consultas em bancos de dados.

### Quando Usar Índices
Cenários práticos para otimização e quando implementar índices.

## Transações e Controle de Confiabilidade

### Importância das Transações
Conceitos de `COMMIT` e `ROLLBACK` em transações de banco de dados.

### Cenários Práticos
Exemplos de sistemas onde o controle de transações é crucial.

## Stored Procedures e Triggers

### Definição e Utilização
O que são stored procedures e triggers, e como podem automatizar processos.

### Exemplos Práticos
Aplicações de stored procedures e triggers no dia a dia.

## Conclusão

Este guia fornece uma visão geral dos principais conceitos de banco de dados e SQL. Para mais informações ou para contribuir, sinta-se à vontade para abrir uma issue ou pull request.

