## Equipe 07 - Carrinho de Compras 

- CRUD de Produtos
- CRUD de itens no carrinho


#### Endpoints
- Função de adicionar ao carrinho
- Remover do carrinho
- Atualizar quantidade
- Calcular subtotal e total final de acordo com o tipo de pagamento:
  - pix: 10%
  - cartao 1x: 5%
  



#### Use patterns:

| Pattern                        | Por que usar                                      |
| ------------------------------ | ------------------------------------------------- |
| **Repository Pattern**         | Desacoplar consultas de produtos e carrinho.      |
| **DTO (Data Transfer Object)** | Padronizar entrada de itens no carrinho.          |
| **Domain Service**             | Regras de negócio como cálculo de subtotal/total. |
| **Aggregate Root** (Cart)      | Garantir consistência entre Cart e CartItems.     |
| **Factory** (opcional)         | Criar objetos CartItem devidamente validados.     |
