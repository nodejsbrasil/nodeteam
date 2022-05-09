# 2 - Projeto Controle de Estoque

Desenvolver uma API de Controle de Estoque com autenticação via usuário e senha e autorizações com JWT ou outro tipo de autenticação e autorização caso julgue melhor.

O projeto deverá cadastrar Produtos, Adição e retirada do produto do estoque.

## Requisitos:

1. O sistema deverá ter uma rota privada para criar usuário:

   - Permissões
     - Cadastrar produto
     - Alterar produto
     - Deletar produto

</br>

1. O usuário poderá se cadastrar no sistema com os seguintes atributos:

   - Nome completo
   - Nome da empresa
   - Seguimento
   - CNPJ
   - E-mail
   - Senha

   - [ ] Criar rotas para o usuário editar seu perfil.

</br>

3. O sistema deverá ter uma rota privada para cadastrar os produtos com os seguintes atributos:

   - Nome do produto
   - Descrição do produto
   - Valor do produto
   - Código do produto
   - Quantidade de estoque do produto
   - Categoria

   - [ ] Criar rotas para o usuário editar o produto.

</br>

4. O sistema deverá ter uma rota privada para listagem dos produtos:

   - Nome do produto
   - Descrição do produto
   - Valor do produto
   - Quantidade de estoque do produto
   - Código do produto

</br>

5. O sistema deverá ter uma rota privada para detalhar o produto pelo ID.

   - Nome
   - Descrição
   - Valor
   - Quantidade
   - Código

</br>

6. O sistema deverá ter uma rota para pesquisar os produtos por:

   - Nome
   - Código
   - Categoria

</br>

7. O sistema deverá ter um mini Dashboard com informações do estoque do usuário e deverá mostrar:

   - Total de produtos que já foi cadastrado
   - Total de produtos em estoque
   - Total de produtos que já saiu do estoque
   - Valor total do estoque atual
   - Valor já faturado

</br>

8. A API deverá ter documentação completa, sugerimos que seja feita com [**Swagger**](https://swagger.io/).