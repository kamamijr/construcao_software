# Análise do Artigo sobre Qualidade de Código em Desenvolvimento de Software

## Ideias Principais do Texto
O artigo aborda a importância da qualidade no desenvolvimento de software, destacando técnicas e ferramentas para medição e garantia dessa qualidade. Através da verificação estática e de métricas como complexidade ciclomática e coesão de métodos, desenvolvedores e líderes de projetos podem identificar e corrigir problemas potenciais no código. Ferramentas como SonarQube e a iniciativa brasileira Code Sheriff são mencionadas como soluções eficazes para monitoramento contínuo da qualidade do código.

## Novidades em Relação ao Conteúdo do Artigo
Para mim, a discussão sobre a "Falta de coesão em métodos (LCOM)" foi particularmente reveladora. A métrica LCOM ajuda a entender como os métodos dentro de uma classe acessam variáveis e métodos comuns, indicando potenciais problemas de design por ter responsabilidades múltiplas ou mal distribuídas dentro da classe. Essa métrica, especificamente, é nova para mim e parece ser um excelente indicador para avaliar a manutenibilidade do código.

## O que já era conhecido
 a importancia incluir a verificação do código a cada commit durante a integração contínua, mas também permitir ao desenvolvedor a possibilidade de ter ciência dos valores da métrica na máquina dele. Por mais que existam dashboards para mostrar gráficos de evolução, é importante que desenvolvedor possa verificar localmente como está seu código e se sentir seguro a commitar as alterações

## Conhecimentos Prévios
Estava familiarizado com muitos dos conceitos apresentados, como a complexidade ciclomática e a importância de evitar duplicação de código. Também conhecia o SonarQube como uma ferramenta de análise de qualidade de código, mas não estava ciente das especificidades de algumas métricas como a LCOM e os detalhes sobre a customização.
