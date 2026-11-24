# Reconhecimento da aplicação — SauceDemo

## 1. Objetivo

Realizei uma exploração inicial da aplicação SauceDemo para conhecer suas funcionalidades e entender como funciona o fluxo de compra.

Durante a navegação, observei as principais telas, os recursos disponíveis e alguns comportamentos que podem ser considerados em testes futuros.

## 2. Página de produtos

Ao entrar na aplicação, após realizar o login, fui direcionado para a página Products.

Nessa tela, observei:

- Menu lateral no canto superior esquerdo.
- Carrinho de compras no canto superior direito.
- Filtro para ordenar os produtos.
- Produtos organizados em duas colunas.
- Cards com imagem, nome, descrição, preço e botão Add to cart.

Os filtros disponíveis são:

- Name (A to Z)
- Name (Z to A)
- Price (low to high)
- Price (high to low)

Também acessei os detalhes de alguns produtos. Nessa tela são exibidos o nome, a descrição, o preço e o botão Add to cart, além da opção Back to products para retornar à lista.

No menu lateral, encontrei as opções All Items, Dynamic Catalog, About, Logout e Reset App State. Dentro de Dynamic Catalog, aparecem as opções Lazy Load, Spinner e Slider.

## 3. Carrinho

Ao adicionar um produto, o botão Add to cart muda para Remove, indicando que o item foi adicionado. O número exibido no ícone do carrinho também é atualizado conforme a quantidade de itens adicionados.

Ao acessar o carrinho, fui direcionado para a tela Your Cart.

Nessa tela, os produtos aparecem com as seguintes informações:

- Quantidade (QTY).
- Nome e descrição do produto.
- Preço unitário.
- Botão Remove.

Também observei que o campo de quantidade não permite alteração direta pelo carrinho. Ele apenas exibe a quantidade do produto.

A tela possui os botões Continue Shopping e Checkout.

Ao clicar em Remove, o produto desaparece do carrinho e o indicador de quantidade é atualizado. Quando todos os produtos são removidos, o indicador do carrinho deixa de aparecer.

Na página de produtos, o botão do item removido volta a apresentar a opção Add to cart.

## 4. Checkout: Your Information

Ao clicar em Checkout, fui direcionado para a tela de preenchimento dos dados do comprador.

Os campos disponíveis são:

- First Name
- Last Name
- Zip/Postal Code

Também estão disponíveis os botões Cancel e Continue.

Observei que os três campos são obrigatórios. Ao tentar continuar sem preencher as informações, a aplicação apresenta mensagens específicas para cada campo:

- Sem preencher nenhum campo: `Error: First Name is required`.
- Com apenas o primeiro nome preenchido: `Error: Last Name is required`.
- Com primeiro e último nome preenchidos, mas sem o código postal: `Error: Postal Code is required`.

Quando ocorre um erro, os campos ficam destacados em vermelho e a mensagem aparece em uma caixa vermelha. Essa mensagem também possui um botão para fechá-la.

## 5. Checkout: Overview

Depois de preencher os dados solicitados, fui direcionado para a tela Checkout: Overview.

Nessa etapa, são apresentados:

- Produtos selecionados.
- Quantidade e descrição dos produtos.
- Informações de pagamento (Payment Information).
- Informações de entrega (Shipping Information).
- Valor dos produtos.
- Taxa (Tax).
- Valor total da compra.

No final da página, aparecem os botões Cancel e Finish.

## 6. Checkout: Complete

Após clicar em Finish, fui direcionado para a tela Checkout: Complete.

A aplicação apresenta um ícone de confirmação e a mensagem:

`Thank you for your order!`

Também é exibida a mensagem informando que o pedido foi enviado e chegará ao destino.

Nessa tela, encontrei duas opções:

- Back home
- Generate PDF order

## 7. Fluxo de compra

Durante a exploração, consegui percorrer o fluxo principal de compra da aplicação:

1. Acessar a aplicação.
2. Visualizar a página de produtos.
3. Selecionar um produto.
4. Adicionar o produto ao carrinho.
5. Acessar o carrinho.
6. Conferir os produtos adicionados.
7. Iniciar o checkout.
8. Preencher os dados do comprador.
9. Conferir o resumo da compra.
10. Finalizar o pedido.
11. Visualizar a confirmação da compra.

## 8. Observações finais

A exploração permitiu conhecer as principais etapas da compra, desde a seleção dos produtos até a confirmação do pedido.

Também identifiquei alguns comportamentos que podem ser considerados em atividades futuras, como validação dos campos obrigatórios, inclusão e remoção de produtos, atualização do indicador do carrinho e exibição das informações no resumo da compra.

---

**Projeto:** QA E-commerce Testing  
**Aplicação:** SauceDemo  
**Tarefa:** SCRUM-2 — Reconhecimento inicial da aplicação  
**Atividade:** Reconhecimento funcional