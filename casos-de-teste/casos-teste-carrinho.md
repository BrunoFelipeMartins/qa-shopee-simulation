# 🧾 Casos de Teste - Carrinho de Compras

| ID | Requisito | Caso de Teste | Passos | Resultado Esperado |
|----|------------|----------------|--------|--------------------|
| CT-02 | RF-01 | Adicionar produto ao carrinho | 1. Acessar Shopee pelo navegador web no desktop <br>2. Pesquisar um produto <br>3. Clicar em "Adicionar ao carrinho" | O produto é adicionado com sucesso |
| CT-02 | RF-02 | Alterar quantidade no carrinho | 1. Acessar o carrinho ao lado do buscador de produtos <br>2. Alterar quantidade do produto <br>3. Confirmar alteração | Deve recalcular o valor de acordo com nova quantidade de itens |
| CT-02 | RF-03 | Quantidade maxima de compra | 1. Acessar o carrinho ao lado do buscador de produtos <br>2. Alterar quantidade do produto para além do estoque do item <br> | Deve avisar quando a quantidade do item exceder a quantidade do estoque. |
| CT-02 | RF-04 | Remover item do carrinho | 1.Acessar o carrinho ao lado do buscador de produto <br>2. Clicar em excluir o item <br> | O item é removido e o total é recalculado |
| CT-02 | RF-05 | Calcular valor total com frete | 1. Adicionar produto ao carrinho <br>2. Prosseguir para checkout <br>3. Selecionar método de entrega | O sistema exibe corretamente o valor do frete e o total |
| CT-02 | RF-06 | Finalizar compra com sucesso | 1. Selecionar método de pagamento <br>2. Confirmar pedido | O sistema exibe mensagem de sucesso e número do pedido |
