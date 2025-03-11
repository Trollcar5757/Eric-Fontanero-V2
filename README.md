<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eric Fontanero - Fontaneria Professional</title>
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
        .historia-equip {
            background: #f9f9f9;
            padding: 40px 0;
            margin: 30px 0;
        }
        .equip-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        .membre-equip {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .alias {
            color: #1a5a99;
            font-style: italic;
            margin: 5px 0;
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
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Eric Fontanero</h1>
        <p>Fontaneria professional i reparacions d'urgència</p>
    </header>

    <div class="container">
        <!-- Secció Serveis -->
        <h2>📌 Els nostres serveis</h2>
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

        <!-- Secció Història i Equip -->
        <div class="historia-equip">
            <h2>📜 La nostra història</h2>
            <p>Fundada el 2010 per Eric Fontanero, hem crescut de ser un petit negoci local a convertir-nos en referència del sector gràcies al nostre compromís i professionalitat.</p>

            <h2 style="margin-top: 40px;">🌟 L'equip que ho fa possible</h2>
            <div class="equip-grid">
                <div class="membre-equip">
                    <h3>Said</h3>
                    <p class="alias">"Saido"</p>
                    <p>Secretari Executiu<br>Expert en gestió i organització</p>
                </div>

                <div class="membre-equip">
                    <h3>Sergi</h3>
                    <p class="alias">"El Nene"</p>
                    <p>Vicepresident Operatiu<br>Estratega de camp de batalla</p>
                </div>

                <div class="membre-equip">
                    <h3>Eric</h3>
                    <p class="alias">"El Fontanero"</p>
                    <p>CEO i Fundador<br>15+ anys salvant llars</p>
                </div>

                <div class="membre-equip">
                    <h3>Ousman</h3>
                    <p class="alias">"El Guru"</p>
                    <p>Cap de Màrqueting<br>Geni de les xarxes socials</p>
                </div>
            </div>
        </div>

        <!-- Secció Contacte -->
        <div class="contacto">
            <h2>📲 Contacte ràpid</h2>
            <a href="https://wa.me/34694206969" class="whatsapp">
                <i class="fab fa-whatsapp"></i> WhatsApp: 694 20 69 69
            </a>
            <p style="margin: 20px 0;">O omple el formulari:</p>
            <form>
                <input type="text" placeholder="Nom" required style="padding: 10px; width: 80%; max-width: 300px; margin: 5px;">
                <input type="tel" placeholder="Telèfon" required style="padding: 10px; width: 80%; max-width: 300px; margin: 5px;">
                <button type="submit" style="background: #1a5a99; color: white; padding: 10px 25px; border: none; border-radius: 5px; margin: 10px;">
                    Demana ajuda
                </button>
            </form>
        </div>
    </div>

    <footer>
        <p>© 2025 Eric Fontanero - Certificat N°: HB-694206969</p>
        <p>Truca ara: <a href="tel:694206969" style="color: #25D366; text-decoration: none;">694 20 69 69</a></p>
    </footer>
</body>
</html>
