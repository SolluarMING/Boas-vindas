<!-- 

       ## IMPORTANTE ##
       Desafio feito a partir dos desafios do professor Gustavo Guanabara
       Ele será somente usado para fins de estudos


-->








<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desafio</title>
    <style>
        input{
            width: 120px;
            height: 50px;
            font: normal 12pt arial;
            background: black;
            color: white;
        }
        body{
            background: yellow;
            font: oblique 20pt arial;
        }
    </style>
</head>
<body>
    <h1>Boas-vindas</h1>
    <input type="button" value="Inicie o desafio" onclick="d1()">
     
    <script>
        function d1() {
            var a = window.prompt(`Qual o seu nome?`)
            var b = window.prompt(`Bem vindo, ${a}! Quantos anos você tem?`)
            var c = window.alert(`Acabei de conhecer ${a}, que tem ${b} anos idade!`)
        }
    </script>

</body>
</html>
