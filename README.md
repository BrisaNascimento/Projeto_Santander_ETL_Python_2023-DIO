# Projeto_Santander_ETL_Python_2023-DIO

Esse projeto é uma aplicação do projeto desenvolvido pela DIO em parceria com o Santander que visa a construção de um pipeline ETL com python explorando recursos da IA generativa do GPT-3.5 turbo. O projeto possui as etapas a seguir:
1 - extração de IDs de usuários de um arquivo csv;
2 - transformação com a IA da OpenAI (GPT-3.5 - turbo);
3 - carregamento dos dados transformados de volta a API original do 'Santander Dev Week 2023'.

Para isso foi utilizada a API pré concebida no Swagger para a 'Santander Dev Week 2023' e toda a orientação e condução do professor Venilton. A documentação pode ser encontrada em:
https://github.com/digitalinnovationone/santander-dev-week-2023-api

Instruções do projeto obtidas no Santander Bootcamp 2023 - Ciência de Dados com Python (DIO):

Contexto: Você é um cientista de dados no Santander e recebeu a tarefa de envolver seus clientes de maneira mais personalizada. Seu objetivo é usar o poder da IA Generativa para criar mensagens de marketing personalizadas que serão entregues a cada cliente.

Condições do Problema:

Você recebeu uma planilha simples, em formato CSV ('SDW2023.csv'), com uma lista de IDs de usuário do banco.
Seu trabalho é consumir o endpoint GET https://sdw-2023-prd.up.railway.app/users/{id} (API da Santander Dev Week 2023) para obter os dados de cada cliente.
Depois de obter os dados dos clientes, você vai usar a API do ChatGPT (OpenAI) para gerar uma mensagem de marketing personalizada para cada cliente. Essa mensagem deve enfatizar a importância dos investimentos.
Uma vez que a mensagem para cada cliente esteja pronta, você vai enviar essas informações de volta para a API, atualizando a lista de "news" de cada usuário usando o endpoint PUT https://sdw-2023-prd.up.railway.app/users/{id}.

# Repositório da API: https://github.com/digitalinnovationone/santander-dev-week-2023-api
# Documentação API OpenIA: https://platform.openai.com/docs/api-reference/introduction
# API Swagger: https://sdw-2023-prd.up.railway.app/users/{id}
