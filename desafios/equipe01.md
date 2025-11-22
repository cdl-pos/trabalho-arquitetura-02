### Equipe 01 - Lógistica/Rastremanto 

- CRUD de Pacotes
- Endpoints para rastreio via código

```
Cada pacote possui:
- código de rastreio
- destinatário
- endereço
- status
```

#### Endpoints
- CRUD pacotes
- Atualizar status
- Consultar linha do tempo do pacote



#### Use patterns:

| Pattern                           | Por que usar                                     |
| --------------------------------- | ------------------------------------------------ |
| **Event Sourcing (simplificado)** | Cada movimentação vira um evento.                |
| **Read Model** (CQRS light)       | Uma tabela para consulta rápida do status atual. |
| **Command Handler**               | “RegistrarMovimentação”, “AtualizarStatus”.      |
| **Value Objects**                 | Código de rastreio, endereço, coordenadas.       |
