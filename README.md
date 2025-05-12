# 🛒 Alura Store - Análise de Vendas

Este projeto consiste em uma análise exploratória dos dados de vendas de quatro lojas fictícias da Alura Store. A proposta é identificar padrões de compra, desempenho por loja e fornecer recomendações estratégicas para tomada de decisão, como qual loja apresenta pior desempenho e pode ser vendida.

## 📌 Propósito da Análise

O objetivo principal desta análise é fornecer **insights relevantes sobre o desempenho financeiro e operacional** das lojas da Alura Store. A partir desses dados, foi possível:

- Avaliar o faturamento total de cada loja.
- Verificar quais categorias de produtos têm maior volume de vendas.
- Calcular a média de avaliação dos clientes por loja.
- Identificar os produtos mais e menos vendidos.
- Comparar o custo médio de frete entre as lojas.
- Recomendar a venda da loja com menor desempenho financeiro.

## 🗂 Estrutura do Projeto

```
alura-store-analysis/
│
├── data/
│   ├── loja_1.csv
│   ├── loja_2.csv
│   ├── loja_3.csv
│   └── loja_4.csv
│
├── notebooks/
│   └── alura_store_analise.ipynb   # Notebook principal com toda a análise
│
├── images/
│   ├── faturamento_por_loja.png
│   ├── vendas_por_categoria.png
│   ├── media_avaliacao_lojas.png
│   ├── produtos_mais_vendidos.png
│   ├── produtos_menos_vendidos.png
│   └── frete_medio_por_loja.png
│
├── README.md
└── relatorio_final.pdf             # Relatório final com recomendações
```

## 📊 Exemplos de Gráficos e Insights

### 🔸 Faturamento por Loja
![Faturamento por Loja](images/faturamento_por_loja.png)

> **Insight:** A Loja 1 apresenta o maior faturamento, enquanto a Loja 4 tem o menor desempenho financeiro.

### 🔸 Vendas por Categoria
![Vendas por Categoria](images/vendas_por_categoria.png)

> **Insight:** A categoria "móveis" lidera as vendas, seguida de "eletrônicos" e "brinquedos".

### 🔸 Média de Avaliação das Lojas
![Média de Avaliação](images/media_avaliacao_lojas.png)

> **Insight:** A Loja 3 possui a melhor média de avaliação (4.05), indicando maior satisfação do cliente.

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/alura-store-analysis.git
cd alura-store-analysis
```

### 2. Instale as dependências

Certifique-se de ter o Python 3.9+ instalado. Em seguida, instale as bibliotecas necessárias:

```bash
pip install pandas matplotlib seaborn
```

### 3. Execute o Jupyter Notebook

```bash
jupyter notebook notebooks/alura_store_analise.ipynb
```

### 4. Visualize os gráficos e o relatório

Todos os gráficos gerados serão exibidos no notebook e salvos na pasta `images/`. O relatório final pode ser encontrado em `relatorio_final.pdf`.

## 📚 Conclusão

O projeto oferece uma visão clara e fundamentada sobre o desempenho de cada loja. A análise aponta a **Loja 4 como a menos rentável**, sendo a principal candidata à venda. Essa abordagem orientada por dados auxilia na **tomada de decisões estratégicas mais seguras e lucrativas**.

---

Desenvolvido como parte do desafio de Data Science da Alura.
