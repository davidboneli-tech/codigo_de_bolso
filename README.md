<div align="center">

# 📘 Código de Bolso

### Conhecimento à mão. Mais tempo para aprender.

**📱 Android · 📴 Offline · 🔎 Consulta rápida · 🎓 Aprendizado**

Uma biblioteca de consulta pessoal para acompanhar os estudos de programação e análise de dados.

**380 fichas · 28 categorias · Versão 0.6.1**

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

A versão documentada reúne **380 fichas em 28 categorias**, agrupadas aqui por área:

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

A coleção inclui 815 exemplos, código agrupado por tarefa e 22 imagens de gráficos para consulta offline. As áreas possuem sublistas para manter a navegação compacta. Power BI permanece como possibilidade de expansão.

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

**Versão documentada: 0.6.1.** O manifesto define Android 8.0 como versão mínima. A compatibilidade precisa ser verificada no aparelho; não há declaração de testes em todos os modelos Android.

A revisão 0.6.1 simplificou as explicações e reuniu linhas de uma mesma tarefa. Foram executados 8 exemplos novos e 1.109 verificações de interface; a lógica e as saídas dos outros 807 exemplos foram preservadas. O APK foi compilado e teve a assinatura verificada. David confirmou o funcionamento da 0.6.0 no aparelho; a instalação da 0.6.1 ainda precisa ser conferida. Veja [escopo e limites dos testes](docs/escopo_e_validacao.md).

## 🤝 Concepção e desenvolvimento

**David dos Santos Boneli** — idealização, definição das necessidades, escolhas de interface, prioridades e avaliação do uso cotidiano.

O desenvolvimento contou com assistência de inteligência artificial na implementação, nas revisões e na documentação. O projeto mostra como uma necessidade pessoal pode ser transformada em requisitos, decisões de produto e um aplicativo funcional, com evolução a partir do uso.

## 📚 Documentação do projeto

| Documento | O que você encontra |
|---|---|
| [Arquitetura](docs/arquitetura.md) | Organização técnica e decisões de implementação |
| [Escopo e validação](docs/escopo_e_validacao.md) | Estado documentado e limites das verificações |
| [Padrão de atualizações](docs/padrao_atualizacoes.md) | Critérios para manter as próximas versões consistentes |
| [Publicação](docs/publicacao.md) | Cuidados com imagens, dados e materiais de terceiros |
| [Histórico](CHANGELOG.md) | Alterações na apresentação do portfólio |
| [Direitos](DIREITOS.md) | Condições de disponibilização |

## 🔐 Sobre este repositório

Esta é a apresentação pública do projeto. O código completo e o instalador permanecem reservados. A publicação da documentação não concede autorização para exploração comercial do aplicativo; consulte o aviso de direitos.

As capturas de tela serão acrescentadas após a revisão dos dados e dos recursos visuais apresentados.
