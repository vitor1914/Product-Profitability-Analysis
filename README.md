# Análise de Rentabilidade de Produtos | Product Profitability Analysis

🇧🇷 Português | 🇺🇸 English

## 🇧🇷 Sobre o projeto

Este projeto utiliza Google Sheets e Google Apps Script para analisar a rentabilidade de produtos, calcular indicadores financeiros e apresentar os resultados em um dashboard interativo.

A solução automatiza cálculos de receita, custos, despesas, lucro, margem de lucro e retorno sobre o investimento (ROI), facilitando a análise do desempenho comercial por produto e categoria.

## 🎯 Objetivos

- Automatizar cálculos de rentabilidade.
- Identificar produtos rentáveis e produtos com prejuízo.
- Comparar o desempenho financeiro entre categorias.
- Consolidar indicadores em um dashboard.
- Praticar automação de planilhas e análise de dados.

## 🛠️ Tecnologias utilizadas

- Google Sheets
- Google Apps Script
- JavaScript
- Gráficos e indicadores financeiros

## 📊 Estrutura do projeto

### 1. Produtos

Base de dados com informações de produtos, incluindo:

- SKU e nome do produto
- Categoria
- Preço de venda
- Custo unitário
- Quantidade vendida
- Despesa unitária
- Receita total
- Custo total
- Despesas totais
- Lucro estimado
- Margem de lucro
- ROI
- Situação de rentabilidade

### 2. Analise

Apresenta a análise financeira por categoria, com receita, lucro, margem, unidades vendidas e quantidade de produtos. Também identifica os dez produtos com maior lucro estimado.

### 3. Dashboard

Consolida os principais indicadores:

- Receita total
- Custo dos produtos
- Despesas totais
- Lucro estimado
- Margem global
- ROI global
- Quantidade de produtos rentáveis
- Quantidade de produtos com prejuízo
- Unidades vendidas
- Categorias analisadas

Inclui gráficos para comparar receita e lucro por categoria e visualizar o lucro estimado por produto.

## 🧮 Indicadores financeiros

**Lucro estimado**

Lucro = Receita total − Custo total − Despesas totais

**Margem de lucro**

Margem = Lucro estimado ÷ Receita total

**Retorno sobre o investimento (ROI)**

ROI = Lucro estimado ÷ (Custo total + Despesas totais)

Os indicadores de margem e ROI são apresentados em percentual. Quando o denominador é zero, o indicador é considerado zero.

## ⚙️ Como utilizar

1. Crie uma planilha no Google Sheets.
2. Acesse **Extensões → Apps Script**.
3. Insira o código JavaScript do projeto.
4. Salve e execute a função `criarProjeto`.
5. Autorize as permissões solicitadas.
6. Consulte as abas `Produtos`, `Analise` e `Dashboard`.
7. Substitua os dados de demonstração pelos dados dos produtos que deseja analisar.
8. Execute `atualizarProjeto` para recalcular os indicadores e atualizar os gráficos.

**Importante:** a função `criarProjeto` recria as três abas com os dados de demonstração. Depois de inserir seus próprios dados, utilize `atualizarProjeto` para evitar sobrescrevê-los.

## 📈 Resultados esperados

O projeto permite visualizar o desempenho financeiro dos produtos, comparar categorias, identificar oportunidades de melhoria e apoiar decisões comerciais com base nos indicadores calculados.

Os resultados dependem dos preços, custos, despesas e quantidades informados.

## 🚀 Aprendizados

- Manipulação de dados em planilhas.
- Automação com Google Apps Script.
- Programação em JavaScript.
- Cálculo e interpretação de indicadores financeiros.
- Construção de dashboards e gráficos.
- Organização e análise de dados comerciais.

## 🇺🇸 About the Project

This project uses Google Sheets and Google Apps Script to analyze product profitability, calculate financial indicators, and present results in a dashboard.

The solution automates revenue, cost, expense, estimated profit, profit margin, and return on investment (ROI) calculations, making it easier to evaluate commercial performance by product and category.

## 🎯 Objectives

- Automate profitability calculations.
- Identify profitable and loss-making products.
- Compare financial performance across categories.
- Consolidate key indicators into a dashboard.
- Practice spreadsheet automation and data analysis.

## 🛠️ Technologies Used

- Google Sheets
- Google Apps Script
- JavaScript
- Charts and financial indicators

## 📊 Project Structure

### 1. Products

Contains product data, including SKU, product name, category, selling price, unit cost, quantity sold, unit expenses, total revenue, total costs, total expenses, estimated profit, profit margin, ROI, and profitability status.

### 2. Analysis

Provides financial analysis by category, including revenue, profit, margin, units sold, and product count. It also identifies the ten products with the highest estimated profit.

### 3. Dashboard

Displays the main financial indicators, including total revenue, product costs, expenses, estimated profit, overall margin, ROI, profitable products, loss-making products, units sold, and analyzed categories.

The dashboard includes charts comparing revenue and profit by category and estimated profit by product.

## 🧮 Financial Indicators

**Estimated Profit**

Estimated Profit = Total Revenue − Total Costs − Total Expenses

**Profit Margin**

Profit Margin = Estimated Profit ÷ Total Revenue

**Return on Investment (ROI)**

ROI = Estimated Profit ÷ (Total Costs + Total Expenses)

Profit margin and ROI are displayed as percentages. If the denominator is zero, the indicator is set to zero.

## ⚙️ How to Use

1. Create a spreadsheet in Google Sheets.
2. Open **Extensions → Apps Script**.
3. Add the project's JavaScript code.
4. Save and run the `criarProjeto` function.
5. Grant the requested permissions.
6. Explore the `Produtos`, `Analise`, and `Dashboard` sheets.
7. Replace the sample data with the products you want to analyze.
8. Run `atualizarProjeto` to recalculate the indicators and refresh the charts.

**Important:** The `criarProjeto` function recreates the three sheets with sample data. After entering your own data, use `atualizarProjeto` to avoid overwriting it.

## 📈 Expected Results

The project helps users evaluate product financial performance, compare categories, identify improvement opportunities, and support commercial decisions based on calculated indicators.

Results depend on the prices, costs, expenses, and quantities entered.

## 🚀 Skills Developed

- Spreadsheet data manipulation
- Google Apps Script automation
- JavaScript programming
- Financial indicator calculations and interpretation
- Dashboard and chart development
- Commercial data organization and analysis

## 👤 Author

**Vitor**

GitHub: [@vitor1914](https://github.com/vitor1914)

---

🇧🇷 Projeto desenvolvido para fins de estudo e prática em automação de planilhas, programação e análise de dados.

🇺🇸 Project developed for learning and practice in spreadsheet automation, programming, and data analysis.
