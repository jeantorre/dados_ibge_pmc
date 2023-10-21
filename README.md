# Case Técnico
Notebook com todo o processo de ETL para o case técnico.

## Objetivo
Automatizar o processo de extração e limpeza de dados, dada que as informações são disponibilizadas apenas com dados mensais. Dessa forma se torna mais fácil a utilização de longos períodos, tornando a análise mais rica.

## Observações
Na base de dados obtidas tiveram colunas desnecessárias. Os dados disponibilizados tinham o seguinte *layout*:  

Mês vigente -2 | Mês vigente -1 | Mês vigente
-|-|-
Informação 1| Informação 2| Informação 3  

Como só foram necessárias as informações do mês vigente, as outras foram excluídas.
