# Projeto de Autenticação

Desenvolver uma API de autenticação de usuários por e-mail

O projeto deverá cadastrar usuário, confirmar usuário por e-mail e autenticar o usuário no sistema via e-mail.

## Requisitos

1. O sistema deverá ter uma rota para criar o usuário com os seguintes atributos:

   - Nome completo
   - E-mail
   - Senha

</br>

2. O sistema deverá enviar um link com expiração de 24 horas para o e-mail do usuário para confirmar o cadastro da conta.

   - Link de confirmação

</br>

3. O usuário poderá logar no sistema digitando apenas o e-mail e  deverá receber um link com expiração de 24 horas por e-mail para logar no sistema.

   - Link para SignIn

</br>

4. O sistema deverá ter uma rota privada para o usuário alterar os dados do seu perfil:

   - Nome completo

</br>

5. O sistema deverá invalidar o link de SignIn enviado por e-mail após o usuário logar no sistema.

</br>

6. A API deverá ter documentação completa, sugerimos que seja feita com [**Swagger**](https://swagger.io/).