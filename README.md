# saddam
Pagina web
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía Turística Guatemala - Descubre la Magia de Centro América</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #2c5aa0, #1e3d72);
            color: white;
            text-align: center;
            padding: 3rem 1rem;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.1rem;
            margin: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            background: white;
            margin: 20px 0;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .intro-section {
            background: linear-gradient(135deg, #e8f4fd, #f0e8fd);
            border: 2px solid #4285f4;
        }
        .maps-link, .contact-btn {
            display: inline-block;
            background: #4285f4;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin: 10px 10px 10px 0;
            transition: background 0.3s, transform 0.2s;
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }
        .maps-link:hover, .contact-btn:hover {
            background: #3367d6;
            transform: translateY(-2px);
        }
        .secondary-btn {
            background: #34a853;
        }
        .secondary-btn:hover {
            background: #1e8c4a;
        }
        h1, h2 {
            color: #2c5aa0;
        }
        h2 {
            border-bottom: 3px solid #4285f4;
            padding-bottom: 10px;
        }
        ul, ol {
            padding-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        .highlight {
            background: #e8f4fd;
            padding: 15px;
            border-left: 5px solid #4285f4;
            margin: 15px 0;
            border-radius: 5px;
        }
        .highlight-warning {
            background: #fff3e0;
            border-left-color: #ff9800;
        }
        .highlight-success {
            background: #e8f5e9;
            border-left-color: #34a853;
        }
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 20px 0;
        }
        .card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border-left: 5px solid #4285f4;
        }
        .price {
            font-size: 1.5rem;
            color: #2c5aa0;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
            margin-top: 40px;
        }
        @media (max-width: 768px) {
            header h1 {
                font-size: 1.8rem;
            }
            .container {
                padding: 10px;
            }
            .section {
                padding: 15px;
            }
            .grid-2 {
                grid-template-columns: 1fr;
            }
            .maps-link, .contact-btn {
                display: block;
                text-align: center;
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🌍 Guía Turística de Guatemala 🌍</h1>
        <p>¡Descubre la magia de Centro América! Naturaleza, cultura antigua y aventura te esperan</p>
    </header>

    <div class="container">
        <!-- Introducción -->
        <div class="section intro-section">
            <h2>¡Bienvenido a Guatemala!</h2>
            <p>Guatemala es un destino increíble con <strong>paisajes asombrosos, historia milenaria y gente acogedora</strong>. Desde las ruinas mayas hasta volcanes activos, lagos cristalinos y selvas vírgenes, tenemos todo lo que necesitas para una aventura inolvidable.</p>
            <div class="highlight">
                <strong>✨ ¿Por qué visitar Guatemala?</strong>
                <ul>
                    <li>🏛️ Patrimonio Maya: Descubre civilizaciones antiguas en Tikal y Antigua</li>
                    <li>🌋 Naturaleza Espectacular: Volcanes, lagos y selvas tropicales</li>
                    <li>🎨 Cultura Vibrante: Mercados tradicionales, artesanías y gastronomía única</li>
                    <li>💰 Precios Accesibles: Un destino económico con lujo y confort</li>
                    <li>🤝 Gente Acogedora: Locales amables y hospitalarios</li>
                </ul>
            </div>
        </div>

        <!-- Ubicación Central -->
        <div class="section">
            <h2>📍 Ubicación y Contacto</h2>
            <p>Nuestra oficina central está ubicada en el corazón de Guatemala, lista para ayudarte a planificar tu viaje perfecto:</p>
            <a href="https://maps.app.goo.gl/9Vz3eJcdgpZAnLv36" target="_blank" class="maps-link">
                🗺️ Ver Ubicación en Google Maps
            </a>
            <div class="highlight">
                <strong>📌 Dirección:</strong> Central de Guatemala<br>
                <strong>🕐 Horario de Atención:</strong> Lunes a Domingo, 6:00 AM - 8:00 PM<br>
                <strong>📱 Contacto Principal:</strong> WhatsApp disponible para consultas y reservas<br>
                <strong>✈️ Acceso:</strong> A 20 minutos del Aeropuerto La Aurora (MGA)
            </div>
        </div>

        <!-- Información Práctica -->
        <div class="section">
            <h2>💡 Información Práctica para tu Viaje</h2>
            <div class="grid-2">
                <div class="card">
                    <h3>💵 Moneda y Dinero</h3>
                    <p><strong>Moneda oficial:</strong> Quetzal Guatemalteco (Q)</p>
                    <p><strong>Conversión aproximada:</strong> 1 USD ≈ 7-8 Q</p>
                    <p>Los USD se aceptan en muchos lugares turísticos. Hay cajeros automáticos en ciudades principales.</p>
                </div>
                <div class="card">
                    <h3>📅 Mejor Época para Visitar</h3>
                    <p><strong>Temporada seca:</strong> Noviembre - Abril (recomendado)</p>
                    <p><strong>Temporada lluviosa:</strong> Mayo - Octubre</p>
                    <p>¡Se puede visitar todo el año! El clima varía según la altitud.</p>
                </div>
                <div class="card">
                    <h3>🗣️ Idioma</h3>
                    <p><strong>Idioma oficial:</strong> Español</p>
                    <p>El inglés se habla en zonas turísticas. Nuestros guías dominan múltiples idiomas.</p>
                    <p><em>Frases útiles:</em> "¿Cuánto cuesta?" / "Gracias"</p>
                </div>
                <div class="card">
                    <h3>🎫 Documentos Necesarios</h3>
                    <p><strong>Visa:</strong> Muchas nacionalidades NO requieren visa para turismo (hasta 90 días)</p>
                    <p><strong>Pasaporte:</strong> Válido por 6 meses mínimo</p>
                    <p>Consulta los requisitos específicos de tu país.</p>
                </div>
            </div>
        </div>

        <!-- Seguridad y Salud -->
        <div class="section">
            <h2>🏥 Salud y Seguridad</h2>
            <div class="highlight highlight-warning">
                <strong>⚠️ Recomendaciones Importantes:</strong>
                <ul>
                    <li>Vacunas recomendadas: Fiebre Amarilla, Hepatitis A, Tétano</li>
                    <li>Lleva protector solar, repelente y pastillas para el agua</li>
                    <li>Bebe agua embotellada o hervida</li>
                    <li>Evita objetos de valor en la calle y mantén tu pasaporte seguro</li>
                    <li>Viaja con amigos y respeta el horario de tours</li>
                    <li>Contrata un seguro de viaje</li>
                </ul>
            </div>
        </div>

        <!-- Tours Principales -->
        <div class="section">
            <h2>✈️ Nuestros Tours Destacados</h2>

            <!-- Tikal -->
            <div class="card" style="margin-bottom: 20px; border-left-color: #8e44ad;">
                <h3>🏛️ Tikal - La Joya Maya (Recomendado)</h3>
                <p>Visita una de las 7 maravillas del mundo y experimenta la grandeza de la civilización Maya en la selva de Petén.</p>
                <ul>
                    <li><strong>Duración:</strong> 2 días / 1 noche</li>
                    <li><strong>Incluye:</strong> Transporte, guía experto certificado, entrada al parque, alojamiento, desayuno</li>
                    <li><strong>Salidas:</strong> Diarias desde nuestra central</li>
                    <li><strong>Lo Especial:</strong> 
                        <ul>
                            <li>🌅 Amanecer con vista a la selva y sonidos de monos aulladores</li>
                            <li>🕰️ Templo IV - La estructura más alta (65 metros)</li>
                            <li>📸 Vistas panorámicas incomparables</li>
                            <li>🧭 Senderismo por senderos arqueológicos</li>
                        </ul>
                    </li>
                </ul>
                <p><span class="price">Desde Q1,250 por persona</span></p>
            </div>

            <!-- Cráter Azul -->
            <div class="card" style="margin-bottom: 20px; border-left-color: #3498db;">
                <h3>💙 Cráter Azul - Maravilla Natural</h3>
                <p>Descubre el agua más cristalina de Guatemala en una maravilla natural rodeada de selva virgen. Perfecta para nadar y bucear.</p>
                <ul>
                    <li><strong>Duración:</strong> Día completo (8:00 AM - 6:00 PM)</li>
                    <li><strong>Incluye:</strong> Transporte, guía profesional, entrada, almuerzo incluido, equipo de snorkel</li>
                    <li><strong>Salidas:</strong> Miércoles, viernes y domingos</li>
                    <li><strong>Lo Especial:</strong>
                        <ul>
                            <li>🌊 Agua cristalina de 30°C todo el año (termal)</li>
                            <li>🏞️ Caminata por la selva con vistas a cascadas</li>
                            <li>🤿 Snorkel en aguas únicas y saludables</li>
                            <li>🍽️ Comida tradicional incluida</li>
                        </ul>
                    </li>
                </ul>
                <p><span class="price">Desde Q850 por persona</span></p>
            </div>

            <!-- Antigua Guatemala -->
            <div class="card" style="margin-bottom: 20px; border-left-color: #e74c3c;">
                <h3>🏰 Antigua Guatemala - Historia Colonial</h3>
                <p>Explora una de las ciudades coloniales mejor preservadas de América Latina, Patrimonio de la Humanidad.</p>
                <ul>
                    <li><strong>Duración:</strong> Día completo (7:00 AM - 5:00 PM)</li>
                    <li><strong>Incluye:</strong> Transporte, guía histórico, entrada a museos, almuerzo</li>
                    <li><strong>Salidas:</strong> Martes, jueves y sábados</li>
                    <li><strong>Lo Especial:</strong>
                        <ul>
                            <li>🏛️ Ruinas de iglesias y conventos coloniales</li>
                            <li>🎨 Calles empedradas y mercados autóctonos</li>
                            <li>🌋 Vistas al Volcán de Agua</li>
                            <li>🛍️ Gastronomía y artesanías auténticas</li>
                        </ul>
                    </li>
                </ul>
                <p><span class="price">Desde Q650 por persona</span></p>
            </div>
        </div>

        <!-- Guías Profesionales -->
        <div class="section">
            <h2>👨‍💼 Nuestros Guías Profesionales</h2>
            <div class="highlight highlight-success">
                <strong>🌟 ¿Por qué elegirnos?</strong>
                <ul>
                    <li>✅ Guías certificados con más de 10 años de experiencia</li>
                    <li>✅ Hablan español, inglés, francés y otras lenguas</li>
                    <li>✅ Conocimiento profundo de historia, cultura, naturaleza y seguridad</li>
                    <li>✅ Equipados con todo lo necesario para tu confort y seguridad</li>
                    <li>✅ Atención personalizada para grupos pequeños y grandes</li>
                    <li>✅ <strong>98% de satisfacción de clientes - Más de 5,000 turistas guiados</strong></li>
                    <li>✅ Tours adaptados a tus intereses y ritmo</li>
                </ul>
            </div>
        </div>

        <!-- Galería de Testimonios -->
        <div class="section">
            <h2>⭐ Lo que dicen nuestros viajeros</h2>
            <div class="grid-2">
                <div class="card">
                    <p><em>"¡Increíble experiencia en Tikal! Los guías fueron muy profesionales y atentos. Guatemala es un destino que todos deben visitar."</em></p>
                    <p><strong>- María, España 🇪🇸</strong></p>
                </div>
                <div class="card">
                    <p><em>"El Cráter Azul fue mágico. El agua limpia, la naturaleza impresionante y el trato excepcional. ¡Volveré!"</em></p>
                    <p><strong>- John, Canadá 🇨🇦</strong></p>
                </div>
            </div>
        </div>

        <!-- Reservas -->
        <div class="section" style="background: linear-gradient(135deg, #e8f5e9, #f0e8fd); text-align: center;">
            <h2>📞 ¡Reserva tu Aventura Hoy Mismo!</h2>
            <p style="font-size: 1.1rem;">No esperes más. <strong>Plazas limitadas</strong> y precios especiales para grupos.</p>
            <div style="margin: 30px 0;">
                <button class="contact-btn" onclick="alert('Contacta a través de WhatsApp')">
                    📱 Contactar por WhatsApp
                </button>
                <a href="https://maps.app.goo.gl/9Vz3eJcdgpZAnLv36" target="_blank" class="secondary-btn" style="display: inline-block; text-decoration: none;">
                    🗺️ Visítanos en Persona
                </a>
            </div>
            <div style="font-size: 1.2rem; margin: 20px 0;">
                <strong>📲 WhatsApp:</strong> <span style="background: #34a853; padding: 5px 15px; border-radius: 5px; font-weight: bold;">+502 1234-5678</span>
            </div>
            <p style="color: #666; margin-top: 20px;">✅ Respuesta rápida | ✅ Asesoramiento gratuito | ✅ Flexibilidad en horarios</p>
        </div>

        <!-- Preguntas Frecuentes -->
        <div class="section">
            <h2>❓ Preguntas Frecuentes</h2>
            <div class="card">
                <h4>¿Se requiere visa para entrar a Guatemala?</h4>
                <p>La mayoría de turistas internacionales NO requieren visa para estancias de hasta 90 días. Consulta con tu embajada según tu nacionalidad.</p>
            </div>
            <div class="card">
                <h4>¿Cuál es la mejor forma de llegar?</h4>
                <p>El Aeropuerto Internacional La Aurora (MGA) en la Ciudad de Guatemala es la entrada principal. Desde aquí, es fácil llegar a nuestros tours.</p>
            </div>
            <div class="card">
                <h4>¿Puedo hacer tours por mi cuenta?</h4>
                <p>¡Por supuesto! Pero recomendamos nuestros guías por su experiencia, seguridad y conocimiento local que enriquecerá tu experiencia.</p>
            </div>
            <div class="card">
                <h4>¿Hay descuentos para grupos?</h4>
                <p>Sí, ofrecemos tarifas especiales para grupos de 8 o más personas. ¡Consulta con nosotros!</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Guía Turística Guatemala. Todos los derechos reservados.</p>
        <p>Viajes seguros, memorables y auténticos garantizados. 🌍</p>
    </footer>
</body>
</html>
