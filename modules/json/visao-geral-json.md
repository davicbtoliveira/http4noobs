# Visão Geral do JSON

## Índice

- [Recapitulando o JSON](#recapitulando-o-json)
- [O JSON não é exclusivo do JavaScript](#o-json-não-é-exclusivo-do-javascript)
- [Casos de Uso Mais Comuns](#casos-de-uso-mais-comuns)

## Recapitulando o JSON
O JSON é basicamente uma representação em formato de texto (string) de um objeto JavaScript. É justamente essa característica que o torna perfeito para ser salvo em um arquivo ou enviado em uma requisição HTTP.

###### ***Lembre-se:*** um objeto JavaScript de verdade só existe na memória, dentro das variáveis do seu código enquanto o programa está rodando. Se quisermos enviar esses dados para fora do nosso programa, por exemplo, através da internet em uma requisição HTTP, precisamos transformá-los em texto primeiro. É aí que o JSON entra.

## O JSON não é exclusivo do JavaScript
Só porque o nome significa JavaScript Object Notation, não ache que ele só serve para JavaScript! O JSON é um padrão de mercado universal, reconhecido e suportado por praticamente qualquer linguagem de programação (Python, Go, PHP, Java, C#, etc.).

###### ***Exemplo Prático***: Mesmo que o back-end de uma empresa seja escrito em Go ou C#, ele ainda vai usar o formato JSON para enviar e receber dados do front-end (que roda no client). Ele funciona como uma "língua franca" entre tecnologias diferentes.

## Casos de Uso Mais Comuns
- **No corpo (body) de requisições e respostas HTTP:** Para enviar dados de formulários ou retornar informações de uma API.
- **Arquivos de configuração:** Arquivos com a extensão .json são muito usados para configurar projetos (como o famoso package.json no ecossistema do Node.js).
- **Bancos de dados NoSQL:** Bancos como MongoDB, Elasticsearch e Firestore armazenam seus dados em formatos estruturados baseados ou idênticos ao JSON.
