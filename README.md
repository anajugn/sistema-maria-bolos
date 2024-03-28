O sistema de Maria segue a seguite especificação:

Maria faz bolos de aniversário por encomenda. Em virtude do grande aumento dos pedidos ela pediu para Joaquim, seu filho desenvolvedor de sistemas, 
construir um pequeno sistema que lhe permita controlar a ficha de suas clientes e os respectivos pedidos. 
Quando Maria recebe um pedido, ela anota em seu caderno o nome e o telefone de suas clientes. 
Sobre o pedido, ela anota: o tamanho do bolo (altura e largura), o formato, o sabor da massa (chocolate ou inglês), o sabor do recheio (brigadeiro, goiaba ou doce de leite), 
data de entrega, valor do bolo e valor do sinal. O sistema deve exigir que o valor do sinal seja de, no mínimo, 50%. O preço do bolo é calculado da seguinte forma:

Área do bolo = altura * largura;

Custo_ingredientes = área * R$ 51,40;

Custo_recheio = no de camadas;

Valor_do_bolo = Custo_ingredientes + Custo_recheio.

Para calcular o prazo de entrega, considera-se que Maria só consegue produzir 4 bolos por dia.
Maria gostaria que o sistema controlasse os pedidos, calculasse o preço final dos bolos e o prazo de entrega. Para cada bolo cadastrado, 
deve ser emitido um recibo em duas vias (cliente e empresa de Maria), contendo todos os dados da encomenda e do pagamento.
