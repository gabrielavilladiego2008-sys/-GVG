<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Atardecer - Presentación</title>
    <style>
        :root {
            --bg-primary: #0f172a;
            --bg-card: #1e293b;
            --accent-orange: #f97316;
            --accent-red: #ef4444;
            --accent-yellow: #f59e0b;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-primary);
            color: var(--text-main);
            line-height: 1.6;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            padding: 3rem 1rem;
            background: linear-gradient(135deg, #1e1b4b 0%, #431407 50%, #7c2d12 100%);
            border-radius: 16px;
            margin-bottom: 2rem;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.5);
        }

        header h1 {
            font-size: 2.8rem;
            letter-spacing: 2px;
            text-transform: uppercase;
            background: linear-gradient(to right, #fbbf24, #f97316, #ef4444);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 0.5rem;
        }

        header p {
            color: #cbd5e1;
            font-size: 1.2rem;
        }

        .intro-card {
            background-color: var(--bg-card);
            border-left: 5px solid var(--accent-orange);
            padding: 1.5rem 2rem;
            border-radius: 8px;
            margin-bottom: 2.5rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }

        .intro-card h2 {
            color: var(--accent-yellow);
            margin-bottom: 0.8rem;
        }

        .intro-card ul {
            list-style-type: disc;
            padding-left: 1.5rem;
        }

        .intro-card li {
            margin-bottom: 0.5rem;
        }

        .section-title {
            font-size: 1.8rem;
            color: var(--accent-yellow);
            border-bottom: 2px solid #334155;
            padding-bottom: 0.5rem;
            margin: 2.5rem 0 1.5rem 0;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .card {
            background-color: var(--bg-card);
            border-radius: 12px;
            padding: 1.5rem;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            border: 1px solid #334155;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(249, 115, 22, 0.2);
        }

        .card h3 {
            color: var(--accent-orange);
            font-size: 1.3rem;
            margin-bottom: 0.8rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .card p {
            color: #cbd5e1;
            font-size: 0.95rem;
            margin-bottom: 0.6rem;
        }

        .card .highlight {
            color: var(--accent-yellow);
            font-weight: 600;
        }

        .china-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.2rem;
        }

        .china-card {
            background: linear-gradient(145deg, #1e293b, #0f172a);
            border: 1px solid #334155;
            border-radius: 10px;
            padding: 1.2rem;
        }

        .china-card h4 {
            color: #f43f5e;
            font-size: 1.1rem;
            margin-bottom: 0.4rem;
        }

        .china-card p {
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        .conclusion {
            background: linear-gradient(135deg, #431407 0%, #1e293b 100%);
            border-radius: 12px;
            padding: 2rem;
            text-align: center;
            margin-top: 3rem;
            border: 1px solid var(--accent-orange);
        }

        .conclusion h2 {
            color: var(--accent-yellow);
            margin-bottom: 1rem;
        }

        .conclusion p {
            font-size: 1.1rem;
            color: #f1f5f9;
            max-width: 800px;
            margin: 0 auto;
        }

        footer {
            text-align: center;
            color: var(--text-muted);
            margin-top: 3rem;
            font-size: 0.85rem;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>El Atardecer</h1>
        <p>Un recorrido por los atardeceres del mundo</p>
    </header>

    <div class="intro-card">
        <h2>¿Qué es un atardecer?</h2>
        <ul>
            <li>Es el momento en que el Sol desaparece por el horizonte.</li>
            <li>El cielo puede adquirir colores como amarillo, naranja, rojo, rosado y morado.</li>
            <li>El paisaje cambia dependiendo del lugar donde se observe.</li>
        </ul>
    </div>

    <h2 class="section-title">Atardeceres en el Mundo</h2>

    <div class="grid">
        <!-- Colombia -->
        <div class="card">
            <h3>🇨🇴 Colombia</h3>
            <p>Los atardeceres pueden observarse sobre montañas, playas y ciudades.</p>
            <p><span class="highlight">Paisajes destacados:</span> Cartagena, La Guajira o los Llanos Orientales.</p>
            <p>Destacan los colores cálidos y los paisajes naturales.</p>
            <p>Cerca del Ecuador, el atardecer suele ocurrir alrededor de las 18:00 y cambia poco durante el año.</p>
        </div>

        <!-- Brasil -->
        <div class="card">
            <h3>🇧🇷 Brasil</h3>
            <p>Sus playas ofrecen grandes paisajes para observar el atardecer.</p>
            <p><span class="highlight">Paisaje destacado:</span> Río de Janeiro.</p>
            <p>El Sol se puede observar sobre el océano mientras ilumina las montañas.</p>
            <p>Varía mucho por su enorme extensión; cerca del Ecuador los cambios son pequeños, mientras que al sur son mayores.</p>
        </div>

        <!-- México -->
        <div class="card">
            <h3>🇲🇽 México</h3>
            <p>Tiene atardeceres muy llamativos en sus playas y zonas desérticas.</p>
            <p><span class="highlight">Paisajes destacados:</span> Cancún o Baja California.</p>
            <p>El cielo puede reflejarse sobre el mar.</p>
            <p>El Sol se pone aproximadamente entre las 17:30 y las 20:30, dependiendo de la ciudad y la estación del año.</p>
        </div>

        <!-- España -->
        <div class="card">
            <h3>🇪🇸 España</h3>
            <p>Los atardeceres combinan el cielo con el mar, las montañas y las ciudades.</p>
            <p><span class="highlight">Paisajes destacados:</span> Islas Canarias o Barcelona.</p>
            <p>En verano suele anochecer bastante tarde, especialmente en el oeste y norte.</p>
        </div>

        <!-- Japón -->
        <div class="card">
            <h3>🇯🇵 Japón</h3>
            <p>Los atardeceres pueden observarse junto al mar y las montañas.</p>
            <p><span class="highlight">Paisaje destacado:</span> Monte Fuji.</p>
            <p>La silueta del monte puede verse mientras el cielo cambia de color.</p>
            <p>El atardecer cambia notablemente entre verano e invierno.</p>
        </div>

        <!-- Estados Unidos -->
        <div class="card">
            <h3>🇺🇸 Estados Unidos</h3>
            <p>El atardecer ilumina las formaciones rocosas y crea diferentes tonos en el paisaje.</p>
            <p><span class="highlight">Paisaje destacado:</span> Gran Cañón.</p>
            <p>Gran variación según el estado; en verano los días son especialmente largos en el norte.</p>
        </div>

        <!-- Australia -->
        <div class="card">
            <h3>🇦🇺 Australia</h3>
            <p>El atardecer cambia el color de la gran formación rocosa y crea un paisaje impresionante.</p>
            <p><span class="highlight">Paisaje destacado:</span> Uluru.</p>
            <p>El sur presenta grandes diferencias entre verano e invierno; el norte tropical tiene cambios menores.</p>
        </div>

        <!-- Sudáfrica -->
        <div class="card">
            <h3>🇿🇦 Sudáfrica</h3>
            <p>El atardecer cambia durante el año debido a las estaciones.</p>
            <p><span class="highlight">Horarios:</span> En verano entre 18:30 y 20:00; en invierno entre 17:00 y 18:00.</p>
            <p>En lugares como Ciudad del Cabo, los atardeceres de verano pueden ser especialmente largos y coloridos.</p>
        </div>
    </div>

    <h2 class="section-title">🇨🇳 Destacados de China</h2>
    <div class="china-grid">
        <div class="china-card">
            <h4>La Gran Muralla China</h4>
            <p>Una de las maravillas del mundo. Sucesión infinita de murallas y torres entre montañas impresionantes.</p>
        </div>
        <div class="china-card">
            <h4>Ciudad Prohibida - Beijing</h4>
            <p>Palacio imperial con más de 900 edificios. Patrimonio Mundial y símbolo de la dinastía Ming.</p>
        </div>
        <div class="china-card">
            <h4>El Bund - Shanghai</h4>
            <p>Zona moderna frente al río Huangpu, famosa por sus rascacielos futuristas y arquitectura colonial.</p>
        </div>
        <div class="china-card">
            <h4>Guerreros de Terracota - Xi'an</h4>
            <p>Más de 8,000 figuras a tamaño real creadas para proteger al primer emperador Qin.</p>
        </div>
        <div class="china-card">
            <h4>Zhangjiajie</h4>
            <p>Paisaje natural que inspiró escenarios de la película Avatar: pilares de piedra flotando entre niebla.</p>
        </div>
        <div class="china-card">
            <h4>Río Li / Guilin</h4>
            <p>Navegación escénica entre montañas kársticas, uno de los paisajes más bellos de China.</p>
        </div>
    </div>

    <div class="conclusion">
        <h2>Conclusión</h2>
        <p>El atardecer es un fenómeno que podemos observar en todo el mundo, pero cada país ofrece un paisaje diferente. Las montañas, playas, desiertos y ciudades hacen que cada atardecer sea único y especial.</p>
    </div>

    <footer>
        <p>Presentación adaptada a HTML - El Atardecer</p>
    </footer>
</div>

</body>
</html>
