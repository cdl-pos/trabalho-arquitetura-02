## Equipe 04 - Controle de Oficina Mecanica 

- CRUD de Clientes
- CRUD de Veículos (relacionado ao cliente)
- CRUD de Ordens de Serviço

```
**Cada OS possui:**
- descrição do problema
- status
- valor estimado
- valor final
```

#### Regras
- Não permitir OS finalizada sem valor final
- Registrar histórico de mudanças de status 




#### Use patterns:

| Pattern             | Por que usar                                                  |
| ------------------- | ------------------------------------------------------------- |
| **State Pattern**   | Controle de status da OS (aberta → em execução → finalizada). |
| **Event Log Model** | Registrar histórico de mudança de status.                     |
| **Domain Events**   | "OSFinalizada", "StatusAlterado".                             |
| **Unit of Work**    | Alterar OS + histórico de forma transacional.                 |
