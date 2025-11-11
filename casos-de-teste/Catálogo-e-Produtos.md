# 🧾 Casos de Teste - Catálogo e Produtos

| ID | Requisito | Caso de Teste | Passos | Resultado Esperado |
|----|------------|----------------|--------|--------------------|
| CT-01 | RF-01 | Funcionamento da barra de pesquisa, ao clicar na lupa de pesquisa. | 1. Pesquisar itens <br>2. Clicar na lupa para realizar a pesquisa <br> | Deve enviar a pesquisa. |
| CT-01 | RF-02 | Funcionamento da barra de pesquisa, ao pressionar o ENTER para pesquisa.  | 1. Pesquisar itens <br>2. Pressionar o ENTER para realizar a pesquisa <br> | Deve enviar o comando de pesquisa. |
| CT-01 | RF-03 | Utilizar item do historico de pesquisa | 1. Selecionar um item do historico de pesquisa, ao clicar na barra de pesquisa ira aparecer os itens pesquisados anteriormente <br>2. clicar em um dos itens do historico. <br> | Deve realizar a pesquisa no item selecionado. |
| CT-01 | RF-04 | Pesquisar produtos com nomes escritos de formas diferentes, como todos em UPPERCASE. | 1. Pesquisar item com letra em UPPERCASE Ex: GARRAFA <br> | Deve buscar itens Garrafa, mesmo com nome sendo escrito em UPPERCASE|
| CT-01 | RF-05 | Pesquisar produtos com nomes escritos de formas diferentes, como todos em lowercase. | 1. Pesquisar item com letra em lowercase Ex: garrafa <br> | Deve buscar itens Garrafa, mesmo com nome sendo escrito em lowercase|
| CT-01 | RF-06 | Pesquisar produtos com nomes escritos de formas diferentes, como sem acentuação para vereficar se o buscador busca os nomes referentes, ex: armario/Armário | 1. Pesquisar item armario | Deve buscar itens correspondente a Armário, mesmo sendo escrito armario. |
| CT-01 | RF-07 | Pesquisar produtos com nomes escritos de formas diferentes, como sem acentuação para vereficar se o buscador busca os nomes referentes, ex: armaio/Armário | 1. Pesquisar item armaio | Deve buscar itens correspondente a Armário, mesmo sendo escrito armaio. |
| CT-01 | RF-08 | Buscar uma categoria | 1. Escolher uma categoria <br>2. Pesquisar a categoria de itens <br> | Deve conter os itens daquela categoria|
| CT-01 | RF-09 | Buscar item da categoria feminina dentro da categoria masculina  | 1. Abrir itens da categoria masculina <br>2. Na barra de pesquisa pesquisar itens de outra categora "em categoria Masculina" <br> | Não dev encontrar itens de categorias diferentes.|
| CT-01 | RF-10 | Aplicação de filtro  | 1. Aplicar um filtro  <br>2. Pesquisar itens com filtro aplicado <br> | Exibir itens relacionados aos itens do filtro |
| CT-01 | RF-11 | Aplicação de multiplos filtros  | 1. Aplicar varios filtros  <br>2. Pesquisar itens com os filtros aplicados <br> | Exibir itens relacionados a escolha dos filtros, espera que seja poucos itens |
| CT-01 | RF-12 | Destalhes/descrição do produto  | 1. Escolher produto do catálogo  <br>2. Abaixo do item selecionado deve conter a descrição detalhada do item <br> | Descrição do destalhes do item selecionado |
| CT-01 | RF-13 | Verificar valor do item por cor ou tamanho  | 1. Escolher produto do catálogo  <br>2. Escolher diferentes cores ou tamahos <br>3. Verificar a diferença de valores conforme mudar as cores/tamanhos  | Deve ser alterado o valor conforme a cor/tamanho do produto escolhido |
