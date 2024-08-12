# Exerc-cios-DEW
## Exercício 1: Site simples

**Resposta:**<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        body {
            background-color: #f4f4f4;
        }
        header {
            background-color: hsla(211, 100%, 50%, 0.875);
        }
        footer {
            background-color: darkgray;
        }
    </style>
</head>
<body>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>Rodapé</p>
    </footer>
</body>
</html>

## Exercício 2: Estilização de Texto

**resposta:** <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
            header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
            footer {
                background-color: darkgray;
            }
    </style>
</head>
<body>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
</body>
</html>

## Exercício 3: Adição de Imagens
**Resposta**<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
        img {
            border: 5px solid black;
            }
            header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
            footer {
                background-color: darkgray;
            }
    </style>
</head>
<body>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
    <img src="c:\Users\bezja\OneDrive\Imagens\Capturas de tela\Captura de tela 2024-07-07 154512.png" alt="Descrição da imagem">
</body>
</html>

## Exercício 4: Criação de Links
**Resposta** <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
            header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
            footer {
                background-color: darkgray;
            }
            a {
            font-weight: bold;
            color: blue;
            text-decoration: none;
        }
        a:hover {
            color: red;
        }
    </style>
</head>
<body>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
    <!-- <img src="c:\Users\bezja\OneDrive\Imagens\Capturas de tela\Captura de tela 2024-07-07 154512.png" alt="Descrição da imagem"> -->
    <p>
        Visite o <a href="https://www.google.com" target="_blank">Google</a> ou o <a href="https://www.youtube.com" target="_blank">YouTube</a>.
    </p>
</body>

## Exercício 5: Criação de uma Lista
**Resposta** <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
            header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
            footer {
                background-color: darkgray;
            }
        ul {
            list-style-type: none;
        }
        ul li {
            background-color: yellow;
            margin-bottom: 10px;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
</body>
</html>

## Exercício 6: Criação de Botões
**Resposta** <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
        header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
        footer {
                background-color: darkgray;
        }button {
            background-color: blue;
            color: white;
            border: none;
            padding:10px 20px ;
            border-radius: 15px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
    <button>enviar</button>
</body>
</html>

## Exercício 7: Criação de uma Tabela
**Resposta** <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
        header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
        footer {
                background-color: darkgray;
        }button {
            background-color: blue;
            color: white;
            border: none;
            padding:10px 20px ;
            border-radius: 15px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: darkblue;
        }
        table {
            width: 50%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: gray;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
    <button>enviar</button>
    <table>
        <tr>
            <th>Atributo 1</th>
            <th>Atributo 2</th>
        </tr>
        <tr>
            <td>Linha 1A</td>
            <td>Linha 1B</td>
        </tr>
        <tr>
            <td>Linha 2A</td>
            <td>Linha 2B</td>
        </tr>
    </table>
</body>
</html>

## Exercício 8: Uso de Classes e IDs
**Respostas** <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        .paragrafo-vermelho {
            color: red;
        }
        #paragrafo-azul {
            color: blue;
        }

        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
        header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
        footer {
                background-color: darkgray;
        }
    </style>
</head>
<body>
    <p class="paragrafo-vermelho">Este é o primeiro parágrafo, estilizado com uma classe para ter texto vermelho.</p>
    <p id="paragrafo-azul">Este é o segundo parágrafo, estilizado com um ID para ter texto azul.</p>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
</body>
</html>

## Exercício 9: Estilização de um Formulário
**Resposta** <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        .paragrafo-vermelho {
            color: red;
        }
        #paragrafo-azul {
            color: blue;
        }

        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
        header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
        footer {
                background-color: darkgray;
        }
        input[type="text"] {
            border: 2px solid black;
            padding: 5px;
            font-size: 16px;
            width: 200px;
            margin-right: 10px;
        }
        input[type="submit"] {
            background-color: green;
            color: white;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }

        input[type="submit"]:hover {
            background-color: darkgreen;
        }
    </style>
</head>
<body>
    <p class="paragrafo-vermelho">Este é o primeiro parágrafo, estilizado com uma classe para ter texto vermelho.</p>
    <p id="paragrafo-azul">Este é o segundo parágrafo, estilizado com um ID para ter texto azul.</p>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
    <form action="#" method="post">
        <input type="text" name="nome" placeholder="Digite seu nome">
        <input type="submit" value="Enviar">
</body>
</html>

## Exercício 10: Criação de um Layout com Flexbox
**Resposta**<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Site Simples</title>
    <style>
        .paragrafo-vermelho {
            color: red;
        }
        #paragrafo-azul {
            color: blue;
        }

        p { font-family: Arial; color: green; font-size: 16px;
        }
        body {
            background-color: #f4f4f4;
        }
        header {
                background-color: hsla(211, 100%, 50%, 0.875);
            }
        footer {
                background-color: darkgray;
        }
        input[type="text"] {
            border: 2px solid black;
            padding: 5px;
            font-size: 16px;
            width: 200px;
            margin-right: 10px;
        }
        input[type="submit"] {
            background-color: green;
            color: white;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }

        input[type="submit"]:hover {
            background-color: darkgreen;
        }
        .flex-container {
            display: flex;
            justify-content: space-between;
        }
        .flex-container .box {
            flex: 1;
            margin: 10px;
            padding: 20px;
            color: white;
            text-align: center;
            font-size: 18px;
        }
        .box-1 {
            background-color: red;
        }

        .box-2 {
            background-color: green;
        }

        .box-3 {
            background-color: blue;
        }
    </style>
</head>
<body>
    <div class="flex-container">
        <div class="box box-1">Caixa 1</div>
        <div class="box box-2">Caixa 2</div>
        <div class="box box-3">Caixa 3</div>
    </div>
    <p class="paragrafo-vermelho">Este é o primeiro parágrafo, estilizado com uma classe para ter texto vermelho.</p>
    <p id="paragrafo-azul">Este é o segundo parágrafo, estilizado com um ID para ter texto azul.</p>
    <header>
        <h1>HTML-CSS</h1>
    </header>
    <footer>
        <p>páragrafo</p>
    </footer>
    <form action="#" method="post">
        <input type="text" name="nome" placeholder="Digite seu nome">
        <input type="submit" value="Enviar">
</body>
</html>

## Exercício 11:
