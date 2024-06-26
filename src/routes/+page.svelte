<script>
  import "../app.css";

  // Buscar aliases sveltekit
  import imagenLogo from '$lib/assets/iconos/TRES60.png'
  import imagenProducto from '$lib/assets/iconos/productos.png'
  import imagenReportes from '$lib/assets/iconos/reportes.png'
  import imagenProveedores from '$lib/assets/iconos/proveedores.png'
  import imagenClientes from '$lib/assets/iconos/clientes.png'
  import imagenCaja from '$lib/assets/iconos/caja.png'
  import imagenFacturas from '$lib/assets/iconos/facturas.png'


</script>
<header class="sticky top-0 z-20">
    <div class=" w-full h-14 bg-slate-900 text-slate-100 flex"> 
        <img src={imagenLogo} alt="icono" class="pl-5">
        <p><a href="contact" class="absolute top-0  right-60 pt-5"> Contacto</a></p>
        <p><a href="aboutUs" class="absolute top-0  right-32 pt-5"> Nosotros</a></p>   
        <p><a href="login" class="absolute top-0  right-10 t-2 mt-2 p-2 rounded-lg bg-blue-400 "> Log in</a></p>
    </div>
</header>

<main class="h-full min-w-96 bg-white  relative">

    <div class="article">
        <div class="sub-encabezado">
            <div class="w-full h-96  static bg-gradient-to-r from-cyan-500 to-blue-500 ">
                <h1 class="text-slate-100 text-7xl text-left font-sans pt-16 pl-24 font-medium">Control estratégico, <br>resultados tangibles </h1>
                <h5 class="pl-24 pb-8 pt-5 text-black">Lorem ipsum dolor sit amet consectetures rem aliquid aliquam vel quas explicabo perspiciatis molest <br>iae magnam veniam incidunt velit, nam consectetur iure est voluptas sapiente quisquam.</h5>
                <a href="login" class="absolute top-94 left-10 ml-16 p-3 bg-slate-50 font-bold rounded-lg">INGRESAR</a>
            </div>
        </div>
        <div class="text-center p-20"> 
            <h1 class="text-5xl font-bold">Bienvenido a TRES60 tu sistema de inventario</h1>
            <h4 class="pt-8">Maneja tu inventario de forma eficiente, sin barreras. TRES60 te agrupa todo tu negocio en un solo lugar</h4>
        </div>
        <div class="contenedores-centro"> 
            <div class="grid gap-6 gap-x-6 gap-y-4 grid-cols-3 max-w-4xl m-auto  ">
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenProducto} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Inventario - Productos / servicios</h2>
                    <a href="#producto" class="pl-5 text-indigo-700 font-medium">Leer más</a>
                    
                </div>
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenReportes} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Reportes - estadisticas</h2>
                    <a href="#reporte" class="pl-5 text-indigo-700 font-medium">Leer más</a>
                </div>
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenProveedores} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Pedidos proveedores</h2>
                    <a href="#proveedor" class="pl-5 text-indigo-700 font-medium">Leer más</a>
                </div>
                <div class=" shadow-lg  bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenClientes} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Consultas clientes</h2>
                    <a href="#cliente" class="pl-5 text-indigo-700 font-medium">Leer más</a>
                </div>
                <div class="shadow-lg  bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenCaja} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Caja registradora</h2>
                    <a href="#caja" class="pl-5 text-indigo-700 font-medium">Leer más</a>
                </div>
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenFacturas} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Facturas</h2>
                    <a href="#factura" class="pl-5 text-indigo-700 font-medium">Leer más</a>
                </div>
            </div>
        </div>
       <!-- contendio -->

          <div class="pt-32 pb-32 max-w-5xl m-auto text-justify">
    <h1 class="text-4xl text-black font-bold my-4">TRES60 - Aplicación de Inventarios</h1>

    <h2 class="pt-12 pb-5 text-3xl text-black font-bold my-3">Público Objetivo</h2>
    <p>TREES60 está diseñada para pequeñas y medianas empresas que buscan una solución eficiente y efectiva para gestionar sus inventarios. Nuestro público objetivo incluye minoristas, mayoristas, fabricantes, y cualquier negocio que necesite mantener un control detallado de sus productos y suministros.</p>
    <p>Además, TREES60 es ideal para empresas de comercio electrónico que desean integrar la gestión de inventarios con sus plataformas de ventas en línea, permitiendo una actualización en tiempo real de los niveles de stock y evitando rupturas de inventario.</p>
    <p>Las startups y las empresas en crecimiento también encontrarán en TREES60 una herramienta fundamental para escalar sus operaciones, gracias a su capacidad para manejar grandes volúmenes de datos y su flexibilidad para adaptarse a las necesidades cambiantes del negocio.</p>
    <p>Finalmente, las tiendas físicas y los almacenes pueden beneficiarse enormemente del uso de TREES60, ya que les proporciona un control exhaustivo sobre sus existencias, facilita la realización de inventarios físicos y mejora la eficiencia operativa.</p>

    <h2 class="pt-12 pb-5 text-3xl text-black font-bold my-3">Proyección de la Aplicación</h2>
    <p>TREES60 se proyecta como una herramienta esencial en la transformación digital de la gestión de inventarios. A medida que la tecnología avanza, nuestra aplicación incorporará nuevas funcionalidades basadas en inteligencia artificial y análisis predictivo para ofrecer recomendaciones de reabastecimiento, pronósticos de demanda y optimización de almacenes.</p>
    <p>Nos vemos expandiendo nuestra base de usuarios a nivel global, ofreciendo soporte multilingüe y adaptándonos a las regulaciones de diferentes mercados internacionales. Nuestro objetivo es convertirnos en líderes en soluciones de inventario, reconocidos por nuestra innovación y la satisfacción de nuestros clientes.</p>
    <p>Además, planeamos integrar TREES60 con otras plataformas empresariales, como sistemas de gestión de relaciones con clientes (CRM) y sistemas de planificación de recursos empresariales (ERP), para ofrecer una solución completa y coherente que abarque todas las áreas operativas del negocio.</p>
    <p>Con el tiempo, TREES60 también incluirá funcionalidades avanzadas como la gestión de inventario por lotes y fechas de caducidad, control de calidad automatizado, y un sistema de alertas inteligentes que notificará a los usuarios sobre posibles problemas antes de que ocurran.</p>

    <h2 class="pt-8 text-3xl text-black font-bold my-3">Apartados de la Aplicación</h2>

    <h3 id="caja" class="pt-8 pb-5 text-2xl text-black font-bold my-2">Caja Registradora</h3>
    <p>La sección de Caja Registradora de TREES60 permite a los usuarios procesar ventas rápidamente, generar recibos y mantener un registro detallado de todas las transacciones. Con integración a sistemas de pago, facilita una experiencia de compra rápida y segura para los clientes.</p>
    <p>Además, la Caja Registradora está equipada con funciones avanzadas como la gestión de descuentos, devoluciones y cambios, así como la capacidad de manejar múltiples métodos de pago, incluidas tarjetas de crédito, débito y pagos móviles. Los usuarios pueden también personalizar los recibos con el logo y la información de su negocio, proporcionando una experiencia de compra profesional y coherente.</p>
    <p>El sistema también proporciona informes de ventas en tiempo real, lo que permite a los gerentes monitorear el desempeño de ventas, identificar productos más vendidos y ajustar las estrategias de marketing y ventas en consecuencia. Además, la integración con herramientas de análisis de datos permite realizar un seguimiento detallado de las tendencias de ventas, ayudando a los negocios a prever la demanda y a planificar el inventario de manera más efectiva.</p>

    <h3 id="cliente" class="pt-12 pb-5 text-2xl text-black font-bold my-2">Clientes</h3>
    <p>En el apartado de Clientes, los usuarios pueden gestionar información detallada sobre sus clientes, incluyendo historial de compras, preferencias y datos de contacto. Esto ayuda a personalizar la experiencia del cliente y mejorar las estrategias de marketing.</p>
    <p>TREES60 permite segmentar la base de clientes en diferentes categorías, como clientes frecuentes, nuevos clientes y clientes inactivos, facilitando la creación de campañas de marketing dirigidas y programas de fidelización. Los negocios pueden enviar ofertas especiales, cupones y promociones exclusivas a segmentos específicos de su base de clientes, aumentando la lealtad y la repetición de compras.</p>
    <p>Además, la integración con sistemas de correo electrónico y mensajería permite enviar notificaciones y promociones personalizadas, mejorando la comunicación con los clientes y aumentando las tasas de retención. Los usuarios pueden también utilizar los datos de los clientes para realizar encuestas y obtener retroalimentación, ayudando a mejorar los productos y servicios ofrecidos.</p>

    <h3 id="proveedor" class="pt-12 pb-5 text-2xl text-black font-bold my-2">Proveedores</h3>
    <p>La sección de Proveedores permite llevar un control exhaustivo de todos los proveedores, incluyendo contratos, historial de pedidos y tiempos de entrega. Facilita la negociación de términos y la gestión de relaciones comerciales clave para el negocio.</p>
    <p>TREES60 también proporciona herramientas para evaluar el desempeño de los proveedores, basándose en criterios como puntualidad en las entregas, calidad de los productos y cumplimiento de los términos acordados. Esto permite a los usuarios tomar decisiones informadas sobre con quién hacer negocios, optimizando la cadena de suministro y reduciendo costos.</p>
    <p>Con la capacidad de automatizar pedidos de reabastecimiento y gestionar múltiples proveedores por producto, TREES60 asegura que siempre haya suficiente stock disponible sin necesidad de exceso de inventario. Los usuarios pueden establecer niveles mínimos y máximos de stock para cada producto, recibiendo alertas automáticas cuando es necesario realizar un pedido. Además, la integración con sistemas de logística y transporte permite realizar un seguimiento en tiempo real de los envíos, asegurando entregas puntuales y eficientes.</p>

    <h3 id="reporte" class="pt-12 pb-5 text-2xl text-black font-bold my-2">Reportes</h3>
    <p>El apartado de Reportes ofrece una amplia variedad de informes personalizables sobre inventarios, ventas, compras y desempeño financiero. Estos reportes ayudan a los gerentes a tomar decisiones informadas basadas en datos precisos y actualizados.</p>
    <p>Los informes de TREES60 incluyen gráficos y visualizaciones interactivas, permitiendo a los usuarios identificar rápidamente tendencias y patrones, así como áreas de oportunidad y posibles problemas. Los usuarios pueden también exportar los informes a diferentes formatos, como PDF y Excel, para su análisis y presentación.</p>
    <p>La capacidad de programar informes periódicos y recibir alertas automáticas sobre indicadores clave asegura que los gerentes estén siempre informados y puedan actuar rápidamente para optimizar las operaciones. Además, TREES60 permite a los usuarios crear dashboards personalizados con los indicadores más relevantes para su negocio, proporcionando una visión clara y concisa del desempeño general.</p>
    <p>Los reportes avanzados incluyen análisis de rentabilidad por producto, rendimiento de proveedores, y métricas de satisfacción del cliente, proporcionando una visión integral de todas las áreas del negocio. Los usuarios pueden también realizar comparaciones entre diferentes periodos, identificar temporadas de alta demanda, y planificar campañas de marketing y promociones basadas en datos históricos.</p>

    <h3 id="producto" class="pt-12 pb-5 text-2xl text-black font-bold my-2">Productos</h3>
    <p>En el apartado de Productos, TREES60 permite gestionar todos los detalles relacionados con los productos del inventario, incluyendo descripciones, categorías, precios, y niveles de stock. Los usuarios pueden añadir y editar productos de manera sencilla, manteniendo siempre la información actualizada.</p>
    <p>La aplicación también facilita la clasificación de los productos en diferentes categorías y subcategorías, mejorando la organización del inventario y permitiendo una búsqueda rápida y eficiente. Los usuarios pueden asignar etiquetas y palabras clave a los productos, facilitando la identificación y el seguimiento.</p>
    <p>Además, TREES60 proporciona herramientas para la gestión de variantes de productos, como diferentes tamaños, colores o modelos, asegurando que cada variante sea rastreada individualmente. Los usuarios pueden también gestionar precios especiales y descuentos para productos específicos, facilitando la implementación de promociones y ofertas.</p>
    <p>Con la capacidad de realizar un seguimiento detallado del ciclo de vida de cada producto, desde la adquisición hasta la venta, TREES60 asegura un control total sobre el inventario. Los usuarios pueden establecer fechas de caducidad y realizar un seguimiento de productos perecederos, evitando pérdidas y garantizando la frescura de los productos.</p>
    <p>La integración con herramientas de análisis y reportes permite a los usuarios identificar productos de alta y baja rotación, optimizando las estrategias de compra y marketing. Además, la capacidad de gestionar inventarios en múltiples ubicaciones y almacenes proporciona una visión global del stock disponible en todo momento.</p>

    <h3 id="factura" class="pt-12 pb-5 text-2xl text-black font-bold my-2">Facturas</h3>
    <p>El apartado de Facturas de TREES60 permite a los usuarios generar y gestionar facturas de manera eficiente, asegurando un registro detallado de todas las transacciones comerciales. Los usuarios pueden crear facturas personalizadas con el logo y la información de su negocio, proporcionando una imagen profesional a sus clientes.</p>
    <p>La aplicación permite automatizar el proceso de facturación, generando facturas automáticamente a partir de los pedidos realizados y enviándolas por correo electrónico a los clientes. Los usuarios pueden también realizar un seguimiento del estado de las facturas, desde la emisión hasta el pago, asegurando una gestión efectiva de las cuentas por cobrar.</p>
    <p>Además, TREES60 ofrece herramientas para la gestión de facturas recurrentes, facilitando la facturación de servicios y productos que se venden de manera periódica. Los usuarios pueden establecer recordatorios y alertas para los pagos pendientes, mejorando la eficiencia en la gestión de cobros.</p>
    <p>La integración con sistemas de contabilidad permite un flujo de información continuo, asegurando que todas las transacciones sean registradas correctamente y reduciendo la carga administrativa. Los usuarios pueden también generar reportes de facturación detallados, proporcionando una visión clara de los ingresos y las cuentas por cobrar.</p>
    <p>Con la capacidad de gestionar diferentes tipos de impuestos y realizar cálculos automáticos, TREES60 asegura el cumplimiento de las normativas fiscales y facilita la preparación de declaraciones de impuestos. La aplicación también permite realizar un seguimiento de los pagos parciales y gestionar notas de crédito y devoluciones, proporcionando una solución completa para la gestión de facturas.</p>
</div>

<slot />
</main>
<!-- footer siempre -->

<footer class=" bg-gray-800 text-white py-8">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Información General -->
        <div>
          <h2 class="text-lg font-semibold mb-4">Sobre Nosotros</h2>
          <p class="text-sm">Somos una empresa dedicada a la gestión de inventarios, ofreciendo soluciones innovadoras para el manejo de productos, clientes, proveedores y más.</p>
        </div>
        <!-- Enlaces Rápidos -->
        <div>
          <h2 class="text-lg font-semibold mb-4">Enlaces Rápidos</h2>
          <ul class="text-sm">
            <li><a href="aboutUs" class="hover:underline">Sobre Nosotros</a></li>
            <li><a href="contact" class="hover:underline">Contacto</a></li>
            <li><a href="login" class="hover:underline">Iniciar Sesión</a></li>
            <li><a href="register" class="hover:underline">Registrarse</a></li>
          </ul>
        </div>
        <!-- Contacto -->
        <div>
          <h2 class="text-lg font-semibold mb-4">Contacto</h2>
          <p class="text-sm">Email: contacto@tres60.com</p>
          <p class="text-sm">Teléfono: +34 123 456 789</p>
          <p class="text-sm">Dirección: Calle Falsa 123, Ciudad, País</p>
        </div>
      </div>
      <div class="text-center mt-8">
        <p class="text-sm">&copy; 2024 TRES60. Todos los derechos reservados.</p>
      </div>
    </div>
</footer>

