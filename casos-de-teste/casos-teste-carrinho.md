# 🧾 Casos de Teste - Carrinho de Compras

| ID | Requisito | Caso de Teste | Passos | Resultado Esperado |
|----|------------|----------------|--------|--------------------|
| CT-01 | RF-04 | Adicionar produto ao carrinho | 1. Acessar Shopee <br>2. Pesquisar um produto <br>3. Clicar em "Adicionar ao carrinho" | O produto é adicionado com sucesso |
| CT-02 | RF-05 | Alterar quantidade no carrinho | 1. Acessar o carrinho <br>2. Alterar quantidade do produto <br>3. Confirmar alteração | O valor total é atualizado automaticamente |
| CT-03 | RF-06 | Remover item do carrinho | 1. Acessar o carrinho <br>2. Clicar em "Remover" <br>3. Confirmar remoção | O item é removido e o total é recalculado |
| CT-04 | RF-09 | Calcular valor total com frete | 1. Adicionar produto ao carrinho <br>2. Prosseguir para checkout <br>3. Selecionar método de entrega | O sistema exibe corretamente o valor do frete e o total |
| CT-05 | RF-12 | Finalizar compra com sucesso | 1. Selecionar método de pagamento <br>2. Confirmar pedido | O sistema exibe mensagem de sucesso e número do pedido |
