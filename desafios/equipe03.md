### Equipe 03 - Reserva de hotel

- CRUD de Quartos
- CRUD de hospede
- CRUD de reservas

```
- Não reservar quarto já ocupado no período
- Cancelamento de reservas
- Preço total calculado automaticamente
```


#### Use patterns:

| Pattern                | Por que usar                                                             |
| ---------------------- | ------------------------------------------------------------------------ |
| **Strategy Pattern**   | Cálculo do preço da diária (alta/baixa temporada, bed & breakfast etc.). |
| **Policy Pattern**     | Políticas de reserva (cancelamento, horário limite).                     |
| **Repository Pattern** | Consultar disponibilidade de quartos.                                    |
| **Domain Service**     | Fechamento e conferência da reserva.                                     |
