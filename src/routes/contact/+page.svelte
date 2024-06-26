<script>
     import imagenLogo from '$lib/assets/iconos/TRES60.png'
</script>
<header class="sticky top-0 z-20">
     <div class=" w-full h-16 bg-slate-900 text-slate-100 flex"> 
        <img src={imagenLogo} alt="icono" class="pl-5">
        <p><a href="/" class="absolute top-0 right-96 pt-5"> Inicio</a></p>
        <p><a href="contact" class="absolute top-0  right-60 pt-5"> Contacto</a></p>
        <p><a href="aboutUs" class="absolute top-0  right-32 pt-5"> Nosotros</a></p>   
        <p><a href="login" class="absolute top-0  right-10 t-2 mt-2 p-2 rounded-lg bg-blue-400 "> Log in</a></p>
    </div>
</header>
<body class="bg-white p-10">
    <div class="max-w-4xl mx-auto bg-indigo-500 p-8 shadow-lg rounded-lg">
        <h1 class="text-3xl font-bold mb-6 text-white">Contacto</h1>
        <form>
            <div class="mb-4">
                <label for="name" class="block text-sm font-medium text-gray-700">Nombre</label>
                <input type="text" id="name" name="name" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="John doe">
            </div>
            <div class="mb-4">
                <label for="email" class="block text-sm font-medium text-gray-700">Correo Electrónico</label>
                <input type="email" id="email" name="email" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="ejemplo@gmail.com">
            </div>
            <div class="mb-4">
                <label for="subject" class="block text-sm font-medium text-gray-700">Asunto</label>
                <input type="text" id="subject" name="subject" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Quiero mi plan">
            </div>
            <div class="mb-4">
                <label for="message" class="block text-sm font-medium text-gray-700">Mensaje</label>
                <textarea id="message" name="message" rows="4" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Quiero más información"></textarea>
            </div>
            <div class="flex justify-end">
                <button type="submit" class="bg-indigo-600 text-white px-4 py-2 rounded-md shadow-sm hover:bg-indigo-700">Enviar</button>
            </div>
        </form>
    </div>
</body>

<footer class=" bg-gray-800  py-8 pt-20 mt-24 text-white">
    <div class="container mx-auto px-4 pb-10">
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
