# Análise de Acidentes em Rodovias Federais Brasileiras

## Visão Geral

Este projeto tem como objetivo analisar os acidentes registrados pela Polícia Rodoviária Federal (PRF) para identificar padrões relacionados à frequência, localização, causas e gravidade dos acidentes nas rodovias federais brasileiras.

Dataset : https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf

A análise foi desenvolvida utilizando Python para tratamento e exploração dos dados e Power BI para construção de um dashboard executivo.

---

## Objetivo

Compreender os principais fatores associados à ocorrência e à gravidade dos acidentes rodoviários, gerando insights que possam apoiar ações de fiscalização, prevenção e segurança viária.

As principais perguntas de negócio investigadas foram:

* Onde ocorrem mais acidentes?
* Em quais períodos os acidentes são mais frequentes?
* Quais são as principais causas registradas?
* Quais fatores estão mais associados aos acidentes fatais?
* Quais regiões apresentam maior concentração de ocorrências?

---

## Fonte dos Dados

Base pública disponibilizada pela Polícia Rodoviária Federal (PRF).

Período analisado: 2026.

---

## Ferramentas Utilizadas

### Análise de Dados

* Python
* Pandas
* NumPy
* Matplotlib

### Visualização de Dados

* Power BI

### Ambiente de Desenvolvimento

* Google Colab

---

## Metodologia

### 1. Entendimento dos Dados

Foi realizada uma análise inicial para compreender:

* Estrutura do dataset
* Tipos de variáveis
* Qualidade dos dados
* Valores ausentes
* Possíveis inconsistências

### 2. Limpeza e Preparação

Principais etapas executadas:

* Conversão de variáveis de data e hora
* Criação de variáveis temporais (mês e hora)
* Tratamento de valores ausentes
* Padronização de categorias
* Validação da granularidade dos registros

### 3. Análise Exploratória

A análise foi estruturada para responder às principais perguntas de negócio:

#### Distribuição Geográfica

* Acidentes por estado
* Acidentes por município
* Rodovias com maior incidência

#### Distribuição Temporal

* Acidentes por hora
* Acidentes por dia da semana
* Acidentes por mês

#### Causas dos Acidentes

* Principais causas registradas
* Tipos mais frequentes de acidentes

#### Gravidade

* Total de mortes
* Total de feridos graves
* Causas com maior potencial letal

#### Perfil das Vítimas

* Distribuição por sexo
* Distribuição por faixa etária

---

## Dashboard

O dashboard foi desenvolvido para fornecer uma visão executiva dos acidentes registrados nas rodovias federais brasileiras.

Principais indicadores:

* Total de acidentes
* Total de mortes
* Total de feridos graves
* Quantidade de municípios afetados

Principais visualizações:

* Mapa de distribuição geográfica
* Acidentes por estado
* Acidentes por hora
* Acidentes por dia da semana
* Principais causas
* Principais tipos de acidentes
* Análise de gravidade dos acidentes

---

## Principais Insights

A análise identificou que:

* Os acidentes estão concentrados em corredores rodoviários específicos.
* A maior parte das ocorrências está associada a fatores comportamentais dos condutores.
* Algumas causas apresentam menor frequência, porém maior letalidade.
* Determinados períodos do dia concentram maior número de acidentes graves.
* A distribuição geográfica permite identificar regiões prioritárias para ações preventivas.


Tecnologias aplicadas: Python, Power BI, Estatística Descritiva, Análise Exploratória de Dados e Storytelling com Dados.
