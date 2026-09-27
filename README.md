# Consulta de CEP com API em Python

Aplicação desenvolvida em Python para consultar endereços a partir de um CEP utilizando integração com uma API externa.

O usuário informa um CEP e o sistema retorna informações como logradouro, bairro, cidade e estado.

## Funcionalidades

- Consulta de endereço por CEP
- Validação básica do CEP informado
- Integração com API externa
- Tratamento de CEP inexistente
- Tratamento de falhas de comunicação
- Exibição organizada dos dados retornados

## Conceitos aplicados

- Python
- Funções
- Estruturas condicionais
- Loops
- Manipulação de strings
- Requisições HTTP
- Consumo de API externa
- JSON
- Tratamento de exceções

## Tecnologias utilizadas

- Python
- Biblioteca `requests`
- API ViaCEP
- Google Colab
- GitHub

## Como funciona

1. O usuário informa um CEP.
2. O sistema valida se o CEP possui 8 dígitos.
3. A aplicação realiza uma requisição para a API ViaCEP.
4. A resposta é recebida em formato JSON.
5. Os dados são processados e exibidos ao usuário.

## Exemplo de uso

```text
Digite o CEP somente com números: 01001000

=== ENDEREÇO ENCONTRADO ===
CEP: 01001-000
Logradouro: Praça da Sé
Bairro: Sé
Cidade: São Paulo
Estado: SP
