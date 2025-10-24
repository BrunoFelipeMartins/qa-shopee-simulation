# Relatório de Bugs

## BUG-001
**Título:** CT04-RF07 - Catálogo e produtos  
**Descrição:** Detalhes dos itens em branco  
**Severidade:** Baixa  
**Passos para reproduzir:**  
1. Abri item do catálogo  
2. deslocar para baixo, na parte da descrição sem a tela estar maximizada  
**Resultado Esperado:** Toda a descrição dos itens deveriam estar aparecendo  
**Resultado Obtido:** A area da descrição consta em branco quando a tela menor  
**Status:** Aberto

<img width="934" height="855" alt="Não consta a descrição do item, aparece somente tela em branco" src="https://github.com/user-attachments/assets/21acb42e-bbfc-4e22-bfc9-3f547ed713ad" />


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
