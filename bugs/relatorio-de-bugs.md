# Relatório de Bugs

## BUG-001
**Título:** Frete não atualiza ao alterar endereço  
**Severidade:** Média  
**Passos para reproduzir:**  
1. Adicionar produto ao carrinho  
2. Ir para o checkout  
3. Alterar endereço de entrega  
**Resultado Esperado:** O valor do frete deve atualizar conforme o novo endereço  
**Resultado Obtido:** O valor do frete permanece o mesmo  
**Status:** Aberto  

---

## BUG-002
**Título:** Campo de pagamento não valida número de cartão incorreto  
**Severidade:** Alta  
**Passos:**  
1. Selecionar pagamento por cartão  
2. Inserir número inválido (ex: 1234 5678 9999 0000)  
3. Confirmar pagamento  
**Resultado Esperado:** O sistema deve exibir mensagem de erro  
**Resultado Obtido:** Pagamento é processado normalmente  
**Status:** Aberto
