# Bug Report - BR001: Campo "Last Name" não é preenchido corretamente no checkout

**Severidade:** Alta  
**Prioridade:** Alta

**Descrição:** Ao inserir o sobrenome no campo "Last Name" durante o checkout, o sistema altera o valor do campo "First Name" e não preenche o campo "Last Name". Isso impede que o checkout seja concluído.

**Passos para Reproduzir:**
1. Logar no sistema com usuário válido.
2. Adicionar um produto ao carrinho.
3. Prosseguir para o checkout.
4. Inserir nome no campo "First Name".
5. Inserir sobrenome no campo "Last Name".
6. Observar o comportamento.

**Resultado Obtido:**
- O campo "First Name" é alterado com o valor digitado em "Last Name".
- O campo "Last Name" permanece vazio.

**Resultado Esperado:**
- O campo "Last Name" deve receber o sobrenome digitado, mantendo o valor correto no campo "First Name".

**Ambiente:**  
- Navegador: Chrome  
- SO: Windows 11
