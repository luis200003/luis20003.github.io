<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Café Aromas - Cafetería de Especialidad</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header con menú de navegación -->
    <header>
        <div class="container">
            <div class="logo-container">
                <div class="logo">
                    <div class="logo-img">
                        <i class="fas fa-coffee"></i>
                    </div>
                    <div class="logo-text">
                        CAFÉ AROMAS
                        <span>CAFETERÍA DE ESPECIALIDAD</span>
                    </div>
                </div>
            </div>
            <nav>
                <ul>
                    <li><a href="#inicio">PÁGINA PRINCIPAL</a></li>
                    <li><a href="#quienes-somos">¿QUIÉNES SOMOS?</a></li>
                    <li><a href="#mision">MISIÓN</a></li>
                    <li><a href="#servicios">SERVICIOS</a></li>
                    <li><a href="#sucursales">SUCURSALES</a></li>
                    <li><a href="#tienda">TIENDA EN LÍNEA</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Sección Hero -->
    <section class="hero" id="inicio">
        <div class="hero-content">
            <h1>EL ARTE DEL CAFÉ</h1>
            <p>Descubre el placer de un café de especialidad cuidadosamente seleccionado y preparado por nuestros maestros baristas.</p>
            <a href="#tienda" class="btn">Comprar ahora</a>
        </div>
    </section>

    <!-- Sección Quiénes Somos -->
    <section id="quienes-somos">
        <div class="container">
            <h2>¿QUIÉNES SOMOS?</h2>
            <div class="about-container">
                <div class="about-text">
                    <p>En Café Aromas, somos apasionados por el café de calidad. Desde nuestra fundación en 2010, nos hemos dedicado a ofrecer experiencias cafeteras únicas que van más allá de una simple taza de café.</p>
                    <p>Nuestro equipo está formado por baristas certificados, tostadores expertos y amantes del café que trabajan juntos para crear momentos especiales para nuestros clientes.</p>
                    <p>Cada grano que servimos es cuidadosamente seleccionado de fincas sostenibles, tostado artesanalmente en nuestras instalaciones y preparado con precisión para resaltar sus mejores características.</p>
                </div>
                <div class="about-image"></div>
            </div>
        </div>
    </section>

    <!-- Sección Misión -->
    <section id="mision" class="mission">
        <div class="container">
            <h2>NUESTRA MISIÓN</h2>
            <div class="mission-content">
                <div class="mission-statement">
                    Transformar la experiencia del café a través de la excelencia en cada etapa del proceso, desde el cultivo hasta la taza, creando conexiones significativas con nuestros clientes y comunidades.
                </div>
                
                <div class="values-grid">
                    <div class="value-card">
                        <i class="fas fa-star"></i>
                        <h3>Calidad</h3>
                        <p>Buscamos la excelencia en cada detalle, desde la selección de granos hasta la preparación final.</p>
                    </div>
                    <div class="value-card">
                        <i class="fas fa-leaf"></i>
                        <h3>Sostenibilidad</h3>
                        <p>Trabajamos con productores que implementan prácticas agrícolas responsables.</p>
                    </div>
                    <div class="value-card">
                        <i class="fas fa-users"></i>
                        <h3>Comunidad</h3>
                        <p>Creemos en el poder del café para unir personas y construir comunidades.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Servicios -->
    <section id="servicios" class="services">
        <div class="container">
            <h2>NUESTROS SERVICIOS</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-img" style="background-image: url('https://images.unsplash.com/photo-1497515114629-f71d768fd07c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1784&q=80');"></div>
                    <div class="service-content">
                        <h3>Café de Especialidad</h3>
                        <p>Disfruta de nuestras selecciones de granos únicos, preparados con métodos artesanales como pour over, aeropress y siphon.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-img" style="background-image: url('https://images.unsplash.com/photo-1551024506-0bccd828d307?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1664&q=80');"></div>
                    <div class="service-content">
                        <h3>Repostería Artesanal</h3>
                        <p>Nuestros pasteles, galletas y postres son elaborados diariamente con ingredientes frescos y de la más alta calidad.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-img" style="background-image: url('https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=774&q=80');"></div>
                    <div class="service-content">
                        <h3>Talleres de Café</h3>
                        <p>Aprende sobre el mundo del café en nuestros talleres para aficionados y profesionales.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-img" style="background-image: url('https://images.unsplash.com/photo-1527525443983-6e60c75fff46?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1790&q=80');"></div>
                    <div class="service-content">
                        <h3>Eventos Especiales</h3>
                        <p>Celebra tus eventos corporativos o personales en nuestros espacios especialmente diseñados.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Sucursales -->
    <section id="sucursales" class="branches">
        <div class="container">
            <h2>NUESTRAS SUCURSALES</h2>
            <div class="branches-grid">
                <div class="branch-card">
                    <div class="branch-img" style="background-image: url('https://images.unsplash.com/photo-1514933651103-005eec06c04b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1674&q=80');"></div>
                    <div class="branch-info">
                        <h3>Sucursal Centro</h3>
                        <p><i class="fas fa-map-marker-alt"></i> Av. Principal #123, Centro Histórico</p>
                        <p><i class="fas fa-clock"></i> Lunes a Viernes: 7:00 am - 10:00 pm</p>
                        <p><i class="fas fa-clock"></i> Sábados y Domingos: 8:00 am - 11:00 pm</p>
                        <p><i class="fas fa-phone"></i> (55) 1234-5678</p>
                    </div>
                </div>
                <div class="branch-card">
                    <div class="branch-img" style="background-image: url('https://images.unsplash.com/photo-1509042239860-f550ce710b93?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=774&q=80');"></div>
                    <div class="branch-info">
                        <h3>Sucursal Norte</h3>
                        <p><i class="fas fa-map-marker-alt"></i> Plaza Comercial Norte, Local #45</p>
                        <p><i class="fas fa-clock"></i> Lunes a Domingo: 8:00 am - 10:00 pm</p>
                        <p><i class="fas fa-phone"></i> (55) 2345-6789</p>
                    </div>
                </div>
                <div class="branch-card">
                    <div class="branch-img" style="background-image: url('https://images.unsplash.com/photo-1463797221720-6b07e6426c24?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1742&q=80');"></div>
                    <div class="branch-info">
                        <h3>Sucursal Jardines</h3>
                        <p><i class="fas fa-map-marker-alt"></i> Calle Flores #789, Col. Jardines</p>
                        <p><i class="fas fa-clock"></i> Lunes a Sábado: 7:30 am - 9:30 pm</p>
                        <p><i class="fas fa-clock"></i> Domingo: 9:00 am - 8:00 pm</p>
                        <p><i class="fas fa-phone"></i> (55) 3456-7890</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Tienda -->
    <section id="tienda" class="store">
        <div class="container">
            <h2>TIENDA EN LÍNEA</h2>
            
            <div class="store-header">
                <div class="store-filters">
                    <button class="filter-btn active" data-filter="all">Todos</button>
                    <button class="filter-btn" data-filter="cafe">Cafés</button>
                    <button class="filter-btn" data-filter="panaderia">Panadería</button>
                </div>
                <button class="cart-btn">
                    <i class="fas fa-shopping-cart"></i> Carrito
                    <span class="cart-count">0</span>
                </button>
            </div>
            
            <div class="products-grid">
                <!-- Cafés -->
                <div class="product-card" data-category="cafe">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1515442261605-65987783cb6a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80');"></div>
                    <div class="product-badge">Nuevo</div>
                    <div class="product-content">
                        <h3>Café Etiopía</h3>
                        <p>Notas florales con toques de frutos rojos</p>
                        <div class="price">$320 MXN / 500g</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="cafe">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1536257104079-aa99c6460a5a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80');"></div>
                    <div class="product-content">
                        <h3>Café Colombia</h3>
                        <p>Balance perfecto con notas de chocolate</p>
                        <div class="price">$290 MXN / 500g</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="cafe">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1522992319-0365e5f11656?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80');"></div>
                    <div class="product-badge">Popular</div>
                    <div class="product-content">
                        <h3>Café Brasil</h3>
                        <p>Cuerpo completo con notas de nuez</p>
                        <div class="price">$270 MXN / 500g</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="cafe">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1507133750040-4a8f57021571?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80');"></div>
                    <div class="product-content">
                        <h3>Café Guatemala</h3>
                        <p>Sabores cítricos con toques de caramelo</p>
                        <div class="price">$350 MXN / 500g</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="cafe">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1580915411954-282cb1b0d780?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80');"></div>
                    <div class="product-content">
                        <h3>Café Kenia</h3>
                        <p>Intenso con notas de grosella negra</p>
                        <div class="price">$380 MXN / 500g</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="cafe">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1778&q=80');"></div>
                    <div class="product-content">
                        <h3>Kit Iniciación</h3>
                        <p>Todo lo necesario para preparar café en casa</p>
                        <div class="price">$890 MXN</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <!-- Panadería -->
                <div class="product-card" data-category="panaderia">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1608190003443-86b2636f1f02?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80');"></div>
                    <div class="product-badge">Nuevo</div>
                    <div class="product-content">
                        <h3>Croissants</h3>
                        <p>Hechos con mantequilla francesa</p>
                        <div class="price">$35 MXN c/u</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="panaderia">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1550617931-e17a7b70dce2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80');"></div>
                    <div class="product-content">
                        <h3>Pan de Chocolate</h3>
                        <p>Con chispas de chocolate belga</p>
                        <div class="price">$45 MXN</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="panaderia">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1509440159596-0249088772ff?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1772&q=80');"></div>
                    <div class="product-badge">Popular</div>
                    <div class="product-content">
                        <h3>Pastel de Zanahoria</h3>
                        <p>Con nueces y frosting de queso crema</p>
                        <div class="price">$280 MXN</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="panaderia">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1587241321921-91a834d6d191?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80');"></div>
                    <div class="product-content">
                        <h3>Galletas de Avena</h3>
                        <p>Con pasas y nueces, horneadas al momento</p>
                        <div class="price">$25 MXN c/u</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="panaderia">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1608190003443-86b2636f1f02?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80');"></div>
                    <div class="product-content">
                        <h3>Pan de Centeno</h3>
                        <p>Hecho con masa madre natural</p>
                        <div class="price">$85 MXN</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
                
                <div class="product-card" data-category="panaderia">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1563729784474-d77dbb933a9e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80');"></div>
                    <div class="product-badge">Especial</div>
                    <div class="product-content">
                        <h3>Muffins de Arándanos</h3>
                        <p>Con arándanos frescos y crujiente de azúcar</p>
                        <div class="price">$35 MXN c/u</div>
                        <button class="add-to-cart"><i class="fas fa-shopping-cart"></i> Añadir al carrito</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Carrito de compras -->
    <div class="cart-overlay">
        <div class="cart">
            <div class="cart-header">
                <h3>Tu Carrito</h3>
                <button class="close-cart"><i class="fas fa-times"></i></button>
            </div>
            <div class="cart-items">
                <!-- Los elementos del carrito se agregarán aquí dinámicamente -->
            </div>
            <div class="cart-total">
                <span>Total:</span>
                <span class="total-price">$0 MXN</span>
            </div>
            <button class="checkout-btn">Proceder al Pago</button>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>Café Aromas</h3>
                    <p>Tu cafetería de especialidad donde cada taza cuenta una historia.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                <div class="footer-col">
                    <h3>Enlaces Rápidos</h3>
                    <ul>
                        <li><i class="fas fa-chevron-right"></i><a href="#inicio">Inicio</a></li>
                        <li><i class="fas fa-chevron-right"></i><a href="#quienes-somos">Quiénes Somos</a></li>
                        <li><i class="fas fa-chevron-right"></i><a href="#servicios">Servicios</a></li>
                        <li><i class="fas fa-chevron-right"></i><a href="#sucursales">Sucursales</a></li>
                        <li><i class="fas fa-chevron-right"></i><a href="#tienda">Tienda</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Contáctanos</h3>
                    <ul>
                        <li><i class="fas fa-phone"></i> (55) 1234-5678</li>
                        <li><i class="fas fa-envelope"></i> info@cafearomas.com</li>
                        <li><i class="fas fa-map-marker-alt"></i> Av. Principal #123, CDMX</li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Boletín</h3>
                    <p>Suscríbete para recibir promociones y novedades.</p>
                    <form class="newsletter-form">
                        <input type="email" placeholder="Tu correo electrónico">
                        <button type="submit"><i class="fas fa-paper-plane"></i></button>
                    </form>
                </div>
            </div>
            <div class="copyright">
                &copy; 2023 Café Aromas. Todos los derechos reservados.
            </div>
        </div>
    </footer>

    <script>
        // Datos de productos
        const products = [
            {
                id: 1,
                name: "Café Etiopía",
                description: "Notas florales con toques de frutos rojos",
                price: 320,
                category: "cafe",
                image: "https://images.unsplash.com/photo-1515442261605-65987783cb6a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80"
            },
            {
                id: 2,
                name: "Café Colombia",
                description: "Balance perfecto con notas de chocolate",
                price: 290,
                category: "cafe",
                image: "https://images.unsplash.com/photo-1536257104079-aa99c6460a5a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80"
            },
            {
                id: 3,
                name: "Café Brasil",
                description: "Cuerpo completo con notas de nuez",
                price: 270,
                category: "cafe",
                image: "https://images.unsplash.com/photo-1522992319-0365e5f11656?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80"
            },
            {
                id: 4,
                name: "Café Guatemala",
                description: "Sabores cítricos con toques de caramelo",
                price: 350,
                category: "cafe",
                image: "https://images.unsplash.com/photo-1507133750040-4a8f57021571?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80"
            },
            {
                id: 5,
                name: "Café Kenia",
                description: "Intenso con notas de grosella negra",
                price: 380,
                category: "cafe",
                image: "https://images.unsplash.com/photo-1580915411954-282cb1b0d780?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80"
            },
            {
                id: 6,
                name: "Kit Iniciación",
                description: "Todo lo necesario para preparar café en casa",
                price: 890,
                category: "cafe",
                image: "https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1778&q=80"
            },
            {
                id: 7,
                name: "Croissants",
                description: "Hechos con mantequilla francesa",
                price: 35,
                category: "panaderia",
                image: "https://images.unsplash.com/photo-1608190003443-86b2636f1f02?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80"
            },
            {
                id: 8,
                name: "Pan de Chocolate",
                description: "Con chispas de chocolate belga",
                price: 45,
                category: "panaderia",
                image: "https://images.unsplash.com/photo-1550617931-e17a7b70dce2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80"
            },
            {
                id: 9,
                name: "Pastel de Zanahoria",
                description: "Con nueces y frosting de queso crema",
                price: 280,
                category: "panaderia",
                image: "https://images.unsplash.com/photo-1509440159596-0249088772ff?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1772&q=80"
            },
            {
                id: 10,
                name: "Galletas de Avena",
                description: "Con pasas y nueces, horneadas al momento",
                price: 25,
                category: "panaderia",
                image: "https://images.unsplash.com/photo-1587241321921-91a834d6d191?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80"
            },
            {
                id: 11,
                name: "Pan de Centeno",
                description: "Hecho con masa madre natural",
                price: 85,
                category: "panaderia",
                image: "https://images.unsplash.com/photo-1608190003443-86b2636f1f02?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80"
            },
            {
                id: 12,
                name: "Muffins de Arándanos",
                description: "Con arándanos frescos y crujiente de azúcar",
                price: 35,
                category: "panaderia",
                image: "https://images.unsplash.com/photo-1563729784474-d77dbb933a9e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1887&q=80"
            }
        ];

        // Variables globales
        let cart = [];
        let total = 0;

        // Efecto suave al hacer clic en enlaces del menú
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Filtros de productos
        document.querySelectorAll('.filter-btn').forEach(button => {
            button.addEventListener('click', function() {
                // Quitar clase activa de todos los botones
                document.querySelectorAll('.filter-btn').forEach(btn => {
                    btn.classList.remove('active');
                });
                
                // Añadir clase activa al botón clickeado
                this.classList.add('active');
                
                const filter = this.getAttribute('data-filter');
                const productCards = document.querySelectorAll('.product-card');
                
                productCards.forEach(card => {
                    if (filter === 'all' || card.getAttribute('data-category') === filter) {
                        card.style.display = 'block';
                    } else {
                        card.style.display = 'none';
                    }
                });
            });
        });
        
        // Abrir y cerrar carrito
        document.querySelector('.cart-btn').addEventListener('click', function() {
            document.querySelector('.cart-overlay').classList.add('active');
        });
        
        document.querySelector('.close-cart').addEventListener('click', function() {
            document.querySelector('.cart-overlay').classList.remove('active');
        });
        
        // Añadir productos al carrito
        document.querySelectorAll('.add-to-cart').forEach((button, index) => {
            button.addEventListener('click', function() {
                const product = products[index];
                
                // Verificar si el producto ya está en el carrito
                const existingItem = cart.find(item => item.id === product.id);
                
                if (existingItem) {
                    existingItem.quantity += 1;
                } else {
                    cart.push({...product, quantity: 1});
                }
                
                // Actualizar carrito
                updateCart();
                
                // Feedback visual
                const originalText = this.innerHTML;
                this.innerHTML = '<i class="fas fa-check"></i> Añadido';
                this.style.backgroundColor = '#4CAF50';
                
                setTimeout(() => {
                    this.innerHTML = originalText;
                    this.style.backgroundColor = '';
                }, 2000);
            });
        });
        
        // Actualizar carrito
        function updateCart() {
            const cartItems = document.querySelector('.cart-items');
            const cartCount = document.querySelector('.cart-count');
            const totalPrice = document.querySelector('.total-price');
            
            // Vaciar carrito
            cartItems.innerHTML = '';
            total = 0;
            
            // Añadir productos al carrito
            cart.forEach(item => {
                total += item.price * item.quantity;
                
                const cartItem = document.createElement('div');
                cartItem.classList.add('cart-item');
                cartItem.innerHTML = `
                    <div class="cart-item-img" style="background-image: url('${item.image}')"></div>
                    <div class="cart-item-details">
                        <div class="cart-item-title">${item.name}</div>
                        <div class="cart-item-price">$${item.price} MXN</div>
                        <div class="cart-item-quantity">
                            <button class="quantity-btn minus" data-id="${item.id}">-</button>
                            <span>${item.quantity}</span>
                            <button class="quantity-btn plus" data-id="${item.id}">+</button>
                        </div>
                    </div>
                `;
                
                cartItems.appendChild(cartItem);
            });
            
            // Actualizar contador y total
            cartCount.textContent = cart.reduce((sum, item) => sum + item.quantity, 0);
            totalPrice.textContent = `$${total} MXN`;
            
            // Añadir eventos a los botones de cantidad
            document.querySelectorAll('.quantity-btn.minus').forEach(button => {
                button.addEventListener('click', function() {
                    const id = parseInt(this.getAttribute('data-id'));
                    const item = cart.find(item => item.id === id);
                    
                    if (item.quantity > 1) {
                        item.quantity -= 1;
                    } else {
                        cart = cart.filter(item => item.id !== id);
                    }
                    
                    updateCart();
                });
            });
            
            document.querySelectorAll('.quantity-btn.plus').forEach(button => {
                button.addEventListener('click', function() {
                    const id = parseInt(this.getAttribute('data-id'));
                    const item = cart.find(item => item.id === id);
                    item.quantity += 1;
                    updateCart();
                });
            });
        }
        
        // Botón de pago
        document.querySelector('.checkout-btn').addEventListener('click', function() {
            if (cart.length === 0) {
                alert('Tu carrito está vacío');
                return;
            }
            
            alert(`¡Gracias por tu compra! Total: $${total} MXN`);
            cart = [];
            updateCart();
            document.querySelector('.cart-overlay').classList.remove('active');
        });
        
        // Animación para las tarjetas al aparecer
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.animation = 'fadeInUp 1s forwards';
                }
            });
        }, { threshold: 0.1 });
        
        document.querySelectorAll('.service-card, .value-card, .branch-card, .product-card').forEach(card => {
            card.style.opacity = '0';
            card.style.transform = 'translateY(20px)';
            card.style.animation = 'none';
            observer.observe(card);
        });
    </script>
</body>
</html>





