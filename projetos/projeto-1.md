# 1 Projeto Agendamento de Serviço

Desenvolver uma API de Agendamento de Serviços com autenticação com usuário e senha, autorização via JWT ou outro tipo de autenticação e autorização caso ache melhor.

O projeto deverá cadastrar Serviços, agendar/solicitar serviços com data e hora, Avaliação e Comentário.

## Requisitos

1. O sistema deverá ter uma rota privada para criar os usuários de prestadores de serviços.

    - Permissões
      - Criar serviço
      - Listar serviços do prestador
      - Alterar serviço
      - Desabilitar serviço
      - Deletar serviço

</br> 

2. O usuário poderá se cadastrar no sistema com os seguintes atributos:

   - Nome completo
   - Telefone
   - Endereço
   - E-mail
   - Senha

     - Criar rotas para o usuário editar seu perfil

</br>

3. O sistema deverá ter uma rota privada para criar os serviços com os seguintes atributos:

   - Nome do serviço
   - Tipo de serviço
   - Data, hora e dias da semana de funcionamento
   - Valor do serviço

</br>

4. O sistema deverá ter uma rota pública para listar os serviços.

   - Serviço
   - Nome do prestador de serviço
   - Valor do serviço
   - Data, hora e dias disponíveis
   - Avaliações
   - Comentários sobre o serviço

</br>

5. O sistema deverá ter uma rota privada para o usuário agendar/solicitar o serviço:

   - Serviço
   - Usuário
   - Data com dia e a hora da solicitação
   - Status do serviço (Solicitado, Concluido, Cancelado)

</br>

6. O sistema deverá ter uma rota privada para listar os agendamentos/solicitações dos serviços:

   - Serviço
   - Data com dia e a hora que foi agendado/solicitado
   - Valor
   - Status do serviço (Solicitado, Concluido, Cancelado)

</br>

7. O sistema deverá ter uma rota pública para pesquisar os serviços por:

   - Nome
   - Tipo/Categoria

</br>

8. A API deverá ter documentação completa, sugerimos que seja feita com [**Swagger**](https://swagger.io/).
