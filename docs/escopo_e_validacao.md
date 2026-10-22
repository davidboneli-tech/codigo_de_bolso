# Versão 0.7.9 — escopo e validação

Estado da entrega de 22/10/2026. Os registros anteriores aparecem abaixo como histórico.

## Acervo e revisão

- 455 fichas, 35 categorias e 926 exemplos.
- 444 fichas com ilustrações próprias; as outras 11 têm gráficos nos exemplos. Há 22 imagens de gráficos no acervo.
- Cinco indicadores F1–F5, conforme a fase do assunto principal na taxonomia.
- Leitura dos 455 resumos, reescrita de 118 e retirada de 315 frases repetidas entre exemplos.
- Apresentação com um exemplo principal e detalhes opcionais; preparação SQL recolhida, código completo copiável e ausência do rótulo “Ficha revisada”.

## Evidências desta entrega

| Verificação | Resultado e limite |
|---|---|
| Python | 282 exemplos executados e comparados às saídas esperadas; não corresponde a todos os exemplos Python do acervo |
| SQL | 41 exemplos executados em PostgreSQL via PGlite/WASM e comparados às saídas esperadas; não testa um servidor PostgreSQL externo |
| Estrutura dos exemplos | Os 926 códigos e resultados esperados foram preservados em relação à 0.7.8; as explicações e a apresentação foram revisadas |
| Interface geral | 1.382 verificações em Chromium, percorrendo as 455 fichas e verificando fase, leitura inicial, recursos e funções existentes |
| Leitura guiada | 41 verificações adicionais de abertura de detalhes, cópia e legenda de fase em fichas representativas, incluindo tela estreita |
| Recursos offline | 471 ilustrações, gráficos e indicadores decodificados; nenhuma requisição externa. O teste usa a lista de recursos permitidos no código Android |
| Atualização | Simulação sobre a 0.7.8 preservou favoritos, tema, ordem personalizada e posições de leitura |
| APK | 0.7.9, versionCode 20, compilado; assinatura v2/v3 verificada e certificado comparado com o da versão anterior |

## Limites

A triagem das 455 fichas não é uma declaração de execução de todos os 926 exemplos, nem uma garantia absoluta de clareza ou ausência de erros. A leitura dos resumos, a auditoria estrutural, a execução de código e o uso no aparelho são verificações diferentes.

Excel, Power BI, Tableau, MongoDB, MySQL e procedimentos de aplicativos não foram executados nos programas nativos nesta rodada. As outras amostras fora dos grupos executados preservam código e saídas da base anterior; isso não conta como nova execução.

A instalação e o uso da 0.7.9 no celular ainda precisam de conferência. Chromium não equivale a Android WebView em um aparelho real. O aplicativo é uma ferramenta de consulta; não executa Python, SQL ou MongoDB internamente.

Veja também a [revisão didática 0.7.9](revisao_0_7_9.md).

---

# Registros históricos

# Revisão 0.6.4 — imagens e ícones

A versão 0.6.4 acrescenta 100 ilustrações, totalizando 175 fichas ilustradas, e integra 15 ícones de áreas/programas e quatro ícones de leitura. Foram concluídas 1.873 verificações de interface em Chromium e verificada a assinatura v2/v3 do APK com a chave original. A migração da 0.6.3 preserva favoritos e preferências. Imagens otimizadas em WebP mantêm a consulta offline e a compatibilidade com coleções anteriores. A instalação da 0.6.4 no aparelho ainda precisa ser conferida.

Os 815 exemplos não foram alterados nem reexecutados nesta revisão visual. Os testes verificaram as 380 fichas, 175 ilustrações, 19 ícones, legibilidade em tela pequena, cópia, compartilhamento, busca, filtros, importação, restauração e migração. Não houve requisições externas durante os testes. A conferência em Chromium não substitui o Android WebView no aparelho real.

---

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
