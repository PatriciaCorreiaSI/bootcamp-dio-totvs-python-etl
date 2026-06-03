# 🪙 Geração de Notícias Bancárias com IA
### Bootcamp DIO e Totvs | Explorando IA Generativa em um Pipeline de ETL com Python

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-0288D1?style=for-the-badge&logoColor=white)

Este projeto demonstra a extração e transformação de dados de clientes bancários, seguida pela geração de notícias personalizadas usando a API do Google Gemini, e a atualização desses dados em um arquivo CSV.

## 👩‍💻 Funcionalidades

*   **Extração de Dados:** Carrega dados de clientes de um arquivo CSV (`users_bank.csv`).
*   **Transformação de Dados:** Prepara os dados do cliente para a geração de conteúdo.
*   **Geração de Notícias Personalizadas:** Utiliza a API do Google Gemini para criar mensagens de marketing personalizadas para cada cliente.
*   **Atualização de Dados:** Integra as notícias geradas de volta ao `DataFrame` original e salva o `DataFrame` atualizado em um arquivo CSV.

## ▶️ Como Executar o Projeto

1.  **Configuração da API Key:**
    *   Crie uma chave de API para o Google Gemini no [Google AI Studio](https://aistudio.google.com/).
    *   No Google Colab, abra o painel de "Secrets" (ícone de chave 🔑 no lado esquerdo).
    *   Adicione sua chave de API com o nome `BOOTCAMP_DIO`.

2.  **Preparação do Ambiente:**
    *   Certifique-se de que o arquivo `users_bank.csv` esteja presente no ambiente do Colab.

3.  **Execução das Células:**
    *   Execute todas as células do notebook sequencialmente. O notebook está estruturado para processar os dados em etapas: `EXTRAÇÃO`, `TRANSFORMAÇÃO`, `GERAÇÃO DE NOTÍCIAS` e `CARREGAMENTO`.

## 🤖 Tecnologias Utilizadas

*   ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) **Python 3**
*   ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) **Pandas:** Para manipulação e análise de dados.
*   ![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) **Google Generative AI (Gemini API):** Para a geração de conteúdo textual.
*   ![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white) **Google Colab:** Ambiente de desenvolvimento.

## 📍 Observações

*   Este projeto utiliza um modelo do Google Gemini (`gemini-2.5-flash`). Limites de cota da API podem ser encontrados na documentação do Google Gemini.
*   A chave de API é gerenciada de forma segura através do Secrets Manager do Colab e não é exposta diretamente no código-fonte.



Autor do projeto: Patricia Correia
Colaboração de comentários e README: Google Gemini
