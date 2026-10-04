# 📍 Consulta de CEP via API com Python

Aplicação em Python para consulta de endereço a partir de CEP, utilizando integração com serviço externo.

## Objetivo

Demonstrar consumo de API REST, tratamento de respostas JSON e validação de entrada em um fluxo simples e próximo de rotinas cadastrais reais.

## Funcionalidades

- Consulta de endereço por CEP
- Validação básica do formato informado
- Consumo de API externa
- Tratamento de CEP inexistente
- Tratamento de falhas de comunicação
- Exibição estruturada dos dados retornados

## Fluxo da aplicação

1. Usuário informa o CEP.
2. A aplicação valida o formato.
3. É realizada uma requisição HTTP.
4. A resposta JSON é processada.
5. Os dados de endereço são apresentados.

## Competências demonstradas

- Integração com serviços externos
- Requisições HTTP
- Manipulação de JSON
- Tratamento de exceções
- Validação de entrada
- Separação de fluxo em funções
- Diagnóstico básico de falha de comunicação
- Leitura de resposta de serviço externo

## Visão para Operações de TI

Este projeto se conecta diretamente com atividades de suporte e operações porque exige entender requisição, resposta, erro, indisponibilidade e validação de dados.

### Como eu investigaria uma falha

1. Validaria o dado informado pelo usuário.
2. Confirmaria conectividade com o serviço externo.
3. Verificaria o código de resposta HTTP.
4. Analisaria o JSON retornado.
5. Separaria erro de entrada, erro da aplicação e indisponibilidade externa.

## Como explicar em entrevista

> "Esse projeto trabalha com um fluxo real de integração. Se a consulta falha, eu preciso descobrir se o problema está no dado informado, na conexão, na API externa ou no tratamento da resposta. Esse raciocínio de diagnóstico é o que quero levar para uma função operacional de TI."
- Diagnóstico básico de falha de comunicação
- Leitura de resposta de serviço externo
- Tratamento de cenário inválido para o usuário

## Visão para Operações de TI

Este projeto se conecta diretamente com atividades de suporte e operações porque exige entender **requisição, resposta, erro, indisponibilidade e validação de dados**.

### Como eu investigaria uma falha

1. Validaria o dado informado pelo usuário.
2. Confirmaria conectividade com o serviço externo.
3. Verificaria o código de resposta HTTP.
4. Analisaria o JSON retornado.
5. Separaria erro de entrada, erro da aplicação e indisponibilidade externa.
6. Registraria a causa e a ação tomada.

## Como explicar em entrevista

> "Esse projeto é simples, mas é muito útil para suporte e operações porque trabalha com um fluxo real de integração. Se a consulta falha, eu preciso descobrir se o problema está no dado informado, na conexão, na API externa ou no tratamento da resposta. Esse raciocínio de diagnóstico é o que quero levar para uma função operacional de TI."

## Tecnologias

**Python** • **requests** • **ViaCEP** • **JSON**

## Aplicação em contexto de negócio

Consultas de endereço são comuns em processos de **cadastro de clientes, onboarding, validação de dados e operações comerciais**. O projeto mostra como uma informação externa pode ser incorporada a um fluxo operacional.

## Próximas evoluções

- Validação mais robusta
- Interface gráfica ou web
- Cache de consultas
- Persistência de dados
- Testes automatizados
- Integração com cadastro de clientes

## Autor

**Daniel Fernando Martins**
