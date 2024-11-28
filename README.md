Projeto baseado no bootcamp da DIO sobre a certificação AI-102 da Microsoft

Necessário adicionar os parâmetros de configuração do Azure Blob Storage e Document Intelligence do Azure.

Criar um arquivo .env na raiz do projeto com os parâmetros:

Variável / Significado
ENDPOINT = Ponto de extremidade do Document Intelligence criado no Azure Portal
SUBSCRIPTION_KEY = Chave do Document Intelligence
AZURE_STORAGE_CONNECTION_STRING = String de conexão do Azure Blob Storage criado no Azure Portal
CONTAINER_NAME = Nome do container criado no Azure Blob Storage



Exemplo:



ENDPOINT = "https://doc-dio-fraude.cognitiveservices.azure.com/"
SUBSCRIPTION_KEY = ""
AZURE_STORAGE_CONNECTION_STRING = ""
CONTAINER_NAME = "cartoes"
