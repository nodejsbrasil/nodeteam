# 6 - Projeto Pontos Turísticos

Desenvolver uma API de Pontos Turísticos com autenticação via usuário e senha e autorização via JWT ou outro tipo de autenticação e autorização caso ache melhor.

O projeto deverá cadastrar Cidades, Pontos turísticos, Agendamentos de visitas com a data e hora, Avaliação, Comentário e Adição de fotos pelos visitantes.

## Requisitos:

1. O sistema deverá ter uma rota privada para criar os usuários admin.

   - Permissões
     - Criar ponto
     - Alterar ponto
     - Inativar ponto
     - Remover comentário
     - Inativar usuários

</br>

2. O usuário poderá se cadastrar no sistema com os seguintes atributos:
      - Nome completo
      - Nome de usuário
      - E-mail
      - Senha

        - Criar rotas para o usuário editar o próprio perfil

</br>

3. O sistema deverá ter uma rota privada para criar os pontos turísticos.
   - Endereço
   - Fotos do ponto turístico
   - história do local
     - Criar uma sub rota pública que permita adicionar
       - Comentários
       - Fotos
       - Avaliações (escalada de 0 a 10)

</br>

4. O sistema deverá ter uma rota pública para listar os pontos turísticos.

    - Endereço
    - Total de visitas recebidas (considere os agendamentos)
    - Fotos do ponto turístico
    - Fotos dos visitantes
    - Comentários
    - Avaliações (exibir média ex: 9,5)
    - história do local

</br>

5. O Sistema deverá ter uma rota para pesquisar os pontos turísticos por.

    - CEP
    - Endereço
    - Cidade
    - Estados

</br>

6. A API deverá ter Documentação completa, sugerimos que seja feita com [**Swagger**](https://swagger.io/).






