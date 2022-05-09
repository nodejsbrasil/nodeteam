# Proeto Gerenciador de Arquivos

Desenvolver uma API de Gerenciamento de Arquivos via usuário e senha com autorização via JWT ou outro tipo de autenticação e autorização caso julgue melhor.

O projeto deverá fazer uploads de arquivos

# Requisitos

1. O sistema deverá ter uma rota privada para cadastrar usuário

   - Permissões
     - Fazer upload de arquivos
     - Alterar arquivo (Ex: nome do arquivo)
     - Remover arquivo

</br>

2. O usuário poderá se cadastrar no sistema com os seguintes atributos:

   - Nome
   - E-mail
   - Senha
  
   - [ ] Criar rotas para editar o perfil do usuário

</br>

3. O sistema deverá ter uma rota privada para fazer upload de arquivos:

   - Imagens
   - Vídeos
   - PDF's
   - e mais caso julgue interessante

</br>

4. O sistema deverá ter uma rota privada para listagem dos arquivos:

   - Nome do arquivo
   - Formato de arquivo
   - Tamanho do arquivo
   - Link do arquivo

</br>

5. O sistema deverá ter uma rota privada para detalhar o arquivo pelo ID.

   - Nome
   - Formato
   - Tamanho
   - Link

</br>

6. A API deverá ter documentação completa, sugerimos que seja feita com [**Swagger**](https://swagger.io/).