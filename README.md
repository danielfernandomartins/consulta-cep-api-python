# 📍 Consulta de CEP via API com Python

Aplicação em Python para consulta de endereço a partir de CEP usando uma API externa.

## O que o projeto demonstra

- Consumo de API REST
- Requisições HTTP
- Leitura de JSON
- Validação de entrada
- Tratamento de exceções
- Diagnóstico básico de falhas de comunicação

## Fluxo

1. O usuário informa o CEP.
2. A aplicação valida o formato.
3. É feita a requisição ao serviço externo.
4. A resposta HTTP é analisada.
5. O JSON retornado é processado.
6. O endereço é apresentado ao usuário.

## Visão para Suporte e Operações de TI

Se a consulta falhar, eu separo a análise em camadas:

1. Validar o dado informado.
2. Confirmar conectividade.
3. Verificar o status HTTP.
4. Conferir o conteúdo retornado.
5. Identificar se a falha está na entrada, aplicação ou serviço externo.
6. Registrar a causa e a ação tomada.

## Como explicar em entrevista

> "Esse projeto me ajuda a demonstrar troubleshooting em uma integração simples. Se a consulta falha, eu procuro descobrir se o problema está no dado informado, na comunicação com a API ou no tratamento da resposta. O objetivo é isolar a causa antes de escalar ou corrigir."

## Tecnologias

**Python • requests • ViaCEP • JSON**

## Próximas evoluções

- Testes automatizados
- Persistência de consultas
- Logs estruturados
- Interface web
- Integração com cadastro de clientes

## Autor

**Daniel Fernando Martins**
