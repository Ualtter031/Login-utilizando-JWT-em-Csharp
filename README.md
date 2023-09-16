Projeto LoginJWT: Autenticação de Usuário via Token JWT
O projeto LoginJWT é um experimento que se concentra na autenticação de usuários por meio de tokens JWT (JSON Web Tokens). Essa abordagem proporciona um método seguro e eficaz para verificar a identidade do usuário durante o processo de login.

Teste de Envio de JSON
Para testar a funcionalidade da API LoginJWT, você pode usar a seguinte URL para enviar um JSON de exemplo contendo informações de login:

URL de Teste: http://localhost:5139/v1/account/login

Exemplo de Corpo JSON
Aqui está um exemplo de como o corpo JSON deve ser formatado para efetuar a autenticação:

{ "username": "gabriel", "password": "gabriel" }

Método HTTP para Requisição
Certifique-se de utilizar o método HTTP POST ao enviar a sua requisição para a API LoginJWT. Isso garante a segurança e a integridade dos dados de login transmitidos.

Usuários para Teste
Para testar a funcionalidade de autenticação, você pode utilizar os seguintes dados de usuário:

**Usuário 1:

Nome de Usuário: gabriel
Senha: gabriel
**Usuário 2:

Nome de Usuário: robin
Senha: robin
Estes usuários de teste estão disponíveis para facilitar o processo de verificação de autenticação via token JWT.
