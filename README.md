# SSA - São Salvador Alimentos S.A.

Somos o grupo São Salvador Alimentos S.A., uma das principais empresas produtoras de carne de frango do Brasil, com atuação em todas as etapas da cadeia produtiva, desde a produção de ovos férteis até a distribuição de produtos in natura e processados para o Brasil e o exterior. 
Nosso parque industrial é composto por dois complexos produtivos instalados nas cidades de Itaberaí e de Nova Veneza, no estado de Goiás, o que nos proporciona uma capacidade diária de abate de aproximadamente 520 mil aves.

A empresa gentilmente disponibilizou um conjunto de dados com o objetivo de realizar uma análise exploratória. Os dados fornecidos são extremamente valiosos, 
pois permitem que exploremos de maneira mais aprofundada as informações contidas neles. Com base nessa análise, poderemos obter insights importantes, identificar padrões, tendências e relações entre 
os diferentes elementos presentes nos dados. O esquema ficou assim: 

```bash

    NOME
    EQUIPE
    GESTOR
    INICIO-A-QUISITIVO
    FIM_P_AQUISITIVO
    GOZO_VENDA
    DATA_INICIO	DATA_FIM
    QTD_DIAS_GOZO	PESSOA BACKUP

```
## Passos para a realização das análises da SSA - ferias dos funcionários. 

```bash

  1 - Importação de Bibliotecas
  2 - Lendo o Dataset de Ferias dos Funcionários
  3 - Exclusão dos dados irrelevantes das seguintes tabelas: 'INICIO-A-QUISITIVO', 'FIM_P_AQUISITIVO', 'GOZO_VENDA', 'DATA_INICIO', 'DATA_FIM', 'PESSOA BACKUP'
  4 - Verificação de dados nulos
  5 - Verificação de dados duplicados
  6 - Exclusão dos dados duplicados
  7 - Conversão da Coluna INICIO-A-QUISITIVO em formato Data
  8 - Conversão da Coluna FIM_P_AQUISITIVO em formato Data
  9 - Conversão da Coluna DATA_INICIO em formato Data
  10 - Conversão da Coluna DATA_FIM em formato Data
  11 - Conversão da Tabela Id do formato float para o int

```

# Análise dos dados da SSA - São Salvador Alimentos S.A. com as seguintes perguntas.

. Na Linguagem Python 

```bash
  1) quantas pessoas estão de ferias ?
  2) Quantas pessoas estão programadas a cada mes por setor? Operaçoes - Governança - Delivery - Soluçoes - arquitetura.
  3) Se tem conflito na programaçao das datas? e quais os nomes estao chocando as ferias.
```

. No Power BI 

```bash
  1) Quantidade de Ferias das Pessoas
  2) Quantidade de Pessoas Programadas por Mês
  3) Número de Conflitos de férias por funcionário
  4) Quantidade de dias de Atividade
  5) Total de Quantidade de Dias por Gozo Venda
  6) Conflito por Nome
  7) Índice do Aquisitivo
  8) Índide do Trabalho
  9) Total de Dias Gozo
  10) Calendário de Atividades por Equipe 
  11) Calendário de Atividades por Gestor
```

## Tecnologias Utilizadas  

** O projeto foi desenvolvido com as seguintes tecnologia ** 

- [anaconda](https://www.anaconda.com/) 

- [jupyter notebook](https://jupyter.org/)

- [Python](https://www.python.org/) 

** Pacotes para a manipulação e analise de dados 

- [pandas](https://harve.com.br/blog/programacao-python-blog/pandas-python-vantagens-e-como-comecar/)

- [numpy](https://numpy.org/)

- [matplotlib](https://matplotlib.org/)

## Visualização do Projeto em Python e Power BI 

 1. Python

 ```bash

  ## 1 - Clique no arquivo SSA.pbix 
  ## 2 - Vai aparecer um link chamado View raw, aperte nele e abra o projeto no Power BI Desktop

  Obs: O Power BI só vai funcionar somente na versões Windows 7, 8, 8.1, 10 ou 11

```
 2. Power BI
    
```bash

  ## 1 - Clique no arquivo SSA.ipynb e no outro chamado SSA.ipynb
  ## 2 - Já vai aparecer pronto o formato da Ide Python - Jupyter Notebook para a visualização do código 

```

