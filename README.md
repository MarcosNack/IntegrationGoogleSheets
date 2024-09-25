# Integração com Google Sheets
Este script realiza a integração com o Google Sheets para automatizar a extração, tratamento de dados e geração de gráficos. Utilizando as bibliotecas google-api-python-client, google-auth-httplib2, google-auth-oauthlib, pandas e matplotlib, o script acessa as planilhas do Google Sheets, manipula os dados e gera visualizações de forma eficiente.

Funcionalidades:
* Autenticação via API do Google: O script utiliza as credenciais OAuth2 para garantir acesso seguro às planilhas.
* Leitura e escrita em planilhas: Os dados são lidos e atualizados diretamente no Google Sheets.
* Tratamento de dados: O script faz operações de limpeza, transformação e agregação nos dados importados.
* Geração de gráficos: Com os dados tratados, o script utiliza bibliotecas de visualização para criar gráficos.

Requisitos:
* google-api-python-client: Biblioteca para acessar a API do Google.
* google-auth-httplib2: Gerenciamento de autenticação OAuth2.
* google-auth-oauthlib: Fluxo de autenticação OAuth2 para aplicativos desktop.
* matplotlib/plotly: Para criação de gráficos.

Como utilizar:
1. Instale as dependências:

> pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib matplotlib pandas

2. Autentique-se no Google API e configure o arquivo token.json com as credenciais OAuth.
3. Execute o script para tratar os dados e gerar gráficos.

Resultado:

![image](https://github.com/user-attachments/assets/b191d3c2-e979-4799-9131-1872ae4b4251)
