# To-Do App
🔍 **Descrição (Description)**
 - App Desktop de Tarefas construído com Python e Tkinter. 
 - Desktop Tasks App built with Python and Tkinter.
✨ **Funcionalidades (Features)**
 - Criar Tarefas   |  Create Tasks 
 - Editar Tarefas  |  Edit Tasks
 - Excluir Tarefas |  Delete Tasks
 - Marcar Tarefas Concluídas |  Toggle Task Completion
🛠️ **Tecnologias Utilizadas (Technology)**
 - Python 3.12.8
📚 **Bibliotecas (Library)**
 - Tkinter
🏗️ **Estrutura do Código (Code Structure)**
 **PT-BR**
 Importação de Bibliotecas:
 - Utiliza módulos do Tkinter (tk, ttk, font, messagebox, PhotoImage) para construir a interface.

 Funções Principais:
 - adicionar_tarefa(): Trata a entrada e atualização de tarefas.
 - adicionar_item_tarefa(tarefa): Cria os widgets (frame, labels, botões e checkbutton) para cada tarefa.
 - preparar_edicao(frame_tarefa, label_tarefa): Prepara a interface para edição de uma tarefa.
 - atualizar_tarefa(nova_tarefa): Atualiza o texto da tarefa em edição.
 - deletar_tarefa(frame_tarefa): Remove a tarefa da interface.
 - alternar_sublinhado(label): Alterna o estilo da fonte para indicar a conclusão da tarefa.

 Interface Gráfica:
 - A janela principal (janela) é configurada com:
 - Uma área para inserir tarefas.
 - Um frame que contém a lista de tarefas com uma barra de rolagem.
 - Botões para adicionar, editar e deletar tarefas.
 - Carregamento de ícones para os botões de editar e deletar.

 **EN**
  Library import:
 - Uses Tkinter modules (tk, ttk, font, messagebox, PhotoImage) to build the interface.

 Main functions:
 - adicionar_tarefa(): Handles the entry and updating of tasks.
 - adicionar_item_tarefa(tarefa): Creates the widgets (frame, labels, buttons and checkbutton) for each task.
 - preparar_edicao(frame_tarefa, label_tarefa): Prepares the interface for editing a task.
 - atualizar_tarefa(nova_tarefa): Updates the text of the task being edited.
 - deletar_tarefa(frame_tarefa): Removes the task from the interface.
 - alternar_sublinhado(label): Toggles the font style to indicate completion of the task.

 Graphical interface:
 - The main window (janela) is configured with:
 - An area for inserting tasks.
 - A frame containing the list of tasks with a scroll bar.
 - Buttons for adding, editing and deleting tasks.
 - Loading icons for the edit and delete buttons.