# Sintaxe

## Índice

- [Sintaxe do JSON](#sintaxe-do-json)
- [Tipos de Dados Primitivos](#tipos-de-dados-primitivos)
- [Tipos de Coleções](#tipos-de-coleções)
- [Exemplo Prático de um JSON Válido](#exemplo-prático-de-um-json-válido)



## Sintaxe do JSON

O JSON (JavaScript Object Notation) é um formato padrão para organizar e representar dados. Ele foi baseado na sintaxe de objetos do JavaScript, mas hoje é independente e virou o padrão da indústria. A sua principal função no desenvolvimento web é transmitir dados entre aplicações através do protocolo HTTP (como o envio de dados do servidor para o navegador).

###### ***Nota***: Por exemplo, a grande maioria das requisições HTTP que fazemos para APIs na web nos devolve dados formatados em JSON.

## Tipos de Dados Primitivos
O JSON suporta os seguintes tipos de dados básicos:

- Strings (Textos): Sempre entre aspas duplas. `Ex: "Olá, Mundo!"`
- Numbers (Números): Inteiros ou com ponto flutuante. `Ex: 42 ou 3.14`
- Booleans (Booleanos): Valores lógicos. `Ex: true ou false`
- Null (Nulo): Representa a ausência de valor. `Ex: null`

## Tipos de Coleções
Para estruturar dados mais complexos, usamos:

- Arrays (Listas): Uma lista ordenada de valores separados por vírgula e envolvida por colchetes. `Ex: [1, 2, 3]`
- Objetos: Uma coleção de pares de "chave": "valor" envolvida por chaves. `Ex: {"chave": "valor"}`

O formato JSON é extremamente parecido com os objetos do JavaScript e com os dicionários do Python. A regra de ouro aqui é: as chaves sempre devem ser strings (entre aspas duplas), e os valores podem ser de qualquer tipo de dado permitido, inclusive outros objetos ou listas aninhadas.

## Exemplo Prático de um JSON Válido

```json
{
    "filmes": [
        {
            "id": 1,
            "titulo": "Homem de Ferro",
            "diretor": "Jon Favreau",
            "favorito": true
        },
        {
            "id": 2,
            "titulo": "Os Vingadores",
            "diretor": "Joss Whedon",
            "favorito": false
        }
    ]
}
```
