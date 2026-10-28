# Versão 0.8.1 — aprender pela leitura no celular

Entrega de 22/10/2026; documentação pública atualizada em 27/10/2026.

## Problema e decisão

O usuário queria compreender os exemplos pelo celular. Controles para copiar, exportar e compartilhar os códigos acrescentavam ações que não faziam parte dessa experiência. A revisão remove esses controles de todas as fichas e mantém o código visível.

Os exemplos SQL passam a reunir a pergunta, os dados usados, o código, a resposta e a explicação dos passos. Tabelas de entrada e de resultado evitam depender da execução externa para acompanhar o exemplo.

## Conteúdo

- Acervo de 477 fichas, 35 categorias e 966 exemplos.
- 52 fichas com 87 exemplos SQL organizados para leitura.
- Reescrita de 15 resumos e revisão de cuidados específicos de cada assunto.
- Complementos de NULLIF, EXISTS, NOT LIKE e LEAD; demonstrações de índices simples/compostos, EXPLAIN, EXPLAIN ANALYZE e diferenças entre DELETE, TRUNCATE e DROP.
- Banco de cada exemplo identificado para distinguir PostgreSQL, SQL Server e Oracle.
- Fases, identificadores e ilustrações anteriores preservados.

O e-book **SQL na Prática**, de Caroline de Souza Cunha Lopes, fornecido pelo usuário, serviu de apoio para a organização e os conceitos. Foram mapeados 47 assuntos. Os dados, resultados e explicações do app são próprios; o material de referência permanece reservado.

## Continuidade da 0.8.0

A entrega 0.8.0 acrescentou 22 fichas e 22 ilustrações SQL. A coleção chegou a 477 fichas e 959 exemplos. A 0.8.1 mantém essas fichas e imagens e amplia a revisão de leitura, chegando a 966 exemplos.

## Conferência registrada

| Item | Evidência |
|---|---|
| Exemplos PostgreSQL | 80 executados via PGlite/WASM, incluindo dois planos |
| Interface | 1.608 verificações nas 477 fichas |
| Tabelas | 53 verificações adicionais, incluindo as 52 fichas SQL |
| Imagens e indicadores | 493 recursos locais decodificados |
| Atualização | Simulação sobre a coleção 0.8.0 preservando os dados pessoais de consulta |
| APK | Versão 0.8.1, versionCode 22, assinatura original v2/v3 preservada |

A conferência de PostgreSQL usa um motor local de desenvolvimento, sem testar um servidor externo. Os sete exemplos SQL Server/Oracle mantêm revisão documental, sem execução nativa. Os demais módulos tiveram preservação do código e conferência de interface, sem uma nova execução integral dos exemplos. A instalação física ainda depende do aparelho.
