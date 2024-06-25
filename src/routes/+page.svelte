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
    <div class=" w-full h-16 bg-slate-900 text-slate-100 flex"> 
        <img src={imagenLogo} alt="icono" class="pl-5">
        <p><a href="contact" class="absolute top-0  right-60 pt-5"> Contacto</a></p>
        <p><a href="aboutUs" class="absolute top-0  right-32 pt-5"> Nosotros</a></p>   
        <p><a href="login" class="absolute top-0  right-10 pt-5"> Log in</a></p>
    </div>
</header>

<main class="h-full min-w-96 bg-white  relative">

    <div class="article">
        <div class="sub-encabezado">
            <div class="w-full h-96 bg-indigo-500 static">
                <h1 class="text-slate-100 text-7xl text-left font-sans pt-16 pl-10 font">Control estratégico, <br>resultados tangibles </h1>
                <h5 class="pl-10 pb-8 pt-5 text-black">Lorem ipsum dolor sit amet consectetures rem aliquid aliquam vel quas explicabo perspiciatis molest <br>iae magnam veniam incidunt velit, nam consectetur iure est voluptas sapiente quisquam.</h5>
                <a href="login" class="absolute top-94 left-10">Ingresar</a>
            </div>
        </div>
        <div class="text-center p-20"> 
            <h1 class="text-5xl font-normal">Bienvenido a TRES60 tu sistema de inventario</h1>
            <h4 class="pt-8">Maneja tu inventario de forma eficiente, sin barreras. TRES60 te agrupa todo tu negocio en un solo lugar</h4>
        </div>
        <div class="contenedores-centro"> 
            <div class="grid gap-6 gap-x-6 gap-y-4 grid-cols-3 max-w-4xl m-auto  ">
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenProducto} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Inventario - Productos / servicios</h2>
                    <h4 class="pl-5 text-indigo-700">Leer más...</h4>
                </div>
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenReportes} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Reportes - estadisticas</h2>
                    <h4 class="pl-5 text-indigo-700">Leer más...</h4>
                </div>
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenProveedores} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Pedidos proveedores</h2>
                    <h4 class="pl-5 text-indigo-700">Leer más...</h4>
                </div>
                <div class=" shadow-lg  bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenClientes} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Consultas clientes</h2>
                    <h4 class="pl-5 text-indigo-700">Leer más...</h4>
                </div>
                <div class="shadow-lg  bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenCaja} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Caja registradora</h2>
                    <h4 class="pl-5 text-indigo-700">Leer más...</h4>
                </div>
                <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                    <img src={imagenFacturas} alt="icono" class="m-auto pt-2">
                    <h2 class="pt-10 p-5">Facturas</h2>
                    <h4 class="pl-5 text-indigo-700">Leer más...</h4>
                </div>
            </div>
        </div>
       <!-- contendio -->

          <div class="pt-32 pb-32 max-w-5xl m-auto text-justify">

            <h1 class="text-4xl text-black font-bold my-4">TRES60 - Aplicación de Inventarios</h1>

            <h2 class="pt-12 pb-5  text-3xl text-black font-bold my-3">Público Objetivo</h2>
            <p>TREES60 está diseñada para pequeñas y medianas empresas que buscan una solución eficiente y efectiva para gestionar sus inventarios. Nuestro público objetivo incluye minoristas, mayoristas, fabricantes, y cualquier negocio que necesite mantener un control detallado de sus productos y suministros.</p>
            <p>Además, TREES60 es ideal para empresas de comercio electrónico que desean integrar la gestión de inventarios con sus plataformas de ventas en línea, permitiendo una actualización en tiempo real de los niveles de stock y evitando rupturas de inventario.</p>
            <p>Las startups y las empresas en crecimiento también encontrarán en TREES60 una herramienta fundamental para escalar sus operaciones, gracias a su capacidad para manejar grandes volúmenes de datos y su flexibilidad para adaptarse a las necesidades cambiantes del negocio.</p>
            <p>Finalmente, las tiendas físicas y los almacenes pueden beneficiarse enormemente del uso de TREES60, ya que les proporciona un control exhaustivo sobre sus existencias, facilita la realización de inventarios físicos y mejora la eficiencia operativa.</p>

            <h2 class=" pt-12 pb-5 text-3xl text-black font-bold my-3">Proyección de la Aplicación</h2>
            <p>TREES60 se proyecta como una herramienta esencial en la transformación digital de la gestión de inventarios. A medida que la tecnología avanza, nuestra aplicación incorporará nuevas funcionalidades basadas en inteligencia artificial y análisis predictivo para ofrecer recomendaciones de reabastecimiento, pronósticos de demanda y optimización de almacenes.</p>
            <p>Nos vemos expandiendo nuestra base de usuarios a nivel global, ofreciendo soporte multilingüe y adaptándonos a las regulaciones de diferentes mercados internacionales. Nuestro objetivo es convertirnos en líderes en soluciones de inventario, reconocidos por nuestra innovación y la satisfacción de nuestros clientes.</p>
            <p>Además, planeamos integrar TREES60 con otras plataformas empresariales, como sistemas de gestión de relaciones con clientes (CRM) y sistemas de planificación de recursos empresariales (ERP), para ofrecer una solución completa y coherente que abarque todas las áreas operativas del negocio.</p>
            <p>Con el tiempo, TREES60 también incluirá funcionalidades avanzadas como la gestión de inventario por lotes y fechas de caducidad, control de calidad automatizado, y un sistema de alertas inteligentes que notificará a los usuarios sobre posibles problemas antes de que ocurran.</p>

            <h2 class=" pt-8  text-3xl text-black font-bold my-3">Apartados de la Aplicación</h2>

            <h3 class=" pt-8 pb-5 text-2xl text-black font-bold my-2">Caja Registradora</h3>
            <p>La sección de Caja Registradora de TREES60 permite a los usuarios procesar ventas rápidamente, generar recibos y mantener un registro detallado de todas las transacciones. Con integración a sistemas de pago, facilita una experiencia de compra rápida y segura para los clientes.</p>
            <p>Además, la Caja Registradora está equipada con funciones avanzadas como la gestión de descuentos, devoluciones y cambios, así como la capacidad de manejar múltiples métodos de pago, incluidas tarjetas de crédito, débito y pagos móviles.</p>
            <p>El sistema también proporciona informes de ventas en tiempo real, lo que permite a los gerentes monitorear el desempeño de ventas, identificar productos más vendidos y ajustar las estrategias de marketing y ventas en consecuencia.</p>

            <h3 class=" pt-12 pb-5 text-2xl text-black font-bold my-2">Clientes</h3>
            <p>En el apartado de Clientes, los usuarios pueden gestionar información detallada sobre sus clientes, incluyendo historial de compras, preferencias y datos de contacto. Esto ayuda a personalizar la experiencia del cliente y mejorar las estrategias de marketing.</p>
            <p>TREES60 permite segmentar la base de clientes en diferentes categorías, como clientes frecuentes, nuevos clientes y clientes inactivos, facilitando la creación de campañas de marketing dirigidas y programas de fidelización.</p>
            <p>Además, la integración con sistemas de correo electrónico y mensajería permite enviar notificaciones y promociones personalizadas, mejorando la comunicación con los clientes y aumentando las tasas de retención.</p>

            <h3 class=" pt-12 pb-5 text-2xl text-black font-bold my-2">Proveedores</h3>
            <p>La sección de Proveedores permite llevar un control exhaustivo de todos los proveedores, incluyendo contratos, historial de pedidos y tiempos de entrega. Facilita la negociación de términos y la gestión de relaciones comerciales clave para el negocio.</p>
            <p>TREES60 también proporciona herramientas para evaluar el desempeño de los proveedores, basándose en criterios como puntualidad en las entregas, calidad de los productos y cumplimiento de los términos acordados.</p>
            <p>Con la capacidad de automatizar pedidos de reabastecimiento y gestionar múltiples proveedores por producto, TREES60 asegura que siempre haya suficiente stock disponible sin necesidad de exceso de inventario.</p>

            <h3 class=" pt-12 pb-5 text-2xl text-black font-bold my-2">Reportes</h3>
            <p>El apartado de Reportes ofrece una amplia variedad de informes personalizables sobre inventarios, ventas, compras y desempeño financiero. Estos reportes ayudan a los gerentes a tomar decisiones informadas basadas en datos precisos y actualizados.</p>
            <p>Los informes de TREES60 incluyen gráficos y visualizaciones interactivas, permitiendo a los usuarios identificar rápidamente tendencias y patrones, así como áreas de oportunidad y posibles problemas.</p>
            <p>La capacidad de programar informes periódicos y recibir alertas automáticas sobre indicadores clave asegura que los gerentes estén siempre informados y puedan actuar rápidamente para optimizar las operaciones.</p>

            <h3 class=" pt-12 pb-5 text-2xl text-black font-bold my-2">Estadísticas</h3>
            <p>En la sección de Estadísticas, TREES60 proporciona análisis detallados y gráficos sobre el comportamiento del inventario, tendencias de ventas y rendimiento de productos. Esta información es crucial para identificar oportunidades de mejora y optimizar las operaciones del negocio.</p>
            <p>Las estadísticas avanzadas de TREES60 incluyen análisis predictivo para anticipar la demanda futura, optimizar el reabastecimiento y evitar problemas de sobrestock o desabastecimiento.</p>
            <p>Además, la integración con herramientas de análisis de terceros permite una mayor profundidad en el análisis de datos y la creación de modelos personalizados para satisfacer las necesidades específicas de cada negocio.</p>

            <h3 class=" pt-12 pb-5 text-2xl text-black font-bold my-2">Todo el Control que Puede Abracar la Aplicación</h3>
            <p>TREES60 abarca un control integral de todas las áreas críticas relacionadas con la gestión de inventarios. Desde el seguimiento de stock en tiempo real hasta la automatización de pedidos y la gestión de devoluciones, nuestra aplicación asegura que los usuarios tengan un control total sobre sus operaciones.</p>
            <p>La interfaz intuitiva y fácil de usar de TREES60 permite a los usuarios configurar alertas de inventario bajo, programar auditorías regulares y acceder a datos históricos para análisis comparativos. Además, con la seguridad robusta y las copias de seguridad automáticas, los datos están siempre protegidos y accesibles.</p>
            <p>Con funcionalidades adicionales como la gestión de múltiples almacenes, la integración con sistemas de transporte y logística, y la capacidad de realizar seguimiento de productos desde la recepción hasta la venta, TREES60 ofrece una solución completa y versátil para cualquier negocio.</p>
            <p>La flexibilidad de TREES60 permite a los usuarios personalizar la aplicación según sus necesidades específicas, ya sea mediante la creación de flujos de trabajo personalizados, la integración con otras herramientas empresariales o la configuración de permisos y roles de usuario detallados.</p>
          </div> 
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

