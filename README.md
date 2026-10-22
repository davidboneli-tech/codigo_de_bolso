<div align="center">

# 📘 Código de Bolso

### Conhecimento à mão. Mais tempo para aprender.

**📱 Android · 📴 Offline · 🔎 Consulta rápida · 🎓 Aprendizado**

Uma biblioteca de consulta pessoal para acompanhar os estudos de programação e análise de dados.

**455 fichas · 35 categorias · Versão 0.7.9**

</div>

---

## 💡 Por que este aplicativo foi criado?

O Código de Bolso nasceu durante meus estudos de programação e análise de dados. Ao resolver um exercício, eu frequentemente precisava voltar às apostilas para encontrar um comando, lembrar uma sintaxe ou entender como aplicar uma função.

Eu queria consultar esse conteúdo no celular, mesmo sem internet, e encontrar explicações que fizessem sentido para quem ainda estava aprendendo. Uma lista de comandos, sozinha, não atendia à necessidade: era preciso mostrar **para que servem, como usar e o que esperar do resultado**.

Também queria uma interface agradável, com ícones, cores e assuntos fáceis de localizar. A organização de aplicativos de referência técnica, como o Electrodoc, serviu de inspiração para essa experiência de consulta.

> 🎯 **Objetivo:** reduzir o tempo gasto procurando informações e apoiar a compreensão durante a prática.

## ✨ O que o aplicativo oferece

| Recurso | Como ajuda nos estudos |
|---|---|
| 🔎 Busca local | Pesquisa comandos, explicações e exemplos, com sinônimos, tolerância a erros de digitação e opção de buscar em toda a coleção |
| 🗂️ Categorias | Organiza o conteúdo para explorar um assunto por vez |
| ⭐ Favoritos | Mantém os assuntos mais úteis por perto |
| 🕘 Consultas recentes | Facilita retomar uma ficha já visitada |
| 🧩 Exemplos práticos | Mostra a aplicação dos conceitos em situações concretas |
| 🎨 Personalização | Permite ajustar tema, cor de destaque e tamanho do texto |
| ↕️ Organização da lista | Adapta a ordem dos assuntos à rotina de consulta |

A busca consulta o conteúdo disponível no aplicativo. Ela não é um chatbot e não gera respostas novas com IA.

## 🧠 O que posso consultar?

A versão documentada reúne **455 fichas em 35 categorias**, agrupadas aqui por área:

| Área | Assuntos presentes |
|---|---|
| 🐍 Fundamentos de Python | Tipos, textos, funções, erros, arquivos, classes e objetos |
| 📦 Coleções | Listas, tuplas, dicionários, sets e frozenset |
| 🧹 Tratamento de dados | Limpeza de textos, expressões regulares e roteiros de transformação |
| 📊 Análise com Python | Pandas, NumPy, Matplotlib e Seaborn |
| 🌐 Coleta de informações | Web scraping e BeautifulSoup |
| 🗄️ Banco de Dados | SQL/PostgreSQL, modelagem, NoSQL e MongoDB |
| 📖 Consulta | Glossário com filtro próprio e base fictícia original/tratada |
| 📗 Excel | Fórmulas, buscas, condições, textos, datas, estatística e Power tools |
| 🛠️ Ferramentas | Git, GitHub e VS Code |
| 📈 Business Intelligence | Power BI, DAX, Power Query/M e Tableau |
| 🧭 Fundamentos e estatística | Granularidade, métricas, qualidade, amostragem e medidas descritivas |

A coleção inclui **926 exemplos**, **444 fichas com ilustrações 3D** e **11 fichas com gráficos nos exemplos**, cobrindo as 455 fichas com recursos visuais. São 22 imagens de gráficos, além de cinco indicadores de fase no mesmo padrão 3D. As imagens acompanham o APK para consulta offline.

Cada ficha identifica a fase do assunto principal na taxonomia: **F1 — Fundamentos; F2 — Analista de Dados; F3 — Analista avançado; F4 — Cientista de Dados; F5 — Especialização**. Essa indicação orienta o estudo; não certifica domínio do tema.

A leitura começa por uma explicação direta e um exemplo principal. Outros exemplos, sintaxe, preparação de dados e cuidados ficam disponíveis em seções que o leitor pode abrir. O código completo permanece copiável.

## 📖 Como ele entra na rotina

Imagine que um campo de telefone contenha espaços, letras e pontuação. A consulta começa por assuntos como limpeza de texto ou expressões regulares. A ficha ajuda a identificar a operação apropriada, observar os exemplos e adaptar a solução ao exercício.

Outro caminho é abrir uma categoria, como dicionários, consultar uma operação e marcá-la como favorita para revisar depois. O aplicativo funciona como apoio à prática; os exercícios continuam sendo realizados no ambiente de programação.

## 🧭 Decisões que orientam o projeto

- **Funcionamento offline:** o conteúdo acompanha o aplicativo e pode ser consultado sem rede.
- **Linguagem acessível:** as revisões priorizam explicações compreensíveis para iniciantes, com exemplos e resultados.
- **Consulta em pequenas fichas:** cada entrada concentra uma necessidade de aprendizado, sem exigir a leitura de um capítulo inteiro.
- **Conteúdo separado da interface:** facilita revisar explicações e ampliar a base nas próximas versões.

## ⚙️ Como foi construído

| Tecnologia | Responsabilidade |
|---|---|
| Java + Android WebView | Executar a interface local e integrar o aplicativo ao Android |
| HTML + CSS | Estruturar as telas e definir a apresentação visual |
| JavaScript | Busca, navegação, interações e preferências |
| JSON e armazenamento local | Organizar as fichas e preservar os dados de consulta |
| Python | Preparar conteúdo e automatizar a geração do APK |

O aplicativo usa um processo de compilação próprio com JDK 17 e Android SDK 35, sem Gradle. Python participa das ferramentas de desenvolvimento; a interface do aplicativo usa HTML, CSS e JavaScript dentro de uma WebView Android.

## ✅ Estado do projeto

**Versão documentada: 0.7.9, atualizada em 22/10/2026.** O manifesto define Android 8.0 como versão mínima. A compatibilidade precisa ser verificada no aparelho; não há declaração de testes em todos os modelos Android.

A revisão 0.7.9 partiu de relatos de explicações difíceis e repetidas. Foram lidos os resumos das 455 fichas, reescritos 118 e retiradas 315 frases repetidas entre exemplos. O rótulo “Ficha revisada” foi substituído por indicadores de fase, e a leitura passou a destacar um exemplo por vez.

Foram executados **282 exemplos de Python e 41 de SQL**, comparando as saídas esperadas, além de **1.382 verificações de interface nas 455 fichas** e **41 verificações de leitura guiada**. O navegador decodificou 471 recursos locais sem requisições externas, usando a lista de recursos permitidos pelo Android. A simulação de atualização sobre a 0.7.8 preservou favoritos e preferências; o APK foi compilado com a chave original e teve assinatura v2/v3 verificada.

Esses resultados não significam execução dos 926 exemplos nem garantia de clareza em todas as situações. Excel, Power BI, Tableau, MongoDB e MySQL não foram executados em seus programas nativos nesta rodada. A instalação da 0.7.9 no aparelho ainda precisa ser conferida. Veja [escopo e limites dos testes](docs/escopo_e_validacao.md) e [revisão didática 0.7.9](docs/revisao_0_7_9.md).

## 🤝 Concepção e desenvolvimento

**David dos Santos Boneli** — idealização, definição das necessidades, escolhas de interface, prioridades e avaliação do uso cotidiano.

O desenvolvimento contou com assistência de inteligência artificial na implementação, nas revisões e na documentação. O projeto mostra como uma necessidade pessoal pode ser transformada em requisitos, decisões de produto e um aplicativo funcional, com evolução a partir do uso.

## 📚 Documentação do projeto

| Documento | O que você encontra |
|---|---|
| [Arquitetura](docs/arquitetura.md) | Organização técnica e decisões de implementação |
| [Escopo e validação](docs/escopo_e_validacao.md) | Estado documentado e limites das verificações |
| [Revisão didática 0.7.9](docs/revisao_0_7_9.md) | Clareza, fases de estudo, mudanças e evidências |
| [Padrão de atualizações](docs/padrao_atualizacoes.md) | Critérios para manter as próximas versões consistentes |
| [Publicação](docs/publicacao.md) | Cuidados com imagens, dados e materiais de terceiros |
| [Histórico](CHANGELOG.md) | Alterações na apresentação do portfólio |
| [Direitos](DIREITOS.md) | Condições de disponibilização |

## 🔐 Sobre este repositório

Esta é a apresentação pública do projeto. O código completo e o instalador permanecem reservados. A publicação da documentação não concede autorização para exploração comercial do aplicativo; consulte o aviso de direitos.

As capturas de tela serão acrescentadas após a revisão dos dados e dos recursos visuais apresentados.
