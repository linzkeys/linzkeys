<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre mim - Pedro Acioli</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <style>
        body {
            background-color: #f0f4f8;
            color: #4a5568;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
            background-color: #ffffff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            border-radius: 8px;
        }
        .section {
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid #e2e8f0;
        }
        .section-title {
            color: #5a67d8;
            margin-bottom: 1rem;
            font-weight: 600;
        }
        .skill-badge {
            display: inline-block;
            background-color: #ebf4ff;
            color: #4c51bf;
            padding: 0.5rem 1rem;
            border-radius: 9999px;
            margin-right: 0.5rem;
            margin-bottom: 0.5rem;
            font-size: 0.875rem;
        }
        .work-badge {
            display: inline-block;
            background-color: #e6fffa;
            color: #2c7a7b;
            padding: 0.5rem 1rem;
            border-radius: 9999px;
            margin-right: 0.5rem;
            margin-bottom: 0.5rem;
            font-size: 0.875rem;
        }
        .hobby-item {
            display: flex;
            align-items: center;
            margin-bottom: 0.75rem;
        }
        .hobby-icon {
            color: #6b46c1;
            margin-right: 0.75rem;
            font-size: 1.25rem;
        }
        footer {
            text-align: center;
            padding-top: 1.5rem;
            color: #718096;
        }
    </style>
</head>
<body>
    <div class="container my-8">
        <header class="text-center mb-8">
            <h1 class="text-4xl font-bold text-indigo-700 mb-2">Pedro Acioli</h1>
            <div class="w-24 h-1 bg-indigo-500 mx-auto mb-4"></div>
        </header>

        <section class="section">
            <h2 class="section-title text-2xl">Sobre mim</h2>
            <p>
                Nasci em Recife - Pernambuco, sou fluente em inglês e gosto de rock. 
                Sou apaixonado por tecnologia e sempre busco aprender novas habilidades.
            </p>
        </section>

        <section class="section">
            <h2 class="section-title text-2xl">Competências Técnicas</h2>
            <div>
                <span class="skill-badge">Python</span>
                <span class="skill-badge">JavaScript</span>
                <span class="skill-badge">MySQL</span>
                <span class="skill-badge">C</span>
                <span class="skill-badge">C++</span>
                <span class="skill-badge">C#</span>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title text-2xl">Experiência Profissional</h2>
            <div>
                <span class="work-badge">Governo federal dos EUA</span>
                <span class="work-badge">ABIN</span>
                <span class="work-badge">KGB</span>
                <span class="work-badge">CIA</span>
                <span class="work-badge">FBI</span>
                <span class="work-badge">MOSSAD</span>
                <span class="work-badge">Batalhão Azov</span>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title text-2xl">Hobbies</h2>
            <div>
                <div class="hobby-item">
                    <i class="fas fa-language hobby-icon"></i>
                    <span>Aprender idiomas</span>
                </div>
                <div class="hobby-item">
                    <i class="fas fa-book hobby-icon"></i>
                    <span>Ler sobre filosofia e geopolítica</span>
                </div>
                <div class="hobby-item">
                    <i class="fas fa-chess hobby-icon"></i>
                    <span>Jogar jogos de estratégia</span>
                </div>
            </div>
        </section>

        <footer>
            <p>Entre em contato: <a href="mailto:anotaopix@outlook.com.br" class="text-indigo-600 hover:text-indigo-800">anotaopix@outlook.com.br</a></p>
            <p class="text-sm mt-2">&copy; 2023 Pedro Acioli. Todos os direitos reservados.</p>
        </footer>
    </div>
</body>
</html>
