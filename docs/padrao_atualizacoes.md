# Padrão para próximas atualizações

1. Registrar o problema, a alteração e o comportamento esperado.
2. Implementar e testar no projeto reservado.
3. Atualizar a versão do aplicativo quando houver nova entrega.
4. Revisar este README e as páginas afetadas; separar funcionalidades existentes de propostas.
5. Registrar a mudança documental no CHANGELOG, sem inventar histórico anterior.
6. Revisar a lista exata de arquivos antes de publicar.

## Regras específicas

- Preservar os identificadores das fichas e a compatibilidade dos favoritos.
- Explicar o objetivo em linguagem de iniciante; incluir exemplos comentados e resultados esperados.
- Revisar exemplos e diferenças de versão antes de ampliar o conteúdo.

## Escrita

Usar português claro, nomes de arquivos em snake_case e links relativos. Documentar problema, decisão, resultado e limites da validação. Identificar assistência de IA de forma transparente.

## Critérios didáticos e regressão

- Usar o Guia Mestre reservado como referência central, evitando orientações concorrentes.
- Separar código, explicação e saída, mantendo a leitura completa no celular.
- Usar pequenos trechos da base fictícia e registrar decisões de limpeza.
- Testar busca com linguagem natural, sinônimos, acentos, nomes de comandos e filtros.
- Preservar assinatura, pacote, IDs e dados pessoais; não gerar nova chave automaticamente.
- Distinguir execução real de exemplos, revisão técnica, teste de navegador e instalação no Android.

## Padrão aprovado após uso da 0.6.0

Não usar metas de palavras ou caracteres. A ficha int/float/str aprovada por David orienta a clareza: explicação suficiente, exemplo independente, código agrupado por tarefa e resultado separado. Não separar cada linha em um bloco, não repetir parágrafos genéricos e não exigir consulta à Base de Dados. Manter aprofundamento técnico opcional. Confirmar entendimento pelo uso, além dos testes de funcionamento.

## Critérios acrescentados na 0.7.9

- Identificar a fase pelo assunto principal da taxonomia, não apenas pela categoria de navegação. Registrar complementos associados por afinidade.
- Evitar selos genéricos de qualidade, como “Ficha revisada”. A documentação deve informar o que foi efetivamente conferido.
- Começar por uma explicação direta e um exemplo principal. Manter aprofundamentos acessíveis, sem exigir que o leitor veja todos de uma vez.
- Conferir se uma nota de bloco explica o próprio bloco, e não uma consulta de outro exemplo.
- Distinguir exemplo duplicado de uma fórmula igual aplicada a dados diferentes.
- Não desenhar uma segunda cópia do código abaixo dos mesmos blocos. A função de cópia foi retirada na 0.8.1.
- Conferir os novos arquivos na lista de recursos locais permitidos pelo Android, além do teste visual no navegador.
- Publicar contagens e resultados observados. Separar triagem editorial, execução de exemplos, teste de navegador, compilação e teste físico.


## Critérios atuais — 0.8.1

- Manter o código visível para leitura, com resultado e interpretação suficientes na própria ficha.
- Não reintroduzir controles de copiar, exportar ou compartilhar sem uma solicitação do usuário.
- Nos exemplos SQL, apresentar a pergunta e os dados usados; identificar o banco e diferenciar saída fixa de resultado variável.
- Preservar fases e ilustrações ao revisar textos.
- Ao atualizar o GitHub, conferir README, About, histórico e documentação afetada contra os registros da entrega.
- Imagens públicas devem estar na lista explícita de amostras, ter texto alternativo e representar recursos efetivamente usados no app.
