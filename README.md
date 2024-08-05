# aula-4-fds.uninter
aula 4 exercícios Visual Studio Code site para FDS em html 
<br>
Exercício 1 
<br> http://127.0.0.1:5500/formulario.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" contenhttp://127.0.0.1:5500/formulario.htmlt="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Pedido Pizza</h1>
   <form method="POST" action="teste.jsp">
        Nome: <input type="text" name="nome"><br>
        email:<input type="email" name="email"><br>
        Tamanho:
        <input type="radio" name="tamanho" value="g" checked>Grande
        <input type="radio" name="tamanho" value="m">Medio
        <input type="radio" name="tamanho" value="p">Pequeno
        <br>
        Sabor: <select name = "sabor">
            <option>Calabresa</option>
            <option>Napolitana</option>
            <option>Marguerita</option>

        </select>
        Adicionais:
        <input type = "checkbox" name="borda" value="sim">borda
        <input type = "checkbox" name="queijo" value="sim">queijo
        <br>
        Data entrega:<input type="date" name="dataEntrega">
        <br>
        Comnetário:<br>
        <textarea name="mensagem" rows="10" cols="100"></textarea>
<br>
        <input type="submit">

   </form>
</body> 
</html>
<br>
<head></head>
Exercício 2
<br>


