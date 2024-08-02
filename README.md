# Navy Seal Burpees Tracker

## Visão Geral

O **Navy Seal Burpees Tracker** é uma aplicação para monitorar e registrar a quantidade de Navy Seal Burpees (NSBs) realizados. O sistema é baseado em notebooks Jupyter e utiliza arquivos CSV para armazenar e gerenciar os dados.

Os arquivos principais incluem:

- **NSB (ano).ipynb**: Notebooks Jupyter para inserção dos dados diários. Estes notebooks permitem a inserção de dados de NSBs para cada dia do mês e fornecem gráficos mensais detalhados para o ano em questão. Eles geram os arquivos CSV com os totais de NSBs para cada mês do ano.

- **Navy Seal Burpees.ipynb**: Notebook principal que processa os dados dos arquivos CSV gerados e mantém análises comparativas anuais. Ele acessa os arquivos CSV armazenados na pasta `backup` para gerar gráficos e relatórios sobre o desempenho anual.

## Requisitos

- Python 3.x
- Bibliotecas: `pandas`, `matplotlib`, `calendar`, `IPython`, `os`, `shutil`

    ```bash
    pip install pandas matplotlib IPython
    
## Configuração

1. **Clone o Repositório**

   Clone este repositório para o seu ambiente local usando:

   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git

## Uso

-**Inserção e Visualização dos Dados**
Para adicionar dados e visualizar gráficos mensais, abra o notebook correspondente ao ano desejado NSB (ano).ipynb.
Execute as células do notebook para inserir os dados diários e gerar gráficos.

-**Processamento e Análise dos Dados**
Abra o notebook Navy Seal Burpees.ipynb.
Este notebook processa os dados dos arquivos CSV armazenados na pasta backup e gera análises comparativas anuais.

-**Atualização e Backup**
Os dados são salvos e atualizados automaticamente pelos notebooks de inserção.
O sistema faz backup dos arquivos CSV na pasta backup após cada atualização para garantir a integridade dos dados.

-**Caminho para os Dados CSV**
Os caminhos para os arquivos CSV são especificados no código dos notebooks. Certifique-se de atualizar esses caminhos para refletir a localização correta dos arquivos CSV em seu sistema.

Exemplo de como alterar o caminho no código:

    ```bash
    caminho_csv = 'C:\\Seu\\Caminho\\Para\\totais_mensais_2022.csv'
    caminho_backup = 'C:\\Seu\\Caminho\\Para\\backup\\totais_mensais_2022_backup.csv'

    ```bash
    caminho_backup_pasta = 'E:\\Documentos\\Navy-Seal-Burpees\\backup'

