# Projeto Integrador - OurFood

**Gerenciamento de vendas para uma lanchonete**

O nosso cliente, Sr. João, tem uma lanchonete online chamada OurFood e, devido a qualidade de seus produtos, ela está crescendo rapidamente. Devido a alta demanda de pedidos, ele está buscando um sistema que facilite o trabalho de forma ágil e organizada. Um sistema que registre os pedidos, calcule o total da vendas, informe o endereço de entrega, previsão de entrega e forma de pagamento. Além disso, facilite o controle do estoque, relatório de pedidos, de gastos e lucros.


# Situação Problema

![Ciclo da Venda](docs/ciclodevenda.jpeg "Ciclo da Venda")

A empresa OurFood, é uma lanchonete de delivery que atende os pedidos de seus clientes por WhatsApp. A lanchonete existe há dois anos e possui 3 funcionários. O gerente que também é cozinheiro, vulgo o dono, a atendente e o entregador.

O dono do negócio repõe o estoque todas as terças e quintas com os produtos que estão acabando. Em seguida ele faz um levantamento de quanto ele gastou, para repor o estoque. A lanchonete abre às 18:00 das terças aos domingos e fecha às 23:00. Os clientes fazem seus pedidos online pelo WhatsApp, a atendente recebe os mesmos e passa para o cozinheiro, que os prepara e em seguida a atendente embala, junto com as informações do pedido e endereço e por fim o entregador recebe e leva até a residência do cliente. No final da noite, quando a lanchonete fecha, ele soma seus ganhos do dia.

Notamos que os funcionários estavam com excesso de tarefas, e que, por conta disso, ficavam sobrecarregados, principalmente pela falta de organização na hora do atendimento até a entrega. Havia uma alta demanda de pedidos e não era possível atender a todos de uma maneira eficiente. Na hora das entregas, os endereços eram escritos à mão, o que fazia a atendente gastar mais tempo, e também era comunicado da mesma maneira ao cozinheiro.

Sendo assim, diante de toda dificuldade de gerenciamento dos pedidos de forma eficiente, há necessidade de implementação de um software que faça o gerenciamento de pedidos, estoques e controle financeiro.

# Descrição da proposta

A proposta é desenvolver uma plataforma online de pedidos de lanches para uma lanchonete, com o propósito de agilizar e organizar os pedidos.

O cliente terá a possibilidade de escolher seu pedido de forma prática apenas entrando no site. Na página principal haverá uma foto da comida (lanches, bebidas,sobremesas, combos), uma descrição e um botão para selecionar a quantidade. 

O pedido irá para o carrinho. Se o cliente desejar, ele poderá adicionar ou tirar lanches e o site irá calcular o valor total da sua compra. Após isso, o cliente escolhe a sua forma de pagamento, que poderá ser cartão ou pix. Na mesma página, ele ainda irá informar seu endereço e então finalizar o pedido. 

Após finalizar seu pedido, o cliente poderá acompanhar o preparo do seu pedido e receberá um tempo estimado até chegar à sua residência. O cliente poderá dar um feedback com um comentário e classificar o lanche de 0 a 5 estrelas.

No site haverá uma aba onde mostrará quais foram os lanches e combos mais vendidos na semana e quantas estrelas esse lanche tem.

Haverá ainda uma aba no site que só o gerente poderá acessar. Essa aba conterá o faturamento semanal e um relatório do estoque. 

# Regras de Negócio 

- **RN01 - Escolha do pedido:** O cliente irá visualizar as opções de produtos do cardápio no site e colocará no carrinho o que ele deseja e realizará o pedido.

RN02 - Registro de Cliente: Para o pedido ir para produção é necessário registrar os dados do cliente. 

RN03 - Pagamento: Após o realizamento do pedido será feito o pagamento.

RN04 - Visualizações do pedido: A atendente poderá acompanhar os pedidos dos clientes. 

RN05 - Produção do pedido: Com a visualização do pedido, o cozinheiro poderá visualizar os pedidos e produzir o lanche.

RN06 - Comanda para entrega: Após feito o lanche, será expedida uma comanda com dados do pedido e nome do cliente para o entregador, com as informações de endereço do cliente.

RN06 - Entrega: O pedido será entregue no local solicitado pelo cliente ou com a opção de ser retirado pelo cliente no balcão. 

RN08 - Relatórios - Somente o administrador poderá ver todos os relatórios de faturamento e estoque de produtos. 

# Requisitos Funcionais 

**Entrada:**

- **RF01 - Registro de cliente:** O sistema deve possibilitar que os clientes se registrem. **Dados Necessários:** nome, telefone, email, endereço. **Usuários:** cliente.

**Processamento:**
RF02 - O sistema deve encaminhar o pedido para a atendente.

RF03 - O sistema deve informar um tempo extipulado para o pedido chegar em sua residência. 

**Saída:**

RF04 - O sistema deve mostrar os produtos do cardápio.

RF05 - O sistema deve adicionar os produtos escolhidos pelo cliente no carrinho.

RF06 - O sistema deve fornecer uma aba para que o cliente escolha a forma de pagamento(cartão, dinheiro ou pix). 

RF07 - O sistema deve fornecer uma aba para que a atendente possa vizualizar os pedidos. 

RF08 - O sistema deve fornecer um prazo de entrega do pedido. 

RF09 - O sistema deve fornecer um código para que o cliente pague por pix. 

RF11 - O sistema deve emitir um relatório semanal do  faturamento e dos produtos. 

# Requisitos Não Funcionais 

RF01 - O sistema deve estar disponível quando necessário.

RF02 - O sistema deve ser fácil de manter e atualizar.

RF03 - O sistema deve ser confiável e atender aos requisitos do usuário.

RF04 - O sistema deve ser fácil de usar e entender.





