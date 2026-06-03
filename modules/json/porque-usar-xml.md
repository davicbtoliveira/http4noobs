# Por que usar XML?

## Índice

- [JSON vs XML: Qual escolher?](#json-vs-xml-qual-escolher)
- [Por que o JSON costuma vencer?](#por-que-o-json-costuma-vencer)
- [Quando o XML ainda é usado?](#quando-o-xml-ainda-é-usado)

## JSON vs XML: Qual escolher?
Tanto o XML quanto o JSON servem para resolver o mesmo problema, então qual deles você deve escolher no seu projeto? 

Antigamente, o XML era usado exatamente para as mesmas tarefas que o JSON domina hoje. Arquivos de configuração, corpo de requisições HTTP (`body`) e qualquer outro tipo de transferência de dados funcionam perfeitamente com ambos. 

###### ***A Regra Geral:*** Sendo bem direto: se o JSON atende aos requisitos do seu projeto, você deve sempre dar preferência a ele em vez do XML.

## Por que o JSON costuma vencer?
O JSON se tornou o padrão favorito da comunidade e da indústria por três motivos principais:
- **Mais leve:** Como não precisa de tags repetitivas para abrir e fechar elementos, o arquivo final é menor e consome menos banda de rede.
- **Mais fácil de ler:** A sintaxe é muito mais limpa e visualmente agradável para nós, seres humanos.
- **Melhor ecossistema:** Praticamente qualquer linguagem de programação moderna lê e gera JSON de forma nativa e extremamente rápida, sem precisar instalar bibliotecas complexas.

## Quando o XML ainda é usado?
Existem casos específicos onde o XML ainda é a melhor escolha, ou até mesmo obrigatório, mas isso hoje em dia costuma ser a exceção, e não a regra. 

###### ***Exemplo no Brasil:*** O maior exemplo prático de uso de XML no nosso dia a dia dev no Brasil é a **NF-e (Nota Fiscal Eletrônica)**. O governo brasileiro padronizou o formato de emissão e recepção de notas fiscais usando XML por questões de validação de assinaturas digitais e esquemas rígidos de segurança que o formato oferece. Se você for trabalhar com sistemas financeiros ou de faturamento por aqui, com certeza vai trombar com ele!
