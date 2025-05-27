# PadroesSoftaware

# UC02 – Fazer Login
Ator: Usuário

Descrição: Permite que um usuário existente acesse sua conta.

Pré Condição: Usuário deve estar cadastrado no sistema.

Fluxo Principal:

 -1 Usuário acessa tela de login.

 -2 Informa e-mail e senha.

 -3 Sistema valida os dados e redireciona para área logada.

Fluxo Alternativo:

  2a. Dados incorretos → Sistema exibe mensagem de erro.

Pós Condição: 
  Usuário é logado em sua conta e retorna a pagina home.



# UC06 – Finalizar Compra
Ator: Usuário

Descrição: Realiza o processo de checkout.

Fluxo Principal:

 -1 Usuário acessa o carrinho.

 -2 Informa endereço de entrega.

 -3 Escolhe forma de entrega.

 -4 Escolhe método de pagamento.

 -5 Confirma o pedido.

 -6 Sistema salva o pedido e exibe confirmação.

Fluxo Alternativo:

  4a. Pagamento falha → Sistema informa erro e permite nova tentativa.

# UC08 – Acompanhar Pedido
Ator: Usuário

Descrição: Permite ao usuário acompanhar o status do pedido.

Fluxo Principal:

 -1 Usuário acessa sua conta e visualiza pedidos.

 -2 Clica em um pedido.

 -3 O sistema mostra status: pagamento, envio, entrega, cancelamento, etc.

Fluxo Alternativo:

  1a. O usuário não tem nenhum pedido ativo.

Pós Condição: 
  O usuário recebe todas as informações sobre o seu produto.
