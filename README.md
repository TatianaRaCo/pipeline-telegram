# pipeline-telegram
Pipeline de Dados do Telegram feito na AWS (Amazon Web Services)

![01-pipeline_img](https://github.com/TatianaRaCo/pipeline-telegram/assets/125712040/98f3b733-581e-4464-8f2d-b805ba399454)

Este projeto é um exemplo de análise de dados em big data na nuvem e tem como objetivo coletar, refinar e analisar de dados provenientes do aplicativo de mensagens Telegram utilizando os serviços da Amazon Web Services

Dentro do projeto é demonstrado: <br>
O uso da API do Telegram para coletar os dados do aplicativo de mensagens. <br>
A obtenção de um token de autenticação para interagir com a API usando a biblioteca requests em Python. <br>
A extração dos dados relevantes de cada mensagem, salvando-os em um novo arquivo JSON. <br>
O uso da biblioteca pyarrow para criar uma tabela a partir dos dados processados. <br>
A utilização da biblioteca boto3 para interagir com o S3 e carregar os arquivos JSON. <br>
A criação de camadas para utilizar o pacote PyArrow no Lambda. <br>
A adição de informações relevantes, como data e hora de recebimento da mensagem. <br>


