# Análise de Preços de Carros no Brasil - Estudo de Caso em Análise e Visualização de Dados

# Análise de Preços de Carros no Brasil 🚗🇧🇷

Este projeto consiste em um estudo de caso de Análise de Dados focado no mercado automotivo brasileiro. O objetivo é explorar e entender as tendências de preços de veículos utilizando um dataset histórico de preços (Tabela Fipe).

## 📋 Sobre o Projeto

O notebook realiza uma análise exploratória de dados (EDA) para entender o comportamento dos preços de carros no Brasil. O processo passa pelo entendimento do negócio, limpeza e preparação dos dados, até a visualização de insights sobre marcas e características dos veículos.

* **Arquivo do Notebook:** `Analise_de_Precos_de_Carros_no_Brasil.ipynb`
* **Autor:** Thiago Pereira Magalhães
* **Turma:** Engenharia e Análise de DADOS - 2025.2
* **Data:** Novembro de 2025

## 🗂️ Dados Utilizados

O dataset (`precos_carros_brasil.csv`) contém informações históricas e detalhadas sobre veículos. As principais colunas analisadas são:

* `year_of_reference`: Ano de referência da coleta do preço.
* `month_of_reference`: Mês de referência.
* `fipe_code`: Código Fipe do veículo.
* `brand`: Marca do fabricante (ex: Fiat, Ford, GM - Chevrolet).
* `model`: Modelo do veículo.
* `fuel`: Tipo de combustível (Gasoline, Alcohol, Diesel, etc.).
* `gear`: Tipo de câmbio (manual, automatic).
* `engine_size`: Tamanho do motor (1.0, 1.6, etc.).
* `year_model`: Ano de fabricação do modelo.
* `avg_price_brl`: Preço médio em Reais (BRL).

## 🛠️ Tecnologias e Bibliotecas

O projeto foi desenvolvido em Python utilizando o ambiente Google Colab. As principais bibliotecas utilizadas foram:

* **Pandas:** Para manipulação, limpeza e análise de dados tabulares.
* **Matplotlib:** Para geração de gráficos e visualização de dados.

## 🚀 Etapas da Análise

1.  **Entendimento dos Dados:**
    * Carregamento do arquivo CSV.
    * Inspeção inicial (`head`, `info`, `describe`).
    * Verificação de tipos de dados e valores nulos.
    * Identificação de duplicatas.

2.  **Preparação dos Dados (Data Cleaning):**
    * Remoção de registros duplicados.
    * Correção de dados inconsistentes (ex: ajuste manual de dados faltantes ou errados em registros específicos, como o índice 187088).

3.  **Análise Exploratória (EDA):**
    * **Distribuição por Marca:** Visualização da quantidade de carros presentes no dataset agrupados por fabricante.
    * **Distribuição por Câmbio:** Análise da predominância de tipos de câmbio (Manual vs Automático) no mercado.

## 📊 Resultados Preliminares

* O dataset abrange uma grande quantidade de registros (mais de 200.000 entradas) entre os anos de referência de 2021 a 2023.
* A análise gráfica revelou a distribuição de volume de ofertas entre as principais marcas (como Fiat, Volkswagen, Chevrolet).
* Foi possível observar a proporção entre carros manuais e automáticos na base de dados.

## 🔧 Como Executar

1.  Certifique-se de ter o Python instalado ou utilize o [Google Colab](https://colab.research.google.com/).
2.  Instale as dependências necessárias:
    ```bash
    pip install pandas matplotlib
    ```
3.  Faça o upload do dataset `precos_carros_brasil - precos_carros_brasil.csv` para o ambiente de execução.
4.  Execute as células do notebook sequencialmente.
