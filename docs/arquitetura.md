# Arquitetura — Código de Bolso

## Organização do aplicativo reservado

| Local | Responsabilidade |
|---|---|
| app/src/main/java/ | Código de integração com o Android |
| app/src/main/assets/ | HTML, CSS, JavaScript, conteúdo e recursos locais |
| app/src/main/res/ | Ícones, temas e recursos Android |
| app/src/main/AndroidManifest.xml | Identificação e componentes do aplicativo |
| tools/ | Scripts de preparação, compilação e verificações |

Esses caminhos descrevem o projeto completo reservado; não são pastas de código deste repositório público.

## Funcionamento

O Android abre uma WebView que carrega a interface empacotada no próprio APK. HTML e CSS apresentam as telas; JavaScript trata as interações e usa a ponte nativa quando necessário. O manifesto não solicita permissão de internet.

O conteúdo acompanha o aplicativo em arquivos locais. A interface usa localStorage para conteúdo atualizado e preferências, incluindo favoritos e histórico.

## Decisões

- Conteúdo separado da interface para facilitar revisões editoriais.
- Busca local para consultar o material sem depender de uma API de IA.
- Explicações proporcionais à dificuldade e exemplos divididos em blocos legíveis.

## Compilação

O projeto completo possui script Python próprio, utilizando JDK 17, Android SDK Platform 35 e Build Tools 35.0.0, sem Gradle. O repositório público é documental e não permite compilar o aplicativo.

## Evolução 0.6.0

Uma camada de interface organiza áreas e sublistas, busca ampliada, glossário e base fictícia. Os exemplos mantêm código completo e blocos didáticos; gráficos estáticos são recursos locais. O índice de pesquisa é reconstruído após importação ou restauração do conteúdo. Os identificadores e a origem local do armazenamento foram preservados para manter as preferências da versão anterior.

A compilação exige os arquivos originais de assinatura e interrompe se estiverem ausentes. Motores Python/PostgreSQL usados nas verificações são ferramentas de desenvolvimento e não acompanham o aplicativo.
