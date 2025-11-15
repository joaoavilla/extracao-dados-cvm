# Extracao-dados-cvm

Repositório dedicado à extração e compilação dos dados DFP (Demonstrações Financeiras Padronizadas) das companhias abertas disponibilizadas pela CVM.

## Objetivo do Projeto

O propósito deste repositório é oferecer uma forma transparente, reprodutível e acessível de obter, tratar e analisar os demonstrativos financeiros completos das companhias abertas brasileiras, diretamente da fonte oficial (CVM), sem depender de:

  * plataformas pagas,

  * agregadores de dados privados,

  * APIs instáveis ou documentações incompletas.

A proposta é permitir que qualquer usuário gere sua própria base histórica de demonstrativos contábeis (2010–2024), de forma padronizada e consistente, sem intermediários.

## Como utilizar

> * O notebook principal realiza automaticamente o download, leitura, tratamento e exportação dos demonstrativos DFP.
> * A execução ocorre diretamente no Google Colab, em qualquer dispositivo, sem necessidade de instalar Python, bibliotecas ou ferramentas adicionais.
> * Ao final, o usuário pode baixar um conjunto completo de arquivos .csv contendo os demonstrativos tratados (DRE, BPA, BPP, DFC_MI, DFC_MD).
> * Os arquivos podem ser analisados no próprio Colab ou exportados para Excel, Google Sheets, R, Python ou qualquer outra ferramenta de análise.


## ▶️ Executar no Google Colab

Clique abaixo para abrir o notebook automaticamente no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joaoavilla/extracao-dados-cvm/blob/main/notebooks/extracao_dados_cvm.ipynb)

