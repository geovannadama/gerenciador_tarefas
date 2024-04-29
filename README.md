# gerenciador_tarefas
Este é um simples gerenciador de tarefas desenvolvido em PHP, HTML e CSS. Ele permite que você cadastre e visualize suas tarefas de forma rápida e fácil.

## Como funciona
O gerenciador de tarefas utiliza sessões em PHP para armazenar as tarefas cadastradas. Quando você cadastra uma nova tarefa, ela é adicionada à lista de tarefas na sessão atual. Você também tem a opção de limpar todas as tarefas cadastradas.

## Requisitos 
Para utilizar o gerenciador de tarefas, você precisará de:

1. Um servidor web com suporte a PHP.
2. Um navegador web moderno.

## Uso
1. Na página inicial, você verá um campo de entrada para adicionar uma nova tarefa.
2. Digite o nome da tarefa no campo e clique em "Cadastrar".
3. A tarefa será adicionada à lista de tarefas exibida logo abaixo do campo de entrada.
4. Para limpar todas as tarefas cadastradas, clique no botão "Limpar Tarefas".

## Detalhes do código

session_start(): Inicia uma nova sessão ou retoma a sessão existente.

$_SESSION['tasks']: Array utilizado para armazenar as tarefas cadastradas pelo usuário.

Adição de Tarefa: Quando o usuário submete o formulário com o nome da tarefa ($_GET['task_name']), a tarefa é adicionada ao array $_SESSION['tasks'].

Limpeza de Tarefas: Se o usuário clicar no botão "Limpar Tarefas", todas as tarefas são removidas da sessão.



## Fontes 
Chat GPT
(https://www.treinaweb.com.br/blog/css-flexbox-um-guia-interativo-parte-1-containers#google_vignette)  
(https://cursos.alura.com.br/forum/topico-para-que-serve-especificadamente-a-funcao-foreach-222477)  
(https://www.php.net/manual/pt_BR/function.array-sum.php)  

## Informações adicionais
O código pertence ao canal Monolito.
(https://www.youtube.com/watch?v=dJ49I-QYYUk&ab_channel=MonolitoPHP)
