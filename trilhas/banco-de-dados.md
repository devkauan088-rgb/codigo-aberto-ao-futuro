---
layout: default
title: Banco de Dados
---

# 5. Banco de Dados

## Objetivo

Compreender como informações são organizadas, armazenadas, consultadas e atualizadas em sistemas. A trilha começa pelos conceitos de bancos de dados relacionais e SQL, e apresenta tópicos que podem ser aprofundados posteriormente.

## Pré-requisitos

- Recomenda-se ter concluído [Lógica de Programação](logica-programacao.md).
- É útil conhecer os conceitos de variáveis, tipos de dados e estruturas de informação.
- Não é necessário ter experiência anterior com bancos de dados.

## Conteúdo programático

### 5.1 Conceitos iniciais
- O que é um banco de dados.
- Diferença entre banco de dados e sistema gerenciador de banco de dados (SGBD).
- Dados estruturados e não estruturados: visão geral.
- Bancos relacionais e não relacionais: introdução.

### 5.2 Modelagem de dados
- Entidades, atributos e relacionamentos.
- Tabelas, linhas e colunas.
- Chaves primárias e estrangeiras.
- Relacionamentos um para um, um para muitos e muitos para muitos.
- Noções de diagramas entidade-relacionamento.

### 5.3 SQL — linguagem de consulta
- `SELECT` e `FROM`.
- Filtros com `WHERE`.
- Ordenação com `ORDER BY`.
- Inserção com `INSERT`.
- Atualização com `UPDATE`.
- Remoção com `DELETE`.
- Junções com `JOIN`.
- Funções de agregação e agrupamento.

### 5.4 Estrutura e integridade
- Criação e alteração de tabelas.
- Tipos de dados.
- Restrições e integridade referencial.
- Normalização: noções iniciais.
- Índices: finalidade e conceitos.

### 5.5 Administração e segurança: introdução
- Usuários e permissões.
- Backup e recuperação.
- Transações.
- Noções de desempenho.
- Riscos de consultas inseguras e injeção de SQL.

### 5.6 Outros modelos
- NoSQL: visão geral.
- Documentos, chave-valor e outros modelos.
- Quando avaliar alternativas ao modelo relacional.

## Materiais recomendados

| Recurso | Descrição | Acesso |
|---|---|---|
| [SQLBolt](https://sqlbolt.com/) | Lições interativas para aprender SQL, desde consultas básicas até junções e alterações de dados. | Gratuito; conteúdo em inglês. |
| [Tutorial do PostgreSQL](https://www.postgresql.org/docs/current/tutorial.html) | Tutorial oficial que apresenta conceitos relacionais e comandos SQL utilizando PostgreSQL. | Gratuito; documentação em inglês. |
| [Harvard CS50x](https://cs50.harvard.edu/x/) | Inclui uma introdução a SQL, tabelas, consultas, índices e transações. | Conteúdo disponível gratuitamente; certificado pode ter condições próprias. |

## Atividades práticas

- Desenhe um modelo de dados para uma biblioteca, escola ou pequeno comércio.
- Identifique entidades, atributos e relacionamentos.
- Crie tabelas com chaves primárias e estrangeiras.
- Insira registros e faça consultas com filtros e ordenação.
- Relacione duas ou mais tabelas utilizando `JOIN`.

## Projeto sugerido

**Banco de dados de uma biblioteca:** modele livros, autores, usuários e empréstimos. Crie tabelas relacionadas e escreva consultas para listar livros disponíveis, empréstimos em andamento e histórico de empréstimos.

## Resultado esperado

Ao concluir esta trilha, você deverá compreender a finalidade de um banco de dados relacional, modelar estruturas simples e executar operações básicas com SQL.

## Próximas etapas

Aprofunde-se em modelagem, transações, otimização e administração de bancos de dados. Você também poderá estudar a integração entre bancos de dados e aplicações web.
