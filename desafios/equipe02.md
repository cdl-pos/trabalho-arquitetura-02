## Equipe 02 - Sistema de Restaurante 

```
Cada prato possui:
- preço
- nome
- descrição
```

### Endpoints
- CRUD de mesas
- CRUD de pratos
- CRUD de pedidos
- Abertura de comanda para uma mesa
- Adicionar e remover pratos da comanda
- Fechar comanda + gerar total

### Patterns 
| Pattern                      | Por que usar                                        |
| ---------------------------- | --------------------------------------------------- |
| **Aggregate Root** (Comanda) | Comanda controla coerência de pedidos e totais.     |
| **Service Layer**            | Regras de fechamento de conta, gorjeta, descontos.  |
| **Value Objects**            | Representar preço, quantidade, total com segurança. |
| **Repository Pattern**       | Persistência isolada de Comanda e Pedidos.          |
