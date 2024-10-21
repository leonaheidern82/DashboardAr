# Dashboard de Monitoramento da Qualidade do Ar

Este projeto consiste em um dashboard interativo desenvolvido em **Python** usando as bibliotecas **Dash** e **Plotly** para visualização de dados sobre a **qualidade do ar** em municípios do estado de **Minas Gerais**,
extraídos do dataset **MonitorAR** do **Ministério do Meio Ambiente e Mudança do Clima (BRASIL, 2022)**.

## Funcionalidades

O dashboard exibe três gráficos principais, que fornecem insights sobre a qualidade do ar nas regiões monitoradas:
1. **Variação de Monóxido de Carbono (CO) ao longo do dia** para os municípios selecionados.
2. **Índice de Qualidade do Ar (iqar) por município** em Minas Gerais.
3. **Concentração de diferentes poluentes por município**, incluindo PM2.5, NO2, SO2, entre outros.

## Estrutura do Projeto

- `app.py`: Arquivo principal do projeto, contendo o código Python para gerar o dashboard.
- `datasets/monitorar_jul_nov22.xlsx`: Arquivo contendo os dados brutos de monitoramento da qualidade do ar.
- `grafico_poluentes_por_municipio.html`, `grafico_variacao_co.html`, `grafico_qualidadedoar_por_municipio.html`: Gráficos exportados em HTML interativo.
- `README.md`: Este arquivo que documenta o projeto.

## Pré-requisitos

Antes de executar o projeto, você precisará ter instalado os seguintes pacotes Python:

- **Dash**: Para criação do dashboard interativo.
- **Plotly**: Para geração dos gráficos interativos.
- **Pandas**: Para manipulação dos dados.
- **openpyxl**: Para leitura dos arquivos Excel.

Você pode instalar todas as dependências executando o comando:

```bash
pip install dash plotly pandas openpyxl
