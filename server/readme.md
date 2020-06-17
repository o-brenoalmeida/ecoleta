*ANOTAÇÕES*

## Rota : Endereço completo da requisição
## Recurso: Qual entidade estamos acessando do sistema


*VERBOS HTTP*

-> GET: Buscar uma ou mais informações do back-end
## POST: Criar uma nova informação no back-end
## PUT: Atualizar uma informação existente no back-end
## DELETE: Remover uma informação no back-end

## POST http:##localhost:3333/users  => Criar um usuário
## GET http:##localhost:3333/users   => Listar usuários
## GET http:##localhost:3333/users/5 => Buscar dados do usuário com ID 5

*Parâmetros*
## Request Param: Parâmetros que vem na própria rota que identificam um recurso
## Query Param: Parâmetros que vem na própria rota, geralmente opcionais para filtros, paginações e afins.
## Request Body: Parâmetros para criação/atualização de informações
