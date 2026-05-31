## Como executar

  ### Opção 1 — Google Colab (recomendado, sem instalação)

  Clique no badge abaixo para abrir o notebook diretamente no Colab. Não é necessário instalar Python,
  bibliotecas ou ferramentas.

  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joaoavilla/extracao-dados-cvm/blob/main/notebooks/extracao_dados_cvm.ipynb) 

  Execute cada célula em ordem com **Shift + Enter**. Ao final, um arquivo `.zip` com todos os CSVs será
  disponibilizado para download.

  ### Opção 2 — Localmente (Jupyter)

  Requer Python 3.9+ instalado.

  ```bash
  # 1. Clonar o repositório
  git clone https://github.com/joaoavilla/extracao-dados-cvm.git
  cd extracao-dados-cvm

  # 2. Instalar dependências
  pip install -r requirements.txt

  # 3. Abrir o notebook
  jupyter notebook notebooks/extracao_dados_cvm.ipynb

  Os dados serão salvos em data_raw/ (ZIPs originais da CVM) e data_processed/ (CSVs tratados).

  ---
  O que o notebook produz

  ┌──────────────────────┬──────────────────────────────────────────────────┐
  │    Arquivo gerado    │                     Conteúdo                     │
  ├──────────────────────┼──────────────────────────────────────────────────┤
  │ dre_2010_2024.csv    │ Demonstração do Resultado do Exercício           │
  ├──────────────────────┼──────────────────────────────────────────────────┤
  │ bpa_2010_2024.csv    │ Balanço Patrimonial Ativo                        │
  ├──────────────────────┼──────────────────────────────────────────────────┤
  │ bpp_2010_2024.csv    │ Balanço Patrimonial Passivo                      │
  ├──────────────────────┼──────────────────────────────────────────────────┤
  │ dfc_mi_2010_2024.csv │ Demonstração do Fluxo de Caixa (Método Indireto) │
  ├──────────────────────┼──────────────────────────────────────────────────┤
  │ dfc_md_2010_2024.csv │ Demonstração do Fluxo de Caixa (Método Direto)   │
  └──────────────────────┴──────────────────────────────────────────────────┘

  Cobertura: 730 companhias abertas, período 2010–2024.

  ---
  Fonte dos dados

  Portal de Dados Abertos da CVM (https://dados.cvm.gov.br/dados/CIA_ABERTA/DOC/DFP/DADOS/)

