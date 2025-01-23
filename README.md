# ai-900-lab4
 arquivos para entrega do quarto lab de certificação AI-900 da Microsoft.

### Azure Cognitive Search + Sentiment Analysis

## Como Configurar?
    1. Pelo marketplace instalar o AI Search e o AI Services
    2. Criar um novo storage account
    3. Configurar esse storage account para usuários anônimos conseguirem consultar o blob
    4. Criar um blob com os arquivos que serão consultados
    5. Cirar um novo container habilitado para receber acessos anônimos apontando para o blob novo
    6. Configurar e rodar o AI Cognitive Search no container

## Insights e próximos passos
    Acredito que esse tipo de automação facilita a criação de um banco de dados.
    Como exemplo sugerido, uma tabela com todas essas reviews de restaurantes possibilita a criar um score geral dos restaurantes e começar a cruzar outras características, como por exemplo capacidade, localidade, cardápio, etc, e utilizar o review de analise de sentimento  do cognitive search como variável categórica binária para predição de, por exemplo, probabilidade de um restaurante ter sucesso antes de abrir baseado nessas características e reviews reais de usuários.
