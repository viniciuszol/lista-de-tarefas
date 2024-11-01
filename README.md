# Lista de Tarefas

Este projeto em Java é uma aplicação simples de gerenciamento de tarefas, utilizando a interface `Set` para armazenar um conjunto de objetos do tipo `Tarefa`. Cada tarefa possui uma descrição e um indicador booleano que mostra se a tarefa foi concluída ou não.

## Funcionalidades

A classe `ListaTarefas` implementa os seguintes métodos:

- **adicionarTarefa(String descricao)**: Adiciona uma nova tarefa ao conjunto.
- **removerTarefa(String descricao)**: Remove uma tarefa do conjunto pela descrição, se estiver presente.
- **exibirTarefas()**: Exibe todas as tarefas da lista.
- **contarTarefas()**: Conta o número total de tarefas na lista.
- **obterTarefasConcluidas()**: Retorna um conjunto com as tarefas concluídas.
- **obterTarefasPendentes()**: Retorna um conjunto com as tarefas pendentes.
- **marcarTarefaConcluida(String descricao)**: Marca uma tarefa como concluída pela descrição.
- **marcarTarefaPendente(String descricao)**: Marca uma tarefa como pendente pela descrição.
- **limparListaTarefas()**: Remove todas as tarefas da lista.

## Tecnologias Utilizadas

- Java SE
- Interface `Set` para garantir a unicidade das tarefas.
