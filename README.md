# ignite-template-reactjs-conceitos-do-react

Aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no ReactJs.
<br><br>

Principal objetivo da aplicação: 

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

<br>
Para concluir este desafio (o arquivo de teste TaskList.spec.tsx foi executado para validação), os critérios abaixo foram atendidos:

- **should be able to add a task**

Permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o padrão da interface dada.

- **should not be able to add a task with an empty title**

Antes de criar uma nova task, validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio.
Caso o valor digitado seja vazio, impedir a criação da task.

- **should be able to remove a task**

Permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.

- **should be able to check a task**

Permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de `isComplete` de `false` para `true` ou ao contrário, de `true` para `false`.

<br>
Interface da Aplicação:

![image](https://user-images.githubusercontent.com/83955839/231263198-39f3e464-9403-4f71-ae08-12c5cc352921.png)
