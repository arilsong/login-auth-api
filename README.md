## login-auth-api
Esta API, desenvolvida em Java Spring Boot, fornece autenticação usando JSON Web Tokens (JWT) e utiliza o banco de dados H2 para armazenamento temporário de dados na memória.

### Descrição
Uma API de autenticação simples que implementa autenticação baseada em JWT para proteger endpoints e gerenciar usuários, utilizando o banco de dados H2 para armazenamento temporário de dados.

### Funcionalidades
Autenticação de usuários com JWT.
Armazenamento de dados temporários na memória com o banco de dados H2.
Criação e verificação de tokens JWT.

### Endpoints
POST /auth/register: Permita o usuario criar uma conta.
POST /auth/login: Autentica o usuário e retorna um JWT.
GET /user: Requer um JWT válido para acesso.