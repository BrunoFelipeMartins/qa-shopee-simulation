# 🧾 Casos de Teste - Pagamento
| ID | Requisito | Caso de Teste | Passos | Resultado Esperado |
|----|------------|----------------|--------|--------------------|
| CT-01 | RF-04 | Métodos de pagamento | 1. Após conferencia do carrinho e dos cupons deve conter os métodos de pagamentos <br> | Esperado poder selecionar pelo menos uma opção de método de pagamento |
| CT-02 | RF-05 | Opções de pagamentos | 1. Na opção de método de pagamento deve ser possivel selecionar 1 ou mais opções de pagamento <br> | De acordo com opção selecionada é oferecido as opções para dar continuidade |
| CT-03 | RF-06 | Quando não habilitado  | 1. Selecionar opção de pagamento incoerente com local de acesso <br> | Deve exibir mensagem qual solução para a não efetivação da opçao de pagamento |
| CT-04 | RF-07 | Validação de opção de pagamento  | 1. Selecionar opção de pagamento <br>2. Realizar preenchimento dos dados <br> | Deve haver confirmação/verificação dos dados de pagamento |
| CT-05 | RF-08 | Validação de pagamento via pix  | 1. Selecionar opção de pagamento <br>2. Continuar com método de pagamento <br>3. Efetivação do pagamento por QR code ou copia/cola | Espera os dados para efetivação do pagamento, e tempo para realizalçao do pagamento|
