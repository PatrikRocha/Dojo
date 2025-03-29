# Dojo
Um espaço que lhe ensina a se defender e a encontrar o equilíbrio entre corpo e espirito
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dojo Taishin - Karatê-Do Tradicional</title>
    <style>
        /* Reset e Variáveis de Cores */
        :root {
            --preto: #000000;
            --branco: #FFFFFF;
            --vermelho: #D00;
            --cinza: #F5F5F5;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            line-height: 1.6;
            color: var(--preto);
        }

        /* Header */
        header {
            background-color: var(--preto);
            color: var(--branco);
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }
        .logo img {
            height: 60px;
            width: auto;
        }
        nav ul {
            display: flex;
            list-style: none;
            gap: 20px;
        }
        nav ul li a {
            color: var(--branco);
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        nav ul li a:hover {
            color: var(--vermelho);
        }

        /* Banner Hero */
        .banner {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://exemplo.com/sua-imagem-de-banner.jpg');
            background-size: cover;
            background-position: center;
            height: 70vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: var(--branco);
            padding: 20px;
        }
        .banner h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        .banner p {
            font-size: 1.2rem;
            max-width: 800px;
            margin-bottom: 30px;
        }
        .btn {
            background-color: var(--vermelho);
            color: var(--branco);
            padding: 12px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #B00;
        }

        /* Seção Sobre */
        .sobre {
            padding: 80px 20px;
            text-align: center;
            background-color: var(--cinza);
        }
        .sobre h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: var(--vermelho);
        }
        .sobre p {
            max-width: 800px;
            margin: 0 auto 30px;
        }

        /* Seção Horários */
        .horarios {
            padding: 80px 20px;
            text-align: center;
        }
        .horarios h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: var(--vermelho);
        }
        table {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #DDD;
            padding: 15px;
            text-align: center;
        }
        th {
            background-color: var(--vermelho);
            color: var(--branco);
        }

        /* Rodapé */
        footer {
            background-color: var(--preto);
            color: var(--branco);
            text-align: center;
            padding: 30px;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
            .banner h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="logo">
            <img src="https://exemplo.com/logo-dojo.png" alt="Logo Dojo Seishin">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#horarios">Horários</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Banner Principal -->
    <section class="banner" id="home">
        <h1>Dojo Taishin</h1>
        <p>Karatê Shorinryu tradicional para todas as idades. Venha fazer parte da nossa família!</p>
        <a href="#contato" class="btn">Agende uma aula experimental</a>
    </section>

    <!-- Seção Sobre -->
    <section class="sobre" id="sobre">
        <h2>Sobre o Dojo</h2>
        <p>Fundado em 2025 pelo Sensei Patrik da Rocha, o Dojo Taishin segue os princípios do karatê Shorinryu: respeito, disciplina e excelência técnica.</p>
        <p>Nossas aulas são adaptadas para crianças, adolescentes e adultos, com foco no desenvolvimento físico e mental.</p>
    </section>

    <!-- Seção Horários -->
    <section class="horarios" id="horarios">
        <h2>Horários das Aulas</h2>
        <table>
            <tr>
                <th>Turma</th>
                <th>Dias</th>
                <th>Horário</th>
            </tr>
            <tr>
                <td>Infantil (6-12 anos)</td>
                <td>Segunda e Quarta</td>
                <td>18h - 19h</td>
            </tr>
            <tr>
                <td>Adultos (a partir de 13 anos)</td>
                <td>Terça e Quinta</td>
                <td>20h - 21h30</td>
            </tr>
        </table>
    </section>

    <!-- Rodapé -->
    <footer id="contato">
        <p>Entre em contato: (11) 99911-8999 | patrikrch321@gmail.com</p>
        <p>&copy; 2025 Dojo Taishin. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
