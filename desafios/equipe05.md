## Equipe 05 - Agendamentos Hospitalares 

- CRUD de Pacientes
- CRUD de Médicos
- CRUD de agendamento de consultas

```
Cada agendamento possui:
- data
- horario
- medico
- paciente
- status
- descricao
```

#### Regras
- Um médico não pode ter duas consultas no mesmo horário
- Paciente não pode agendar duas consultas simultâneas
- Cancelamento com registro de motivo 


#### Use patterns:

| Pattern                   | Por que usar                                       |
| ------------------------- | -------------------------------------------------- |
| **Specification Pattern** | Para validar conflitos de horário entre consultas. |
| **Domain Service**        | Agendamento, cancelamento e remarcação.            |
| **Soft Delete**           | Cancelamento mantendo histórico.                   |
| **Repository Pattern**    | Filtrar consultas por médico, paciente e horários. |
