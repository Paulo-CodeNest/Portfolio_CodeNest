# CodeNest - Análise Executiva de Vendas

Projeto de análise de vendas utilizando Python e Jupyter Notebook.  
O objetivo é gerar insights estratégicos e relatórios executivos a partir dos dados de vendas.

## Estrutura do Projeto
CodeNest-Portfolio/
│
├── dados/
│ └── Dados_Organizados_Vendas_CodeNest.xlsx
├── outputs/
│ └── Resumo_Vendas_CodeNest.pdf
├── Analise_Vendas_Executivo.ipynb
├── requirements.txt
└── README.md

## Funcionalidades

- Identificação do produto mais vendido
- Produto mais rentável
- Província com mais vendas
- Cliente que mais comprou
- Cálculo da receita total
- Criação de DataFrame resumo
- Geração automática de PDF executivo
- Exportação dos dados para Excel atualizado

## Tecnologias Utilizadas

- Python
- Pandas
- FPDF (geração de PDF)
- OpenPyXL (Excel)
- Tabulate
- Jupyter Notebook

## Como Executar

1. Instale as dependências:

```bash
pip install -r requirements.txt

2. Abra o Notebook:
jupyter notebook

3.Execute todas as células (Run All)
4. O PDF executivo será gerado automaticamente na pasta outputs/
5. O Excel atualizado será salvo na pasta dados/

Resultado Esperado:

PDF com resumo executivo contendo todos os KPIs
Excel atualizado com todos os dados de vendas



