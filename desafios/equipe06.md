## Equipe 06 - Gestão Escolar 

- CRUD de Alunos
- CRUD de Turmas
- CRDU de Matriculas
  
```
Cada matricula possui:
- aluno
- turma
- data e hora
- status
```

#### Endpoints (alé dos CRUDs)
- alunos de uma turma
- turmas de um aluno



#### Use patterns:

| Pattern                         | Por que usar                                                                   |
| ------------------------------- | ------------------------------------------------------------------------------ |
| **Active Record** (intencional) | Aqui o objetivo é ver como o candidato organiza usando o mínimo indispensável. |
| **Transaction Script**          | Processos simples como matrícula, rematrícula, cancelamento.                   |
| **Query Object**                | Para listar alunos por turma, turmas por aluno, filtros.                       |
