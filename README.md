<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eric Fontanero - Fontaneria Professional</title>
    <style>
        /* Estils generals */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Seccions d'amplada completa */
        .full-width {
            width: 100vw;
            position: relative;
            left: 50%;
            right: 50%;
            margin-left: -50vw;
            margin-right: -50vw;
            padding: 40px 0;
        }

        /* Fons comú per història i equip */
        .seccio-fons {
            background: #f9f9f9;
            margin: 0;
        }

        /* Capçalera */
        header {
            background-color: #1a5a99;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }

        /* Serveis */
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
            background: white;
        }

        /* Equip */
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

        /* Ressenyes */
        .resenyes {
            background: #fff8f0;
        }
        
        .grid-resenyes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        
        .targeta-resenya {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        /* WhatsApp */
        .whatsapp {
            background-color: #25D366;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin: 20px 0;
            transition: transform 0.3s ease;
        }

        .whatsapp:hover {
            transform: scale(1.05);
        }

        /* Formulari */
        form input {
            padding: 10px;
            width: 100%;
            max-width: 400px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        button {
            background: #1a5a99;
            color: white;
            padding: 12px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
        }

        /* Footer */
        footer {
            background: #1a5a99;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
    </style>
    <!-- Font Awesome per icones -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Capçalera -->
    <header class="full-width">
        <div class="container">
            <h1>Eric Fontanero</h1>
            <p>Fontaneria professional i reparacions d'urgència</p>
        </div>
    </header>

    <div class="container">
        <!-- Serveis -->
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
    </div>

    <!-- Història -->
    <div class="full-width seccio-fons">
        <div class="container">
            <h2>📜 La nostra història</h2>
            <p>Tot va començar el 2010, quan Eric Fontanero, amb una eina a una mà i un desig fervent d’ajudar a la gent a l’altra, va decidir obrir un servei de fontaneria de proximitat al barri del Xup (Manresa). Els primers anys van ser de porta en porta, amb una furgoneta de segona mà i un telèfon mòbil que no deixava de repicar. Eric es va guanyar la confiança dels veïns amb la seva honradesa (mai cobrava sense explicar abans què havia fet) i la seva habilitat quirúrgica per arreglar canonades sense fer forats innecessaris.</p>
            
            <p>El 2015, el negoci va donar el salt definitiu quan Sergi "El Nene" (aleshores un aprenent de 19 anys) va proposar crear un servei 24 hores per urgències. Aquesta idea va convertir l’empresa en una llegenda local. La gent explicava com Sergi arribava a les 3 de la matinada, amb ulleres de soldar i una ampolla de coca-cola, per salvar cases inundades.</p>

            <p>El 2018, amb l’ajuda de Ousman "El Guru", un expert en màrqueting que es va unir després de veure Eric arreglar una bassa al seu restaurant preferit, van llançar la campanya "No et neguitegis, nosaltres traiem l’aigua... i les preocupacions". Va ser viral: van aparèixer a ràdios locals i fins i tot van rebre una foto amb un client famós (Puigdemont).</p>

            <p>El 2020, Said, Alias "Saido", va entrar per posar ordre en el caos administratiu. Gràcies a ell, van deixar de perdre factures entre bosses d’eines i van començar a tenir certificacions oficials. La seva frase famosa: "Una canonada ben instal·lada comença per un contracte ben signat".</p>
        </div>
    </div>

    <!-- Equip -->
    <div class="full-width seccio-fons">
        <div class="container">
            <h2>🌟 L'equip que ho fa possible</h2>
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
    </div>

    <!-- Ressenyes -->
    <div class="full-width resenyes">
        <div class="container">
            <h2 style="text-align: center; color: #1a5a99;">📣 Que diuen els nostres clients</h2>
            <div class="grid-resenyes">
                <div class="targeta-resenya">
                    <div style="display: flex; align-items: center; gap: 15px; margin-bottom: 15px;">
                        <div style="width: 50px; height: 50px; background: #1a5a99; border-radius: 50%;"></div>
                        <div>
                            <h4 style="margin: 0;">Montserrat G.</h4>
                            <p style="margin: 0; font-size: 0.9em; color: #666;">Poble Nou, Manresa</p>
                        </div>
                    </div>
                    <p style="font-style: italic;">"A les 2am el nen va deixar el joguet al WC. En Sergi va venir en 20 minuts i ho va solucionar sense fer malbé el Ninot! Heroes amb clau anglesa!"</p>
                    <div style="color: #ffb400; font-size: 1.2em;">★★★★★</div>
                </div>

                <div class="targeta-resenya">
                    <div style="display: flex; align-items: center; gap: 15px; margin-bottom: 15px;">
                        <div style="width: 50px; height: 50px; background: #1a5a99; border-radius: 50%;"></div>
                        <div>
                            <h4 style="margin: 0;">Lluís M.</h4>
                            <p style="margin: 0; font-size: 0.9em; color: #666;">Mion, Manresa</p>
                        </div>
                    </div>
                    <p style="font-style: italic;">"L'Ousman va fer un vídeo divertidíssim de com van arreglar la bassa al meu bar. Ara tothom veu que som seriosos però amb bon rotllo!"</p>
                    <div style="color: #ffb400; font-size: 1.2em;">★★★★★</div>
                </div>

                <div class="targeta-resenya">
                    <div style="display: flex; align-items: center; gap: 15px; margin-bottom: 15px;">
                        <div style="width: 50px; height: 50px; background: #1a5a99; border-radius: 50%;"></div>
                        <div>
                            <h4 style="margin: 0;">Aina R.</h4>
                            <p style="margin: 0; font-size: 0.9em; color: #666;">El Xup, Manresa</p>
                        </div>
                    </div>
                    <p style="font-style: italic;">"El Said em va enviar tot el pressupost amb emojis i detalls que fins i tot jo vaig entendre. Cap empresa explica tan bé on et surten els 20€!"</p>
                    <div style="color: #ffb400; font-size: 1.2em;">★★★★★</div>
                </div>
            </div>
        </div>
    </div>

    <div class="container">
        <!-- Contacte -->
        <div class="contacto">
            <h2>📲 Contacte ràpid</h2>
            <a href="https://wa.me/34694206969" class="whatsapp">
                <i class="fab fa-whatsapp"></i> WhatsApp: 694 20 69 69
            </a>
            <p style="margin: 20px 0;">O omple el formulari:</p>
            <form>
                <input type="text" placeholder="Nom" required>
                <input type="tel" placeholder="Telèfon" required>
                <button type="submit">Demana ajuda</button>
            </form>
        </div>
    </div>

    <!-- Footer -->
    <footer class="full-width">
        <div class="container">
            <p>© 2025 Eric Fontanero - Certificat N°: HB-694206969</p>
            <p>Truca ara: <a href="tel:694206969" style="color: #25D366; text-decoration: none;">694 20 69 69</a></p>
        </div>
    </footer>
</body>
</html>
