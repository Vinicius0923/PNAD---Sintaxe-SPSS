## PNADC – Sintaxe-SPSS

## 📊 PNADC – Microdados

Este repositório contém os **microdados da PNAD Contínua (PNADC)** referentes ao ano de 2025, organizados em formato **SPSS Syntax (`GET DATA`)** para leitura dos arquivos de texto fixos disponibilizados pelo IBGE.
---

## 📂 Estrutura dos Arquivos

- **Arquivo de dados**: `PNADC_022025.TXT`  
  Contém os microdados em formato texto, com posições fixas.

- **Arquivo de sintaxe**: `GET DATA.txt`  
  Script SPSS para importar os microdados, definindo variáveis, posições e rótulos.
---

## ⚙️ Como usar

1. Abra o **SPSS** ou outro software compatível.
2. Carregue o arquivo `GET DATA.txt`.
3. Ajuste o caminho do arquivo de dados (`PNADC_022025.TXT`) conforme a sua máquina.
4. Execute o script para importar os microdados com todas as variáveis e rótulos.
---

## 🧾 Principais Variáveis

| Variável | Descrição |
|----------|------------|
| Ano      | Ano de referência |
| Trimestre | Trimestre da coleta |
| UF       | Unidade da Federação |
| Capital  | Município da capital |
| Estrato / UPA | Identificação amostral |
| V2009    | Idade do morador |
| V2010    | Cor ou raça |
| V3001–V3014 | Escolaridade e frequência escolar |
| V4001–V4082 | Condição de trabalho e ocupação |
| VD3004–VD3006 | Nível de instrução padronizado |
| VD4001–VD4037 | Condição na força de trabalho, ocupação e rendimento |

> O arquivo contém centenas de variáveis adicionais, todas já rotuladas no script.
---

## 📑 Documentação

- As variáveis seguem a **metodologia oficial da PNAD Contínua**.  
- Para detalhes sobre questionário, conceitos e classificações, consulte o [site do IBGE](https://www.ibge.gov.br/estatisticas/sociais/trabalho/9173-pnad-continua.html).
---

## 🚀 Objetivo

Este material facilita a **importação e análise dos microdados da PNADC** em softwares estatísticos, permitindo estudos sobre:

- Mercado de trabalho  
- Educação  
- Rendimento  
- Estrutura domiciliar  
---

## 📌 Observações

- Os microdados são de uso público, mas exigem conhecimento estatístico para interpretação.  
- Recomenda-se aplicar os **pesos amostrais (V1027, V1028, etc.)** para análises representativas.  
- O comando `SAVE OUTFILE` no final do script indica onde os dados serão salvos após a importação.
---
