# SERIMEX
web de publicidad
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Serimex - Soluciones Publicitarias en Guadalajara</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Tailwind gray-50 */
            color: #334155; /* Tailwind slate-700 */
        }
        .hero-section {
            background: linear-gradient(to right, rgba(29, 78, 216, 0.8), rgba(126, 34, 206, 0.8)), url('https://placehold.co/1920x600/1d4ed8/ffffff?text=Fondo+de+Serimex'); /* Tailwind blue-700 and purple-700 */
            background-size: cover;
            background-position: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        .section-heading {
            color: #1e3a8a; /* Tailwind blue-800 */
        }
        .card {
            background-color: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 0.5rem;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .btn-primary {
            background-color: #1d4ed8; /* Tailwind blue-700 */
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            transition: background-color 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #1e40af; /* Tailwind blue-800 */
        }
        .footer-bg {
            background-color: #1e293b; /* Tailwind slate-900 */
            color: #e2e8f0; /* Tailwind slate-200 */
        }
        /* Custom scroll-to-top button */
        #scrollToTopBtn {
            display: none; /* Hidden by default */
            position: fixed; /* Fixed position */
            bottom: 20px; /* Place at the bottom */
            right: 20px; /* Place at the right */
            z-index: 99; /* Make sure it's above other elements */
            border: none; /* Remove borders */
            outline: none; /* Remove outline */
            background-color: #1d4ed8; /* Blue background */
            color: white; /* White text */
            cursor: pointer; /* Add a mouse pointer on hover */
            padding: 15px; /* Some padding */
            border-radius: 50%; /* Rounded corners */
            font-size: 18px; /* Increase font size */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: background-color 0.3s ease;
        }
        #scrollToTopBtn:hover {
            background-color: #1e40af; /* Darker blue on hover */
        }
    </style>
</head>
<body class="antialiased">

    <!-- Scroll to Top Button -->
    <button id="scrollToTopBtn" title="Ir arriba">↑</button>

    <!-- Header Section -->
    <header class="bg-white shadow-md p-4 sticky top-0 z-50">
        <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
            <div class="text-3xl font-bold text-gray-800 mb-2 md:mb-0">
                Serimex
            </div>
            <nav class="space-x-4">
                <a href="#inicio" class="text-gray-600 hover:text-blue-700 font-medium">Inicio</a>
                <a href="#nosotros" class="text-gray-600 hover:text-blue-700 font-medium">Nosotros</a>
                <a href="#servicios" class="text-gray-600 hover:text-blue-700 font-medium">Servicios</a>
                <a href="#productos" class="text-gray-600 hover:text-blue-700 font-medium">Productos</a>
                <a href="#contacto" class="text-gray-600 hover:text-blue-700 font-medium">Contacto</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="inicio" class="hero-section py-20 md:py-32 text-center">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-4 animate-fade-in-up">
                Serimex: Tu Socio en Publicidad Impresa
            </h1>
            <p class="text-lg md:text-xl mb-8 animate-fade-in-up delay-200">
                Impresión DTF, Bordado, Serigrafía y Productos Promocionales de Calidad en Guadalajara.
            </p>
            <a href="#contacto" class="btn-primary inline-block animate-fade-in-up delay-400">
                ¡Contáctanos Hoy!
            </a>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="nosotros" class="py-16 md:py-24 bg-gray-50">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold section-heading mb-8">Sobre Nosotros</h2>
            <p class="text-lg leading-relaxed max-w-3xl mx-auto text-gray-700">
                En Serimex, somos una empresa líder en Guadalajara, Jalisco, Centro, especializada en soluciones de impresión y personalización para negocios y particulares. Con años de experiencia, nos dedicamos a ofrecer productos promocionales de la más alta calidad, utilizando tecnología de punta y un equipo de expertos para garantizar resultados excepcionales en cada proyecto.
            </p>
            <p class="text-lg leading-relaxed max-w-3xl mx-auto mt-4 text-gray-700">
                Nuestra misión es ayudarte a destacar con productos que reflejen la identidad de tu marca, desde la impresión DTF hasta bordados y serigrafía en una amplia gama de artículos.
            </p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="servicios" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold section-heading mb-12">Nuestros Servicios Principales</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- DTF Printing Card -->
                <div class="card p-6 flex flex-col items-center">
                    <img src="https://placehold.co/100x100/1d4ed8/ffffff?text=DTF" alt="Impresión DTF" class="w-24 h-24 mb-4 rounded-full bg-blue-100 p-2">
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Impresión DTF</h3>
                    <p class="text-gray-600 text-center">
                        Impresión Directa a Película (DTF) en metro de 58 cm de ancho. Ideal para diseños vibrantes y duraderos en cualquier tipo de tela. Ofrecemos servicio de maquila y personalizado.
                    </p>
                </div>
                <!-- Embroidery Card -->
                <div class="card p-6 flex flex-col items-center">
                    <img src="https://placehold.co/100x100/8b5cf6/ffffff?text=Bordado" alt="Bordados" class="w-24 h-24 mb-4 rounded-full bg-purple-100 p-2">
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Bordados</h3>
                    <p class="text-gray-600 text-center">
                        Bordados de alta calidad para dar un toque de elegancia y profesionalismo a tus prendas. Perfecto para logotipos y diseños detallados.
                    </p>
                </div>
                <!-- Screen Printing Card -->
                <div class="card p-6 flex flex-col items-center">
                    <img src="https://placehold.co/100x100/059669/ffffff?text=Serigrafia" alt="Serigrafía" class="w-24 h-24 mb-4 rounded-full bg-green-100 p-2">
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Serigrafía</h3>
                    <p class="text-gray-600 text-center">
                        Técnica clásica y versátil para grandes volúmenes y diseños con colores planos. Ofrecemos serigrafía en maquila y para proyectos personalizados.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="productos" class="py-16 md:py-24 bg-gray-50">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold section-heading mb-12">Nuestros Productos Personalizables y Promocionales</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Product Card 1 -->
                <div class="card p-4 flex flex-col items-center">
                    <img src="https://placehold.co/300x200/cbd5e1/334155?text=Playeras+Personalizadas" alt="Playeras Personalizadas" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Playeras, Camisas y Chalecos</h3>
                    <p class="text-gray-600 text-center text-sm">
                        Personalizamos todo tipo de prendas con tu diseño, logo o mensaje. Ideal para uniformes, eventos o promociones.
                    </p>
                </div>
                <!-- Product Card 2 -->
                <div class="card p-4 flex flex-col items-center">
                    <img src="https://placehold.co/300x200/cbd5e1/334155?text=Gorras+Personalizadas" alt="Gorras Personalizadas" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Gorras Personalizadas</h3>
                    <p class="text-gray-600 text-center text-sm">
                        Diseña tus gorras con bordado o serigrafía para un toque distintivo.
                    </p>
                </div>
                <!-- Product Card 3 -->
                <div class="card p-4 flex flex-col items-center">
                    <img src="https://placehold.co/300x200/cbd5e1/334155?text=Lonas+Publicitarias" alt="Lonas Publicitarias" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Lonas Publicitarias</h3>
                    <p class="text-gray-600 text-center text-sm">
                        Impresión de lonas de gran formato para publicidad exterior e interior.
                    </p>
                </div>
                <!-- Product Card 4 -->
                <div class="card p-4 flex flex-col items-center">
                    <img src="https://placehold.co/300x200/cbd5e1/334155?text=Banderas+Promocionales" alt="Banderas Promocionales" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Banderas Publicitarias</h3>
                    <p class="text-gray-600 text-center text-sm">
                        Banderas personalizadas para eventos, negocios o promociones.
                    </p>
                </div>
                <!-- Add more product cards as needed -->
                <div class="card p-4 flex flex-col items-center">
                    <img src="https://placehold.co/300x200/cbd5e1/334155?text=Articulos+Promocionales" alt="Otros Productos Promocionales" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold text-gray-800 mb-2">Otros Artículos Promocionales</h3>
                    <p class="text-gray-600 text-center text-sm">
                        Amplia variedad de productos para promocionar tu marca: tazas, plumas, termos, etc.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold section-heading mb-12">Contáctanos</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-start">
                <!-- Contact Info -->
                <div class="text-left bg-gray-50 p-6 rounded-lg shadow-sm">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-4">Información de Contacto</h3>
                    <p class="text-lg text-gray-700 mb-2">
                        <span class="font-semibold">Teléfono / WhatsApp:</span> <a href="https://wa.me/5213336537612" target="_blank" class="text-blue-700 hover:underline">3336537612</a>
                    </p>
                    <p class="text-lg text-gray-700 mb-2">
                        <span class="font-semibold">Email:</span> <a href="mailto:serimexgdl@gmail.com" class="text-blue-700 hover:underline">serimexgdl@gmail.com</a>
                    </p>
                    <p class="text-lg text-gray-700 mb-2">
                        <span class="font-semibold">Dirección:</span> Guadalajara, Jalisco, Centro
                    </p>
                    <p class="text-lg text-gray-700 mb-4">
                        <span class="font-semibold">Horario:</span>
                        <br>Lunes a Viernes: 9:00 a 19:00
                        <br>Sábados: 10:00 a 15:00
                    </p>
                    <a href="https://maps.app.goo.gl/52nDNNjAAPm9yer2A?g_st=ic" target="_blank" class="btn-primary inline-block mt-4">
                        Ver en Google Maps
                    </a>
                </div>

                <!-- Google Map Embed -->
                <div class="w-full h-80 md:h-full rounded-lg overflow-hidden shadow-md">
                    <iframe
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3732.969850125749!2d-103.3485012846939!3d20.67104990520675!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8428b1f5e2b0a0f1%3A0x4d0c9f1a0e1c2b5!2sGuadalajara%2C%20Jal.%2C%20M%C3%A9xico!5e0!3m2!1ses-419!2smx!4v1678912345678!5m2!1ses-419!2smx"
                        width="100%"
                        height="100%"
                        style="border:0;"
                        allowfullscreen=""
                        loading="lazy"
                        referrerpolicy="no-referrer-when-downgrade">
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer-bg py-8">
        <div class="container mx-auto px-4 text-center text-sm">
            <p>&copy; 2025 Serimex. Todos los derechos reservados.</p>
            <p class="mt-2">Diseñado con pasión en Guadalajara, Jalisco.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Show/hide scroll to top button
        const scrollToTopBtn = document.getElementById("scrollToTopBtn");

        window.onscroll = function() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                scrollToTopBtn.style.display = "block";
            } else {
                scrollToTopBtn.style.display = "none";
            }
        };

        // When the user clicks on the button, scroll to the top of the document
        scrollToTopBtn.addEventListener("click", function() {
            document.body.scrollTop = 0; // For Safari
            document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
        });
    </script>
</body>
</html>
