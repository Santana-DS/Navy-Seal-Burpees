# Navy Seal Burpees Tracker

## Visão Geral

O **Navy Seal Burpees Tracker** é uma aplicação para monitorar e registrar a quantidade de Navy Seal Burpees (NSBs) realizados. O sistema é baseado em notebooks Jupyter e utiliza arquivos CSV para armazenar e gerenciar os dados.

Os arquivos principais incluem:

**NSB (ano).ipynb**:

Notebooks Jupyter para inserção dos dados diários. Estes notebooks permitem a inserção de dados de NSBs para cada dia do mês e fornecem gráficos mensais. Eles geram os arquivos CSV com os totais de NSBs para cada mês do ano.

**Navy Seal Burpees.ipynb**:

Notebook principal que processa os dados dos arquivos CSV gerados e mantém análises comparativas anuais. Ele acessa os arquivos CSV armazenados na pasta `backup` para gerar gráficos e relatórios sobre o desempenho anual.

## Requisitos

- Python 3.x
- Bibliotecas: `pandas`, `matplotlib`, `calendar`, `IPython`, `os`, `shutil`

    ```bash
    pip install pandas matplotlib IPython
   ```
  
## Configuração

1. **Clone o Repositório**

   Clone este repositório para o seu ambiente local usando:

   ```bash
   git clone https://github.com/Santana-DS/Navy-Seal-Burpees
   ```
   
## Uso
**Para abrir o notebook Jupyter**

   ```bash
   python -m notebook
   ```

**Inserção e Visualização dos Dados**

Para adicionar dados e visualizar gráficos mensais, abra o notebook correspondente ao ano desejado NSB (ano).ipynb.
Execute as células do notebook para inserir os dados diários e gerar gráficos.

**Processamento e Análise dos Dados**

Abra o notebook Navy Seal Burpees.ipynb.
Este notebook processa os dados dos arquivos CSV armazenados na pasta backup e gera análises comparativas anuais.

**Atualização e Backup**

Os dados são salvos e atualizados automaticamente pelos notebooks de inserção. Os caminhos para os arquivos CSV são especificados por caminhos relativos com base no diretório atual
