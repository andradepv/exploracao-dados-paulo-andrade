# Análise Exploratória de Dados – Dataset HIPERDIA

## Descrição do Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) utilizando Python sobre um dataset relacionado ao programa HIPERDIA, que acompanha registros associados ao monitoramento de condições de saúde.

A análise foi desenvolvida em um notebook utilizando bibliotecas de ciência de dados para limpeza, tratamento e visualização das informações.

---

## Etapas Realizadas

### 1. Carregamento dos Dados
O dataset foi importado utilizando a biblioteca **pandas**, considerando o separador correto do arquivo CSV.

### 2. Tratamento dos Dados
Foram realizadas algumas etapas de limpeza, incluindo:

- Conversão de colunas que estavam como `object` para formato numérico;
- Substituição de valores ausentes representados por "-" por `0`;
- Ajuste dos tipos de dados para permitir análises estatísticas.

### 3. Análise Estatística
Foram calculadas estatísticas descritivas, como:

- média
- mediana
- moda
- valores mínimo e máximo
- desvio padrão e variância
- quartis e intervalo interquartil (IQR)
- verificação de valores ausentes
- identificação dos tipos de dados

### 4. Visualização dos Dados
Foram gerados gráficos para melhor compreensão dos dados:

- histogramas
- boxplots
- gráficos de dispersão
- matriz de correlação

Essas visualizações ajudaram a identificar padrões, distribuição dos valores e possíveis outliers.

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Objetivo da Análise

O principal objetivo foi compreender o comportamento dos dados, identificar padrões, possíveis irregularidades e preparar o dataset para análises futuras.

---

## Autor

Paulo Andrade
