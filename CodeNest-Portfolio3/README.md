# Análise de Estoque com Python

Projeto de análise de dados utilizando Python e Jupyter Notebook.  
O objetivo é analisar vendas diárias, comparar estoque atual com estoque ideal e gerar KPIs, gráficos e relatório em PDF automaticamente.

## Estrutura do Projeto
CodeNest-porfolio3/
│
├── dados/
│ └── vendas_estoque.csv
├── outputs/ # Aqui são gerados gráficos e PDFs
│
├── Analise_Estoque.ipynb
├── requirements.txt
└── README.md


## Funcionalidades

- Limpeza de dados (remoção de duplicados)
- Cálculo da necessidade de reposição
- Classificação de produtos (Crítico, Atenção, Normal)
- KPIs gerais (total de vendas, média de vendas, produtos críticos)
- Ranking de produtos mais vendidos
- Gráficos comparativos: Estoque Atual vs Estoque Ideal
- Geração automática de relatório em PDF com gráficos e KPIs

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- NumPy
- ReportLab
- Jupyter Notebook

## Como Executar

1. Instale as dependências:

```bash
pip install -r requirements.txt

2. Abra o Notebook:
jupyter notebook

3. Execute todas as células do notebook (Run All)
4. O relatório em PDF será gerado na pasta outputs/ junto com o gráfico

Observações
Mantenha o arquivo vendas_estoque.csv na pasta dados/
A pasta outputs/ será criada automaticamente caso não exista
O PDF final contém KPIs, ranking de produtos e gráfico de comparação de estoque

Resultado Esperado

O relatório em PDF terá:

Título: RELATÓRIO DE ANÁLISE DE ESTOQUE
KPIs: total de vendas, média diária, produtos críticos
Ranking: produto mais e menos vendido
Gráfico: Estoque Atual vs Estoque Ideal com legenda das cores