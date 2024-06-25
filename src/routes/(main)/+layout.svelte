<script>
  import "../../app.css";

  import imagenLogo from '$lib/assets/iconos/TRES60.png'
</script>

        
<header>
  <div class="sticky top-0 w-full h-12  items-center text-right bg-slate-600 ">
    <nav class="flex  space-x-8 pt-3  text-white">
      <img src={imagenLogo} alt="icono" class="pl-5 ">
      <p><a href="principal" class="pt-5">Home</a></p>
      <p><a href="cashier" class="pt-5">Caja</a></p>
      <p><a href="clients" class="pt-5">Clientes</a></p>   
      <p><a href="products" class="pt-5">Productos</a></p>
      <p><a href="suppliers" class="pt-5">Proveedores</a></p>
      <p><a href="reports" class="pt-5">Reportes</a></p>
      <p><a href="contact" class="pt-5">Ayuda</a></p>
      <p class="pt-1 right-36 absolute">Empleado</p>
      <p><a href="/" class="pt-1 right-5 absolute font-semibold">Cerrar sesión</a></p>
    </nav>
  </div>
</header>


<!-- min-h-dvh es para que el footer quede fijo abajo de la pantalla -->
<main class=" w-dvw min-h-dvh bg-white "><slot />
 
</main>

<!-- footer siempre -->
<footer class="static bg-gray-800 text-white p-4 w-full  bottom-0">
  <div class="container mx-auto text-center">
    <p>&copy; 2024 TRES60. Todos los derechos reservados.</p>
  </div>
</footer>

