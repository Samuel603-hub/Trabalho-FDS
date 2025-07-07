# Trabalho-FDS
Trabalho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Fundamentos de Desenvolvimento de Software - [Seu Nome]</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Capa -->
    <div class="capa">
        <h2>Fundamentos de Desenvolvimento de Software</h2>
        <p>Atividade Prática</p>
        <p>Profa. Luciane Kanashiro, Me</p>
        <p>Aluno: [Seu Nome]</p>
        <p>Data: [Data de Entrega]</p>
    </div>

    <!-- Título principal -->
    <h1>[Seu Nome]</h1>

    <!-- Parágrafo autobiográfico -->
    <p>
        Olá! Meu nome é [Seu Nome], tenho [sua idade] anos e moro em [sua cidade]. Sou apaixonado por tecnologia, programação e adoro aprender coisas novas. Nos meus tempos livres, gosto de explorar novos hobbies e conhecer culturas diferentes.
    </p>

    <!-- Botão de interação -->
    <button id="mensagemBtn">Clique para ver uma mensagem!</button>
    <div id="mensagem"></div>

    <!-- Lista de hobbies -->
    <ul>
        <li>Fotografia</li>
        <li>Leitura</li>
        <li>Viajar</li>
    </ul>

    <!-- Imagem de um hobby -->
    <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Fotografia" class="hobby-img">

    <!-- Tabela de países -->
    <table>
        <tr>
            <th>País</th>
            <th>Imagem</th>
        </tr>
        <tr>
            <td>Japão</td>
            <td><img src="https://flagcdn.com/40x30/jp.png" alt="Japão"></td>
        </tr>
        <tr>
            <td>Canadá</td>
            <td><img src="https://flagcdn.com/40x30/ca.png" alt="Canadá"></td>
        </tr>
        <tr>
            <td>Itália</td>
            <td><img src="https://flagcdn.com/40x30/it.png" alt="Itália"></td>
        </tr>
    </table>

    <!-- Link de interesse -->
    <p>
        <a href="https://www.tecmundo.com.br" target="_blank">Acesse meu site de tecnologia favorito!</a>
    </p>

    <script src="script.js"></script>
</body>
</html>
body {
    background-color: #f0f4f8;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0 16px;
}

.capa {
    background: #e3eaf2;
    border-radius: 8px;
    padding: 16px;
    margin-bottom: 24px;
    text-align: center;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

h1 {
    color: #2a4d69;
    text-align: center;
    margin-top: 0;
}

p {
    font-size: 1.15em;
    text-align: justify;
    max-width: 700px;
    margin: 16px auto;
}

ul {
    margin: 24px auto;
    max-width: 400px;
    padding-left: 24px;
}

ul li {
    margin-bottom: 16px;
    font-size: 1em;
}

.hobby-img {
    display: block;
    margin: 16px auto;
    width: 220px;
    border-radius: 18px;
    border: 2px solid #aac4e6;
}

table {
    margin: 24px auto;
    border-collapse: collapse;
    background: #fff;
    box-shadow: 0 1px 6px rgba(0,0,0,0.07);
}

table, th, td {
    border: 1px solid #b3cde0;
}

th, td {
    padding: 10px 18px;
    text-align: center;
}

a {
    color: #1e90ff;
    text-decoration: none;
    transition: color 0.3s;
}

a:hover {
    color: #ff6347;
}
document.getElementById('mensagemBtn').addEventListener('click', function() {
    document.getElementById('mensagem').innerText = 'Bem-vindo(a)! Nunca pare de aprender e acreditar no seu potencial!';
});
