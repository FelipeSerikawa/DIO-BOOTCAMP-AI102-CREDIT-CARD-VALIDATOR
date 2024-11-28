Projeto baseado no bootcamp da DIO sobre a certificação AI-102 da Microsoft <br>

Necessário adicionar os parâmetros de configuração do Azure Blob Storage e Document Intelligence do Azure. <br>

Criar um arquivo .env na raiz do projeto com os parâmetros: <br>

Variável / Significado <br>
ENDPOINT = Ponto de extremidade do Document Intelligence criado no Azure Portal <br>
SUBSCRIPTION_KEY = Chave do Document Intelligence <br>
AZURE_STORAGE_CONNECTION_STRING = String de conexão do Azure Blob Storage criado no Azure Portal <br>
CONTAINER_NAME = Nome do container criado no Azure Blob Storage <br>



Exemplo:



ENDPOINT = "https://doc-dio-fraude.cognitiveservices.azure.com/" <br>
SUBSCRIPTION_KEY = "" <br>
AZURE_STORAGE_CONNECTION_STRING = "" <br>
CONTAINER_NAME = "cartoes" <br>
