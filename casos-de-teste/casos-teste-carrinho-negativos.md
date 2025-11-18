# 🧾 Casos de Teste Negativos - Carrinho de Compras
***Todos os testes são realizados pelo navegador web através do descktop.

| ID | Requisito | Caso de Teste | Passos | Resultado Esperado |
|----|------------|----------------|--------|--------------------|
| CT-07 | RF-07 | Adicionar produto com estoque esgotado no carrinho | 1. Acessar Shopee pelo navegador web no desktop <br>2. Adicionar um item com estoque zerado no carrinho <br> | Deve ser "avisado" que produto está sem estoque e não pode dar continuidade no processo de compra. |  
| CT-08 | RF-08 | Adicionar o mesmo item além da quantidade maxíma permitida para aquele item | 1. Adicionar um item ao carrinho de compra <br>2. inserir quantidade maior que permitida do item | Deve ser informado que "Desculpe, você só pode comprar no máximo xxx em um checkout". |  
| CT-09 | RF-09 | Alterar a quantidade de um item no carrinho para zero | 1. Adicionar um item ao carrinho de compra <br>2. inserir quantidade 1 e clicar e - (Site não permite digitar 0) | Deve ser informado pela menssagem "Você quer remover este item?". |  
