# Lista de Tarefas Interativa

Este projeto implementa uma lista de tarefas dinâmica e persistente utilizando HTML, CSS e JavaScript com Local Storage.

## Funcionalidades Principais

* **Adicionar Tarefas:** Permite adicionar novas tarefas à lista digitando no campo de entrada e pressionando a tecla "Enter".
* **Marcar como Concluída:** Possibilita marcar tarefas como concluídas através de um checkbox associado a cada item. O status (marcado ou não) é persistido.
* **Remover Tarefas:** Oferece a funcionalidade de remover tarefas individuais da lista clicando no botão "X" ao lado de cada item.
* **Persistência de Dados:** As tarefas adicionadas, seus respectivos status de conclusão e a ordem da lista são armazenados localmente no navegador utilizando o Local Storage. Isso garante que os dados persistam mesmo após o fechamento da página.
* **Interface Dinâmica:** A lista de tarefas é atualizada em tempo real conforme novas tarefas são adicionadas, marcadas como concluídas ou removidas, sem a necessidade de recarregar a página.

## Como Utilizar

1.  **Acesso:** Abra o arquivo `index.html` no seu navegador web preferido.
2.  **Adicionar Tarefa:**
    * No campo de texto disponível (geralmente rotulado como "Nova Tarefa"), digite a descrição da tarefa que deseja adicionar.
    * Pressione a tecla "Enter". A nova tarefa será automaticamente adicionada à lista abaixo.
3.  **Marcar/Desmarcar Concluída:**
    * Ao lado de cada tarefa na lista, há um checkbox.
    * Clique no checkbox para marcar a tarefa como concluída.
    * Clique novamente no checkbox para desmarcá-la como não concluída.
4.  **Remover Tarefa:**
    * Ao lado de cada tarefa, há um botão com um "X".
    * Clique neste botão para remover a tarefa correspondente da lista.