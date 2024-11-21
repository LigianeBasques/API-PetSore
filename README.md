# 🐶API-PetStore🐶 #

# 👀Visão Geral👀 #
A API Petstore simula um sistema de gerenciamento de informações para uma loja de animais de estimação. 

# 🏃Primeiros passos🏃 #
### Instale o Postman ###
Baixe e instale o postman em seu computador entre no site: https://www.postman.com/downloads/
### Use a API PetStore ###
Acesse o link da api: https://petstore.swagger.io/

# 🪀 Como usar com o Postman🪀  #
+ **Importar a API:** Use o link da documentação (https://petstore.swagger.io/v2/swagger.json) no Postman para importar todos os endpoints diretamente.


# 🔨 Estrutura dos testes da API🔨  #
+ **Pets:** CRUD (Create, Read, Update, Delete) para gerenciar informações sobre animais de estimação, como nome, status (disponível, pendente, vendido), etc
+  **Endpoints comuns:**
+  GET {{baseURL}}/pet/findByStatus?status=sold: Lista todos os pets da loja por status
+  POST / https://petstore.swagger.io/v2/pet: Adiciona um novo pet.
+ PUT /https://petstore.swagger.io/v2/pet: Atualiza informações de um pet existente.
+ DELETE /https://petstore.swagger.io/v2/pet/{id} Remove um pet pelo ID.

# 📈Testando a API no Postman📈  #
No Postman foi adcionado a collection da API PetStore, além de realizar os testes de CRUD, também realizei algumas validações, como por exemplo: Status code 200, conteúdo do body e teste de contrato. 

![Teste da API no Postman](https://imgur.com/cVb16bc.png)
  




