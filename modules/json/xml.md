# O que é o XML

## Índice

- [Introdução ao XML](#introdução-ao-xml)
- [Sintaxe do XML](#sintaxe-do-xml)
- [Comparação Prática: XML vs JSON](#comparação-prática-xml-vs-json)

## Introdução ao XML
Não dá para falar de JSON sem citar o XML. O **XML** (*Extensible Markup Language*, ou Linguagem de Marcação Extensível) é um formato baseado em texto para representar informações estruturadas. No fundo, ele serve para o mesmo propósito do JSON, mas tem uma estrutura diferente e costuma ser bem mais **verboso** (ou seja, exige muito mais texto e caracteres para transmitir a mesma informação).

###### ***Contexto Histórico:*** Antes do JSON dominar o desenvolvimento web e as APIs modernas, o XML era o padrão absoluto para transmissão de dados na internet. Hoje em dia, ele ainda é muito utilizado em sistemas mais antigos, configurações de softwares (como no Android) e na estrutura de Notas Fiscais Eletrônicas (NF-e) aqui no Brasil.

## Sintaxe do XML
O XML é uma linguagem de marcação estruturada de forma muito parecida com o HTML que usamos no front-end. A grande diferença é que o XML é genérico: ele **não possui tags pré-definidas** (como `<h1>`, `<p>` ou `<div>`). 

Assim como no JSON você pode inventar o nome das suas chaves, no XML você é quem cria o nome das tags de acordo com a sua necessidade.

## Comparação Prática: XML vs JSON

Veja abaixo como o mesmo dado é representado nas duas linguagens, para entender a diferença de peso e leitura de cada uma:

### Representação em XML
```xml
<root>
  <id>1</id>
  <genre>Action</genre>
  <title>Iron Man</title>
  <director>Jon Favreau</director>
</root>
```

### O mesmo em JSON
```json
{
  "id": "1",
  "genre": "Action",
  "title": "Iron Man",
  "director": "Jon Favreau"
}
```
