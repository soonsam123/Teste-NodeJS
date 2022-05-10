# Teste-NodeJS

Esse é um teste para a vaga de NodeJS descrita [nesse link](https://www.linkedin.com/jobs/view/3046932582/).

# O que você deve fazer?

Você irá fazer uma API REST de agendamento de serviços.

# O que devo utilizar?

Você deve utilizar para fazer a API:

- NodeJS/Express;
- Banco de dados MySQL;
- Javascript ou Typescript (o de sua preferência);
- O restante que precisa será de sua preferência.

# Banco de dados

O seu banco de dados deve ter apenas 3 tabelas, a que irá armazenar os serviços disponíveis para serem realizados.

A tabela de serviços irá ter colunas como: id, titulo serviço, descrição do serviço, data para o serviço ser executado (Ex: O serviço será realizado no dia 10 de maio de 2022), id do tipo de serviço, id do usuário que está postando o serviço.
A tabela de tipo de serviços irá ter colunas como: id, tipo do serviço. E valores como: `REPOSITOR, PESQUISA DE PRECOS, CAIXA etc...`
A tabela de usuários irá ter colunas como: id, nome, login, senha.

A tabela de serviços será a principal, e nela teremos as chaves estrangeiras do tipo de serviço e do usuário.

# Endpoints

Você deve fazer os seguintes endpoints na sua API.

```
GET /servicos
```

# Como entregar?
