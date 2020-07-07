# Google Drive Connector - Full Tutorial


# OAuth no Google

Se você precisa ter seu próprio Google Drive Connector, precisa obter suas chaves de API do GD. Você pode obtê-los no [Google Developers Console](https://console.developers.google.com/apis/library/drive.googleapis.com) .


Imagem

Você pode criar um novo projeto lá e nomeá-lo como desejar:

Imagem

Após criar o projeto, você precisa criar credenciais para o seu projeto.

Use o ID do cliente OAuth .

Imagem

Defina o nome do seu novo aplicativo como desejar.

Imagem

Depois de definir um nome, você pode finalmente criar o ID do cliente Credenciais para OAuth2 . Certifique-se de definir os URIs de redirecionamento autorizado : https://preview.powerbi.com/views/oauthredirect.html

Imagem

Finalmente, você obteve seu precioso ID de cliente e Segredo de cliente . Você copiará e colará esses itens no seu Google Drive Connector.

Imagem


# Obtenha o projeto

Agora você pode fazer o download do arquivo do conector .mez [aqui] (https://github.com/miljunior/PQGoogleSpreadsheet) e substituir appKey e appSecret em PQGoogleSpreadsheet.pq arquivo com os valores que você tem na etapa anterior.

Imagem

Crie o projeto no Visual Studio e copie o arquivo PQGoogleSpreadsheet.mez da bin pasta from para [My Documents]\Microsoft Power BI Desktop\Custom Connectors [1] (https://github.com/Microsoft/DataConnectors/blob/master/docs/m-extensions.md#overview) .

Se tudo correu como deveria, agora você deve poder vê-lo na lista de conectores:

Imagem




