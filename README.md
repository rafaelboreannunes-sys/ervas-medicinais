<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guia de Ervas Medicinais</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f9f4;
            color: #2d4030;
            margin: 0;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 25px 0;
            background-color: #2e6f40;
            color: #ffffff;
            border-radius: 8px;
            margin-bottom: 30px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: #ffffff;
            border: 1px solid #dcdcdc;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: #1e4d2b;
            margin-top: 0;
        }

        .tag {
            display: inline-block;
            background-color: #e2f0d9;
            color: #2e6f40;
            padding: 4px 10px;
            border-radius: 15px;
            font-size: 0.85rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9rem;
            color: #666;
        }
    </style>
</head>
<body>

    <header>
        <h1>🌿 Guia Prático de Ervas Medicinais</h1>
        <p>Conheça o uso tradicional de plantas medicinais e aromáticas</p>
    </header>

    <main class="container">
        <article class="card">
            <span class="tag">Calmante</span>
            <h3>Camomila</h3>
            <p><strong>Nome científico:</strong> <em>Matricaria chamomilla</em></p>
            <p>Conhecida por suas propriedades suavemente relaxantes, é amplamente utilizada em chás para aliviar a tensão e melhorar o bem-estar.</p>
        </article>

        <article class="card">
            <span class="tag">Digestiva</span>
            <h3>Hortelã</h3>
            <p><strong>Nome científico:</strong> <em>Mentha x piperita</em></p>
            <p>Muito utilizada para refrescar e auxiliar no conforto digestivo após as refeições, além de possuir um aroma estimulante.</p>
        </article>

        <article class="card">
            <span class="tag">Estimulante</span>
            <h3>Alecrim</h3>
            <p><strong>Nome científico:</strong> <em>Rosmarinus officinalis</em></p>
            <p>Planta aromática tradicionalmente associada ao alívio do cansaço mental e ao estímulo da concentração.</p>
        </article>

        <article class="card">
            <span class="tag">Tranquilizante</span>
            <h3>Erva-Cidreira</h3>
            <p><strong>Nome científico:</strong> <em>Melissa officinalis</em></p>
            <p>Famosa por seu sabor suave e cítrico, é perfeita para infusões que ajudam a desacelerar no fim do dia.</p>
        </article>
    </main>

    <footer>
        <p>Nota: O uso de ervas é uma prática tradicional popular. Sempre busque informações de fontes seguras para consumo adequado.</p>
    </footer>

</body>
</html>
