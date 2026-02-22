# Projeto Portfolio CodeNest - Análise de Vendas

Projeto de análise de vendas utilizando Python e Jupyter Notebook.  
O objetivo é analisar vendas, receita por categoria, produtos e províncias, além de gerar relatórios automáticos em PDF e Excel.

## Estrutura do Projeto
CodeNest-Portfolio2/
│
├── dados/
│ └── bu_mz.csv
├── outputs/
│ ├── Resumo_CodeNest.pdf
│ └── maior_1.xlsx
├── Analise_Vendas.ipynb
├── requirements.txt
└── README.md

## Funcionalidades

- Limpeza e organização de dados
- Cálculo de receita total e média
- Ranking de produtos e províncias
- Análise por categoria (ex.: Eletrônicos)
- Filtragem de vendas com quantidade > 1
- Análise de métodos de pagamento
- Geração de resumo em PDF
- Exportação de dados filtrados para Excel

## Tecnologias Utilizadas

- Python
- Pandas
- FPDF (geração de PDF)
- OpenPyXL (Excel)
- Jupyter Notebook

## Como Executar

1. Instale as dependências:

```bash
pip install -r requirements.txt

2. Abra o Notebook:
jupyter notebook

3. Execute todas as células (Run All)
4. Os arquivos PDF e Excel serão gerados automaticamente na pasta outputs/.


Resultado Esperado

PDF: resumo com total de vendas, média e total de vendas
Excel: todas as vendas com quantidade maior que 1
