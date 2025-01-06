<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reduce el Desperdicio de Alimentos</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(to right, #f7b733, #fc4a1a);
            color: white;
            text-align: center;
            padding: 2rem 1rem;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }
        nav {
            background: #333;
            color: white;
            display: flex;
            justify-content: center;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2rem;
            max-width: 1200px;
            margin: auto;
        }
        section h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        .cta {
            background: #4caf50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin: 2rem 0;
            border-radius: 5px;
        }
        .cta button {
            background: white;
            color: #4caf50;
            border: none;
            padding: 1rem 2rem;
            font-size: 1.2rem;
            border-radius: 5px;
            cursor: pointer;
        }
        .cta button:hover {
            background: #3e8e41;
            color: white;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card-body {
            padding: 1rem;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Reduce el Desperdicio de Alimentos</h1>
        <p>"Aporta tu grano de arroz y transforma el mundo."</p>
    </header>
    <nav>
        <a href="#problema">El Problema</a>
        <a href="#solucion">Nuestra Solución</a>
        <a href="#impacto">Impacto</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="problema">
        <h2>El Problema</h2>
        <p>Cada año, un tercio de los alimentos producidos a nivel mundial se desperdicia, mientras millones de personas sufren hambre. Este desperdicio no solo afecta a quienes no tienen acceso a alimentos, sino que también tiene un gran impacto en el medio ambiente.</p>
    </section>
    <section id="solucion">
        <h2>Nuestra Solución</h2>
        <div class="grid">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Redistribución de alimentos">
                <div class="card-body">
                    <h3>Redistribución de alimentos</h3>
                    <p>Trabajamos con ONG's y empresas para redirigir alimentos excedentes hacia quienes más los necesitan.</p>
                </div>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Conciencia social">
                <div class="card-body">
                    <h3>Conciencia social</h3>
                    <p>Promovemos campañas para reducir el desperdicio desde los hogares y las comunidades.</p>
                </div>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Impacto ambiental">
                <div class="card-body">
                    <h3>Reducción del impacto ambiental</h3>
                    <p>Disminuimos el desperdicio para reducir emisiones de CO₂ y proteger el planeta.</p>
                </div>
            </div>
        </div>
    </section>
    <section id="impacto">
        <h2>Impacto</h2>
        <p>Con tu ayuda, podemos redistribuir alimentos, alimentar a miles de personas y reducir toneladas de desperdicios al año.</p>
    </section>
    <section class="cta">
        <h3>¡Únete a nuestra misión!</h3>
        <p>Haz la diferencia y contribuye al cambio. Cada acción cuenta.</p>
        <button onclick="alert('¡Gracias por unirte!')">Participar</button>
    </section>
    <footer>
        <p>&copy; 2025 Reduce el Desperdicio - Todos los derechos reservados</p>
    </footer>
</body>
</html>
