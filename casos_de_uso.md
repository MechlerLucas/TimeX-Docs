# Diagrama de Casos de Uso – TimeX

```mermaid
flowchart TD
    Usuario((Usuário))
    
    Usuario --> CT[ Criar Tarefa ]
    Usuario --> ET[ Editar Tarefa ]
    Usuario --> XT[ Excluir Tarefa ]
    Usuario --> LT[ Listar Tarefas ]
    Usuario --> FT[ Filtrar Tarefas ]
    Usuario --> VD[ Visualizar Detalhes ]
    Usuario --> CO[ Concluir Tarefa ]
    Usuario --> CN[ Configurar Notificações ]
