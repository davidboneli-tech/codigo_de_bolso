## Revisão 0.6.1 — clareza após uso real

David confirmou o funcionamento da 0.6.0 no aparelho, mas relatou explicações confusas e excesso de blocos. A revisão remove 311 parágrafos automáticos repetidos, mantém exemplos curtos em um bloco completo e deixa detalhes técnicos recolhidos. A Base de Dados é opcional. Não há meta de palavras ou caracteres: a explicação deve ter o tamanho necessário para ser entendida.

A ficha int/float/str foi refeita conforme o modelo aprovado; também foram revistas explicações de SQL, modelagem, BeautifulSoup e exemplos de Pandas/NumPy. São 380 fichas e 815 exemplos. Foram executados 8 exemplos novos, preservada a semântica e as saídas de 807 exemplos e concluídas 1.109 verificações de interface, incluindo migração do conteúdo 0.6.0. O APK 0.6.1 foi compilado e sua assinatura v2/v3 verificada. A instalação física desta revisão está pendente. Os testes da edição anterior são históricos, não uma nova execução nesta revisão.

---

## Histórico da validação anterior

# Versão 0.6.0 — escopo e validação

Atualização de 20/09/2026, baseada no projeto reservado 0.5.0.

## O que mudou

A dificuldade de encontrar palavras e compreender explicações curtas orientou esta edição. A coleção passou de 311 para **380 fichas**, distribuídas em **28 categorias**, com **810 exemplos**. Os 311 identificadores anteriores foram preservados.

- Navegação: Python, Bibliotecas, Banco de Dados, Ferramentas, Excel, Roteiros e Consulta, além de Todos. Sublistas evitam excesso de abas.
- Bibliotecas: Pandas, NumPy, BeautifulSoup, Matplotlib e Seaborn. Banco de Dados: SQL/PostgreSQL, modelagem, NoSQL e MongoDB.
- Fichas com explicações ampliadas e blocos separados de código, comentários, impressão e resultados. Cópia por etapa ou do exemplo completo; aprofundamento avançado quando pertinente.
- Busca local indexa explicações, exemplos e termos, normaliza acentos, considera sinônimos e erros de digitação e oferece busca em toda a coleção.
- Glossário com busca própria, filtro por biblioteca e acesso às fichas relacionadas.
- Base fictícia Loja Horizonte: clientes, produtos, vendas e itens; versões original e tratada, descrição de colunas e decisões de limpeza.
- Roteiros de limpeza e preparação do ambiente Python/venv/Git/GitHub; 22 imagens de gráficos geradas e empacotadas para consulta offline.

## Evidências desta edição

| Verificação | Resultado e limite |
|---|---|
| Exemplos Python | 524 executados sem falha; resultados obtidos no ambiente de desenvolvimento |
| Exemplos SQL | 28 executados e comparados aos resultados esperados usando PostgreSQL 18.3 via PGlite 0.5.8/WASM |
| Interface | 1.105 verificações automatizadas em Chromium, incluindo todas as fichas, busca, glossário, base, cópia, compartilhamento, tema, importação e migração do estado 0.5.0 |
| Funcionamento local | Nenhuma requisição externa nos testes de interface; imagens e conteúdo empacotados |
| APK | Compilado com JDK 17 e Android SDK 35; assinatura v2/v3 verificada; arquivos originais de assinatura preservados |
| Dados pessoais | Simulação de migração preservou favoritos e preferências; todos os IDs antigos mantidos |

Os testes de interface usam navegador automatizado, não substituem Android WebView em aparelho real. Instalação sobre a versão anterior, restauração do backup no telefone e uso cotidiano ainda precisam da conferência de David. Não desinstalar a versão anterior para testar a atualização.

MongoDB e procedimentos de ferramentas foram revisados, mas não executados integralmente nos aplicativos correspondentes. As fichas Excel preservam a base anterior e não representam uma nova execução no Microsoft Excel. SQL via PGlite não testa instalação do pgAdmin, conexão de rede ou permissões de um servidor externo. O app consulta os exemplos; não executa Python, SQL ou MongoDB internamente.

## Fontes e continuidade

A revisão priorizou as apostilas e documentos SCTEC, a pasta **Aulas Tecnicas - Chat GPT** e o guia de referência BeautifulSoup fornecido por David. Referências técnicas: [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/), [PostgreSQL](https://www.postgresql.org/docs/current/tutorial.html), [MongoDB](https://www.mongodb.com/docs/manual/aggregation/), [Matplotlib](https://matplotlib.org/stable/tutorials/pyplot.html) e [Seaborn](https://seaborn.pydata.org/tutorial.html).

Power BI segue sem módulo próprio. O Guia Mestre reservado centraliza decisões; esta página documenta a entrega e seus limites. Código completo, APK e material de assinatura permanecem reservados.
