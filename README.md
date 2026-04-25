# Dolcevita
Dulce Vita - El arte de los postres premium. Ofrecemos postres artesanales hechos con ingredientes frescos y de la mejor calidad. Nuestro compromiso es brindarte una experiencia única con cada bocado, entregados directamente a tu casa. Descubre nuestros sabores exclusivos: Pie de Manzana, Pie de Limón, y Tartaleta de Fresa
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dulce Vita - Postres Premium</title>

    <!-- AOS Animation Library -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" />
    <!-- Custom CSS -->
    <link rel="stylesheet" href="style.css" />
</head>
<body>

    <!-- Hero Section -->
    <header class="hero-section" data-aos="fade-up">
        <img src="LOGO_ETIQUETAS.png" alt="Dulce Vita Logo" class="logo" />
        <h1>Dulce Vita - Postres Premium</h1>
        <p>Hechos con amor y calidad, para endulzar tus momentos especiales.</p>
        <button class="cta-button" data-aos="zoom-in" data-aos-delay="500">¡Descubre nuestros sabores!</button>
    </header>

    <!-- Sección "Sobre Nosotros" -->
    <section class="about" data-aos="fade-up">
        <h2>La Historia Detrás de Dolce Vita</h2>
        <p>En **Dulce Vita**, cada postre es preparado con dedicación y pasión, utilizando los mejores ingredientes naturales. Nos especializamos en postres artesanales que no solo son deliciosos, sino también una experiencia para tus sentidos.</p>
        <p>Descubre el sabor exclusivo de nuestros productos: Pie de Manzana, Pie de Limón, y Tartaleta de Fresa. ¡Hechos con amor y listos para ti!</p>
    </section>

    <!-- Sección de Productos -->
    <section class="products-gallery" data-aos="fade-up">
        <h2>Nuestros Postres Premium</h2>
        <div class="product" data-aos="zoom-in" data-aos-delay="300">
            <img src="pie-de-manzana.jpg" alt="Pie de Manzana">
            <p><strong>Pie de Manzana</strong></p>
        </div>
        <div class="product" data-aos="zoom-in" data-aos-delay="400">
            <img src="pie-de-limon.jpg" alt="Pie de Limón">
            <p><strong>Pie de Limón</strong></p>
        </div>
        <div class="product" data-aos="zoom-in" data-aos-delay="500">
            <img src="tartaleta-fresa.jpg" alt="Tartaleta de Fresa">
            <p><strong>Tartaleta de Fresa</strong></p>
        </div>
        <button class="cta-button" data-aos="fade-up" data-aos-delay="600">¡Pide el tuyo ahora!</button>
    </section>

    <!-- Testimonios de Clientes -->
    <section class="testimonials" data-aos="fade-up">
        <h2>Lo que Dicen Nuestros Clientes</h2>
        <div class="testimonial" data-aos="fade-right">
            <p>"¡Los mejores postres que he probado! Sin duda, una experiencia deliciosa." – María R.</p>
        </div>
        <div class="testimonial" data-aos="fade-left">
            <p>"Recomiendo el pie de manzana, ¡es simplemente irresistible!" – Juan C.</p>
        </div>
    </section>

    <!-- Formulario de Contacto -->
    <section class="contact" data-aos="fade-up">
        <h2>Contáctanos</h2>
        <form action="#">
            <input type="text" name="name" placeholder="Tu Nombre" required><br/>
            <input type="email" name="email" placeholder="Tu Correo" required><br/>
            <textarea name="message" placeholder="Tu mensaje..." required></textarea><br/>
            <button type="submit" class="cta-button">Enviar mensaje</button>
        </form>
    </section>

    <!-- Llamado a la Acción Final -->
    <section class="final-cta" data-aos="fade-up">
        <h2>¡Haz tu pedido hoy!</h2>
        <p>No esperes más, ¡endulza tu día con Dolce Vita!</p>
        <button class="cta-button">Pide Ahora</button>
    </section>

    <!-- AOS Script -->
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,  // Tiempo de animación
            once: true,      // Animaciones solo se activan una vez
        });
    </script>
</body>
</html>
