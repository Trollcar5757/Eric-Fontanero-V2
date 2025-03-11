<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eric Fontanero S.L - Fontaneria Professional</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1a5a99;
            color: white;
            text-align: center;
            padding: 2rem;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 40px 0;
        }
        .service-card {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
        }
        .contacto {
            background-color: #f5f5f5;
            padding: 40px 20px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        .whatsapp {
            background-color: #25D366;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin: 20px 0;
        }
        .imatge-urgent {
            width: 100%;
            max-width: 600px;
            display: block;
            margin: 20px auto;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>
    <header>
        <h1>Eric Fontanero S.L</h1>
        <p>Fontaneria professional i reparacions d'urgència</p>
    </header>

    <div class="container">
        <h2>Els nostres serveis</h2>
        <div class="services">
            <div class="service-card">
                <h3>Reparacions d'urgència</h3>
                <p>24 hores - 365 dies l'any</p>
            </div>
            <div class="service-card">
                <h3>Canvi de canonades</h3>
                <p>Materials de primera qualitat</p>
            </div>
            <div class="service-card">
                <h3>Desembassaments</h3>
                <p>Solucions ràpides i efectives</p>
            </div>
        </div>

        <!-- Nova secció amb imatge i telèfon actualitzat -->
        <div style="text-align: center; margin: 40px 0;">
            <h2>🚰 Urgències de fontaneria</h2>
            <img src="https://source.unsplash.com/600x400/?plumbing" alt="Fontaneria professional" class="imatge-urgent">
            <p>No esperis més! Contacta amb nosaltres ara mateix:</p>
            <a href="https://wa.me/34694206969" class="whatsapp">
                <i class="fab fa-whatsapp"></i> WhatsApp: 694 20 69 69
            </a>
            <p style="margin: 10px;">O truca ara: <a href="tel:694206969">694 20 69 69</a></p>
        </div>
    </div>

    <div class="contacto">
        <div class="container">
            <h2>Contacte ràpid</h2>
            <a href="tel:694206969" class="whatsapp">
                <i class="fab fa-whatsapp"></i> Truca ara: 694 20 69 69
            </a>
            <p>O omple el formulari i et trucarem:</p>
            <form>
                <input type="text" placeholder="Nom" required style="padding: 10px; margin: 5px; width: 80%; max-width: 300px;">
                <br>
                <input type="tel" placeholder="Telèfon" required style="padding: 10px; margin: 5px; width: 80%; max-width: 300px;">
                <br>
                <button type="submit" style="padding: 10px 20px; margin: 10px; background-color: #1a5a99; color: white; border: none; border-radius: 5px;">
                    Demana pressupost
                </button>
            </form>
        </div>
    </div>

    <footer>
        <p>© 2025 Eric Fontanero S.L - Fontaneria professional</p>
        <p>Horari: 24h/365 dies - Certificat oficial N°: 12345678A</p>
    </footer>
</body>
</html>
