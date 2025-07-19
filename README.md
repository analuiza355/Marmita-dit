# Marmita-fit
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Marmi Fit - Marmitas Fitness</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background: #f5f7fa;
            color: #333;
        }
        header {
            background: #28a745;
            padding: 20px;
            color: white;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-weight: 700;
            letter-spacing: 2px;
        }
        .container {
            max-width: 960px;
            margin: 30px auto;
            padding: 0 15px;
        }
        .intro {
            text-align: center;
            margin-bottom: 40px;
            font-size: 1.1rem;
            color: #555;
        }
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fill,minmax(280px,1fr));
            gap: 25px;
        }
        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgb(0 0 0 / 0.15);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .card-body {
            padding: 15px;
            flex-grow: 1;
        }
        .card-body h3 {
            margin-top: 0;
            margin-bottom: 10px;
            color: #28a745;
        }
        .card-body p {
            margin: 0 0 15px;
            font-size: 0.95rem;
            color: #666;
        }
        .price {
            font-weight: 700;
            font-size: 1.2rem;
            color: #222;
            margin-bottom: 15px;
        }
        .btn-buy {
            background: #28a745;
            border: none;
            color: white;
            padding: 12px;
            width: 100%;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 0 0 10px 10px;
            transition: background 0.3s ease;
        }
        .btn-buy:hover {
            background: #218838;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #e2e8f0;
            color: #555;
            margin-top: 40px;
            font-size: 0.9rem;
        }
        @media(max-width:400px){
            .card img {
                height: 140px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Marmi Fit</h1>
        <p>Marmitas Fitness Saudáveis e Deliciosas</p>
    </header>
    <div class="container">
        <p class="intro">Confira nosso cardápio de marmitas saudáveis, feitas com ingredientes frescos para uma alimentação balanceada. Preços justos para você cuidar da saúde sem pesar no bolso!</p>
        <div class="cards">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1604908177523-02f6c4c4a2f3?auto=format&fit=crop&w=600&q=80" alt="Marmita Frango com Legumes" />
                <div class="card-body">
                    <h3>Marmita Frango com Legumes</h3>
                    <p>Frango grelhado, brócolis, cenoura e arroz integral.</p>
                    <div class="price">R$ 18,90</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?auto=format&fit=crop&w=600&q=80" alt="Marmita Vegetariana" />
                <div class="card-body">
                    <h3>Marmita Vegetariana</h3>
                    <p>Mix de legumes, tofu grelhado e quinoa.</p>
                    <div class="price">R$ 17,50</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1562967916-eb82221dfb35?auto=format&fit=crop&w=600&q=80" alt="Marmita Salmão com Aspargos" />
                <div class="card-body">
                    <h3>Marmita Salmão com Aspargos</h3>
                    <p>Salmão grelhado, aspargos e arroz integral.</p>
                    <div class="price">R$ 25,00</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=600&q=80" alt="Marmita Strogonoff Fit" />
                <div class="card-body">
                    <h3>Marmita Strogonoff Fit</h3>
                    <p>Strogonoff de frango light com arroz integral.</p>
                    <div class="price">R$ 19,90</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

        </div>
    </div>
    <footer>
        &copy; 2025 Marmi Fit - Todos os direitos reservados
    </footer>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Marmi Fit - Marmitas Fitness</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background: #f5f7fa;
            color: #333;
        }
        header {
            background: #28a745;
            padding: 20px;
            color: white;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-weight: 700;
            letter-spacing: 2px;
        }
        .container {
            max-width: 960px;
            margin: 30px auto;
            padding: 0 15px;
        }
        .intro {
            text-align: center;
            margin-bottom: 40px;
            font-size: 1.1rem;
            color: #555;
        }
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fill,minmax(280px,1fr));
            gap: 25px;
        }
        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgb(0 0 0 / 0.15);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .card-body {
            padding: 15px;
            flex-grow: 1;
        }
        .card-body h3 {
            margin-top: 0;
            margin-bottom: 10px;
            color: #28a745;
        }
        .card-body p {
            margin: 0 0 15px;
            font-size: 0.95rem;
            color: #666;
        }
        .price {
            font-weight: 700;
            font-size: 1.2rem;
            color: #222;
            margin-bottom: 15px;
        }
        .btn-buy {
            background: #28a745;
            border: none;
            color: white;
            padding: 12px;
            width: 100%;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 0 0 10px 10px;
            transition: background 0.3s ease;
        }
        .btn-buy:hover {
            background: #218838;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #e2e8f0;
            color: #555;
            margin-top: 40px;
            font-size: 0.9rem;
        }
        @media(max-width:400px){
            .card img {
                height: 140px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Marmi Fit</h1>
        <p>Marmitas Fitness Saudáveis e Deliciosas</p>
    </header>
    <div class="container">
        <p class="intro">Confira nosso cardápio de marmitas saudáveis, feitas com ingredientes frescos para uma alimentação balanceada. Preços justos para você cuidar da saúde sem pesar no bolso!</p>
        <div class="cards">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1604908177523-02f6c4c4a2f3?auto=format&fit=crop&w=600&q=80" alt="Marmita Frango com Legumes" />
                <div class="card-body">
                    <h3>Marmita Frango com Legumes</h3>
                    <p>Frango grelhado, brócolis, cenoura e arroz integral.</p>
                    <div class="price">R$ 18,90</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?auto=format&fit=crop&w=600&q=80" alt="Marmita Vegetariana" />
                <div class="card-body">
                    <h3>Marmita Vegetariana</h3>
                    <p>Mix de legumes, tofu grelhado e quinoa.</p>
                    <div class="price">R$ 17,50</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1562967916-eb82221dfb35?auto=format&fit=crop&w=600&q=80" alt="Marmita Salmão com Aspargos" />
                <div class="card-body">
                    <h3>Marmita Salmão com Aspargos</h3>
                    <p>Salmão grelhado, aspargos e arroz integral.</p>
                    <div class="price">R$ 25,00</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=600&q=80" alt="Marmita Strogonoff Fit" />
                <div class="card-body">
                    <h3>Marmita Strogonoff Fit</h3>
                    <p>Strogonoff de frango light com arroz integral.</p>
                    <div class="price">R$ 19,90</div>
                    <button class="btn-buy">Comprar</button>
                </div>
            </div>

        </div>
    </div>
    <footer>
        &copy; 2025 Marmi Fit - Todos os direitos reservados
    </footer>
</body>
</html>
