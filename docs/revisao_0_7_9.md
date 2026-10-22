# Revisão didática 0.7.9

## Problema observado

O uso no celular mostrou explicações repetidas, preparação de dados extensa antes de uma consulta simples e notas que misturavam exemplos. Testes de funcionamento e saídas corretas não eram suficientes para demonstrar clareza para quem aprende sozinho.

## Mudanças

- Lidos os resumos das 455 fichas; 118 foram reescritos com linguagem mais direta.
- Retiradas 315 frases repetidas entre exemplos da mesma ficha.
- Um exemplo fica visível inicialmente. Outros exemplos, sintaxe, cuidados e preparação continuam disponíveis em seções expansíveis.
- O código completo continua copiável sem aparecer novamente abaixo dos mesmos blocos.
- Termos usados na explicação podem ser consultados antes do exemplo.
- A ficha `break`/`continue` acompanha cada passagem da repetição para explicar o que acontece com os valores.
- O rótulo “Ficha revisada” deu lugar a indicadores de fase no padrão visual 3D do aplicativo.

## Fases de estudo

| Fase | Significado | Fichas na coleção |
|---|---|---:|
| F1 | Fundamentos | 32 |
| F2 | Analista de Dados | 235 |
| F3 | Analista avançado | 175 |
| F4 | Cientista de Dados | 12 |
| F5 | Especialização | 1 |

A distribuição refere-se às 455 fichas existentes, não à quantidade total de assuntos previstos pela taxonomia. A fase indica o assunto principal; não certifica domínio de uma área. Conteúdos F4 e F5 mantêm sua classificação. Complementos não enumerados individualmente na taxonomia recebem nota de associação por afinidade.

## Verificações e limites

Foram executados 282 exemplos Python e 41 SQL, além de 1.382 verificações de interface e 41 verificações específicas de leitura guiada. Os códigos e resultados esperados dos 926 exemplos foram preservados em relação à versão 0.7.8.

A interface carregou 471 recursos locais sem acesso externo e preservou os dados pessoais simulados na atualização. O APK foi compilado com o certificado original. A instalação física da 0.7.9 está pendente.

Esta revisão não afirma execução de todos os exemplos nem garante clareza em toda situação. Os aplicativos nativos de Excel, Power BI, Tableau, MongoDB e MySQL não foram usados para executar os exemplos nesta rodada. Consulte o [escopo da validação](escopo_e_validacao.md).
