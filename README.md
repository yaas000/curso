<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div>
        <p>usuario:</p>
        <input id="usuario" type="text">
        
        <p>senha:</p>
        <input id="senha" type="password">

        <button id="botao">logar</button>

    </div>
    <script>
        var botao = document.getElementById("botao");

        botao.addEventListener('click', function(){
            var usuario = document.getElementById("usuario").value;
            var senha = document.getElementById("senha").value;
        })
        
    </script>
</body>
</html>
