# estilo.css
#divadd{

}

#divlista{   
    font-family: Arial;
}

.tarefa{
    margin-left: 20%;
}

.desctarefa{
    display: inline;
}

.Prioridade-0{
    color: green;
    font-size: large;
}

.Prioridade-1{
    color: #0000ff;
    font-size: large;
}

.Prioridade-2{
    color: red;
    font-size: large;
}

<!-- html -->

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">
    <title>Document</title>
</head>
<body>
    <!-- div de adicionar tarefas -->
    <div id="divadd">
        <textarea name="" id="" cols="30" rows="10"></textarea>
        <select name="" id="">
            <option value="Prioridade-0">Baixa Prioridade</option>
            <option value="Prioridade-1">Prioridade Normal</option>
            <option value="Prioridade-2">Alta Prioridade</option>
        </select>
        <button>Adicionar</button>
    </div>

    <hr>

    <!-- div de listar tarefas -->
    <div id="divlista">
        <!-- representa um elemento da lista -->
        <div class="tarefa Prioridade-0">
            <p class="desctarefa">Fazer lição</p>
            <button>Excluir tarefa</button>
            <input type="checkbox" name="" id="">
        </div>

        <!-- representa um elemento da lista -->
        <div class="tarefa Prioridade-1">
            <p class="desctarefa">Fazer lição</p>
            <button>Excluir tarefa</button>
            <input type="checkbox" name="" id="">
        </div>

        <!-- representa um elemento da lista -->
        <div class="tarefa Prioridade-2">
            <p class="desctarefa">Fazer lição</p>
            <button>Excluir tarefa</button>
            <input type="checkbox" name="" id="">
        </div>

    </div>    
</body>
</html>
