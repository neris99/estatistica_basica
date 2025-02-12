# Projeto de Análise de Dados de Supermercado

Este projeto faz parte do Módulo 13 do curso **Profissão Cientista de Dados**. O objetivo é aplicar conceitos estatísticos e de visualização de dados em uma base de dados de produtos de um supermercado no Chile.

## 📋 Descrição do Projeto

Neste projeto, trabalhamos com uma base de dados de produtos de um supermercado, contendo informações como nome do produto, marca, preço normal, preço com desconto, preço anterior e categoria. O objetivo é realizar análises estatísticas e criar visualizações para entender o comportamento dos preços e descontos por categoria e marca.

### Dados Utilizados

Os dados estão no arquivo `MODUL07_PROJETOFINAL_BASE_SUPERMERCADO.csv` e contêm as seguintes colunas:

- **Title**: Nome do produto.
- **Marca**: Marca do produto.
- **Preco_Normal**: Preço normal do produto.
- **Preco_Desconto**: Preço com desconto.
- **Preco_Anterior**: Preço anterior antes do desconto.
- **Desconto**: Valor do desconto aplicado.
- **Categoria**: Categoria do produto (em espanhol).

## 🛠️ Ferramentas e Tecnologias

- **Python**: Linguagem de programação utilizada.
- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib e Plotly**: Para criação de gráficos e visualizações.
- **Google Colab**: Ambiente de execução do código.

## 📊 Análises Realizadas

1. **Média e Mediana dos Preços por Categoria**:
   - Calculamos a média e a mediana dos preços normais por categoria e identificamos categorias com valores discrepantes.

2. **Desvio Padrão por Categoria**:
   - Analisamos o desvio padrão dos preços por categoria para entender a variabilidade dos preços.

3. **Boxplot da Distribuição de Preços**:
   - Criamos um boxplot para visualizar a distribuição dos preços na categoria com maior desvio padrão.

4. **Gráfico de Barras de Média de Descontos por Categoria**:
   - Plotamos um gráfico de barras para visualizar a média de descontos por categoria.

5. **Mapa Interativo de Média de Descontos por Categoria e Marca**:
   - Criamos um gráfico de mapa interativo (treemap) para agrupar os dados por categoria e marca, mostrando a média de descontos.

## 📂 Estrutura do Repositório

- **notebooks/**: Contém o arquivo `.ipynb` com o código do projeto.
- **data/**: Contém o arquivo CSV com os dados utilizados.
- **README.md**: Este arquivo, com a descrição do projeto.


