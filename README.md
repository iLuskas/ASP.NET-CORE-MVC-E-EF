# Teste - Processo seletivo

Projeto de teste

## Objetivo
Imagine que você ficou responsável por construir um sistema que seja capaz de receber milhares de eventos por segundo de sensores espalhados pelo Brasil, nas regiões norte, nordeste, sudeste e sul. Seu cliente também deseja que na solução ele possa visualizar esses eventos de forma clara.

## Requisitos
- Sua solução deverá ser capaz de armazenar os eventos recebidos.
- Cada evento poderá ter o estado processado ou erro, caso o campo valor chegue vazio, o status do evento será erro caso contrário processado.
- Para visualização desses dados, sua solução deve possuir:
- Uma tabela que mostre todos os eventos recebidos. Essa tabela deve ser atualizada automaticamente.
- Um gráfico apenas para eventos com valor numérico.
- Para seu cliente, é muito importante que ele saiba o número de eventos que aconteceram por região e por sensor. Como no exemplo abaixo:
- Região sudeste e sul ambas com dois sensores (sensor01 e sensor02):
    1. brasil.sudeste - 1000
    2. brasil.sudeste.sensor01 - 700
    3. brasil.sudeste.sensor02 - 300
    4. brasil.sul - 1500
    5. brasil.sul.sensor01 - 1250
    6. brasil.sul.sensor02 - 250
- Para seu cliente é vital a existência de uma documentação das assinaturas da API.

## Para o desenvolvimento foi utilizado:
* Visual Studio Community 2019 e Visual Studio Code;
* .Net Core;
* Angular;
* Banco de Dados SqlLite;
* DDD Architecture;
* API Rest;
* Code First;

# Métodos da API - POSTMAN
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/99fdb7ee830fc96b0b27)

### EXEMPLO de Readme ainda em construção...
