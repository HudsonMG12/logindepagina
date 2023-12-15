<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Cadastro</title>
    <style>
        body {
            background-image: url('fundoteste.png');
            background-size: cover; /* Para cobrir todo o fundo */
            background-repeat: no-repeat; /* Para evitar repetição da imagem */
        }
    </style>
</head>
<body>
    <h1>Cadastro</h1>
    <form action="C:\xampp\htdocs\conexaoWEB\cadstro.php" method="POST">
        <label for="nome">Nome Completo:</label>
        <input type="text" id="nome" name="nome" required>
        <br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>

        <label for="senha">Senha:</label>
        <input type="password" id="senha" name="senha" required>
        <br><br>

        <label for="confirmar_senha">Confirmar Senha:</label>
        <input type="password" id="confirmar_senha" name="confirmar_senha" required>
        <br><br>

        <label for="idade">Idade:</label>
        <input type="number" id="idade" name="idade" required>
        <br><br>

        <label for="genero">Gênero:</label>
        <select id="genero" name="genero">
            <option value="masculino">Masculino</option>
            <option value="feminino">Feminino</option>
            <option value="outro">Outro</option>
        </select>
        <br><br>

        
        <form action="cadstro.php" method="post">
            <!-- Seus campos de entrada aqui -->
        
            <!-- Botão de envio -->
            <input type="submit" name="cadastrar" value="Cadastrar">
        </form>
        

       <!-- <form input type="submit" value="Cadastrar">
    </form> -->
</body>
</html>
