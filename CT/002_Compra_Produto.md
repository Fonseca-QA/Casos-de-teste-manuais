# Caso de Teste - CT002: Compra de Produto

**Objetivo:** Validar se o usuário consegue realizar uma compra de produto com sucesso.

**Pré-condições:**
- Ter um usuário já cadastrado e logado.
- Produto disponível no estoque.

**Passos:**
1. Acessar a lista de produtos.
2. Selecionar um produto.
3. Adicionar ao carrinho.
4. Ir para o checkout.
5. Inserir nome/sobrenome e código postal.
6. Confirmar compra.

**Resultado Esperado:**
- Compra finalizada com sucesso.
- Mensagem de confirmação exibida com número do pedido.

**Resultado Obtido:**
- Ao inserir o sobrenome no campo "Last Name", o campo "First Name" é alterado e o campo "Last Name" permanece vazio.
- Isso impede o preenchimento correto dos dados para prosseguir no checkout.

**Status:** Falhou.