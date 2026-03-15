<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clube de Patas | Adoção Responsável</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #fdfaf5;
            color: #444;
        }

        /* Menu */
        header {
            background-color: #ffffff;
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #ff9f43;
        }

        /* Banner Principal */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), 
                        url('https://images.unsplash.com/photo-1541591047357-9191ff9f30b6?auto=format&fit=crop&w=1200');
            background-size: cover;
            background-position: center;
            height: 350px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .hero h1 { font-size: 2.5rem; margin-bottom: 10px; }

        /* Grade de Animais */
        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: 0.3s;
        }

        .card:hover { transform: translateY(-8px); }

        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .info {
            padding: 20px;
            text-align: center;
        }

        .info h3 { color: #ff9f43; margin-bottom: 10px; }

        .btn-adotar {
            background-color: #ff9f43;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 50px;
            cursor: pointer;
            font-weight: bold;
            width: 100%;
            transition: 0.3s;
        }

        .btn-adotar:hover { background-color: #ee5253; }

        footer {
            text-align: center;
            padding: 30px;
            background: #333;
            color: white;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">🐾 Clube de Patas</div>
        <p>Adoção e Carinho</p>
    </header>

    <section class="hero">
        <h1>Clube de Patas</h1>
        <p>Não compre um amigo, adote uma história!</p>
    </section>

    <main class="container">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1543466835-00a7907e9de1?auto=format&fit=crop&w=500" alt="Cão">
            <div class="info">
                <h3>Bento</h3>
                <p>Cachorro • 2 anos • Dócil</p><br>
                <button class="btn-adotar">Quero Adotar</button>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?auto=format&fit=crop&w=500" alt="Gato">
            <div class="info">
                <h3>Mel</h3>
                <p>Gata • 1 ano • Calma</p><br>
                <button class="btn-adotar">Quero Adotar</button>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1537151608828-ea2b11777ee8?auto=format&fit=crop&w=500" alt="Cão">
            <div class="info">
                <h3>Thor</h3>
                <p>Cachorro • 4 anos • Protetor</p><br>
                <button class="btn-adotar">Quero Adotar</button>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2026 Clube de Patas - Criado com amor para os animais</p>
    </footer>

</body>
</html>
