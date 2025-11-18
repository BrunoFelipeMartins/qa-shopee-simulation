# 🧾 Casos de Teste Negativos - Carrinho de Compras
***Todos os testes são realizados pelo navegador web através do desktop.

| ID | Requisito | Caso de Teste | Passos | Resultado Esperado |
|----|------------|----------------|--------|--------------------|
| CT-07 | RF-07 | Adicionar produto com estoque esgotado no carrinho | 1. Acessar Shopee pelo navegador web no desktop <br>2. Adicionar um item com estoque zerado no carrinho <br> | Deve exibir a mensagem informando que produto está sem estoque e não pode dar continuidade no processo de compra. |  
| CT-08 | RF-08 | Adicionar o mesmo item além da quantidade máxima permitida para aquele item | 1. Adicionar um item ao carrinho de compra <br>2. Inserir quantidade maior que permitida do item | Deve exibir a mensagem informando "Desculpe, você só pode comprar no máximo <quantidade_maxima> em um checkout". |  
| CT-09 | RF-09 | Alterar a quantidade de um item no carrinho para zero | 1. Adicionar um item ao carrinho de compra <br>2. Inserir quantidade 1 e clicar e no botão "-" (Site não permite digitar 0) | Deve exibir a mensagem informando "Você quer remover este item?". |  
