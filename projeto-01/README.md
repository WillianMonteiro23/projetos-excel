
# 🧹 Projeto de Limpeza de Dados com Excel – Vendas de Café

## Descrição do Projeto

Este projeto apresenta um trabalho completo de **tratamento de dados sujos** utilizando **apenas o Microsoft Excel** como ferramenta principal. O conjunto de dados, originalmente com 10.000 registros, simula transações de vendas em uma cafeteria, contendo diversos tipos de erros e inconsistências que desafiam a qualidade das análises.  
Nosso objetivo foi **reduzir ruídos e inconsistências de forma não agressiva**, mantendo o máximo de informações úteis e relevantes para análises futuras. Ao final do processo, obtivemos **9.872 registros limpos e prontos para uso**, combinando lógica de negócios, conhecimento analítico e técnicas robustas de limpeza com Excel.

## Base de Dados

A base "Dirty Cafe Sales" foi extraída da plataforma [**Kaggle**](https://www.kaggle.com) e pode ser visualizada neste repositório no seguinte link:  
[**dirty_cafe_sales.xlsx**](https://github.com/WillianMonteiro23/projetos-sql/blob/main/projeto-03/dirty_cafe_sales.xlsx)

Este arquivo representa um conjunto propositalmente bagunçado, com:
- Dados faltantes
- Tipos inconsistentes
- Colunas desorganizadas
- Valores errôneos ou fora de padrão

## Objetivos

- **Limpeza de Dados via Excel**:  
  Aplicar fórmulas, filtros avançados, formatações condicionais, validações de dados e substituições manuais para tratar e reduzir inconsistências nos dados brutos.

- **Tratamento Lógico de Colunas**:  
  Aplicação de lógica de negócio para reconstrução de colunas, tratamento de valores fora do padrão e uso de funções "SE", "PROCV", "SUBSTITUIR", entre outras.

- **Padronização e Conversão de Tipos**:  
  Correção de formatos de data, moeda, texto e números, garantindo a consistência dos dados para análises futuras.

- **Redução não agressiva de registros**:  
  Ao longo do processo, apenas registros totalmente irrelevantes foram removidos, respeitando a integridade do conjunto.

## Técnicas Aplicadas

- **Funções de limpeza e manipulação**:  
  `SE()`, `PROCV()`, `SEERRO()`, `OU()`, `E()` e outras.

- **Formatações e Validações**:  
  Uso de **formatação condicional**, **validação de dados** e **classificações personalizadas**.

- **Criação e Combinação de Colunas**:  
  Combinação de dados dispersos em colunas únicas e criação de campos derivados com base em regras e inferências.

- **Registro de Mudanças (Change Log)**:  
  Toda a limpeza foi registrada em um documento para rastreabilidade:  
  [**changelog.xlsx**](https://github.com/WillianMonteiro23/projetos-sql/blob/main/projeto-03/changelog.xlsx)

## Resultado Final

- Os resultados podem ser vistos em :[**dirty_cafe_sales_FINAL.xlsx**](https://github.com/WillianMonteiro23/projetos-sql/blob/main/projeto-03/dirty_cafe_sales_FINAL.xlsx)
- Dados tratados: **9.872 registros válidos**
- Redução de dados apenas em linhas completamente inúteis
- Dados prontos para análise em **Power BI**, **Excel** ou outras ferramentas
- Padronização de tipos e formatos aplicados com cuidado

## Potencial de Uso

Este dataset limpo pode ser usado para:
- Dashboards financeiros e de vendas
- Análises de comportamento de compra
- Projeções de demanda
- Criação de pipelines com ferramentas de BI

## Conclusão

O uso exclusivo do **Excel** neste projeto demonstrou que é possível executar uma limpeza profunda e estruturada mesmo sem linguagens de programação. Através de lógica condicional, funções avançadas e boas práticas de manipulação de dados, foi possível transformar um dataset cheio de ruído em uma base limpa, confiável e pronta para análise.

Este projeto reforça a importância da **limpeza de dados como uma etapa essencial** na jornada analítica, garantindo integridade e qualidade para as decisões baseadas em dados.
