<script>
      import imagenProducto from '$lib/assets/iconos/productos.png'
      import imagenReportes from '$lib/assets/iconos/reportes.png'
      import imagenFacturas from '$lib/assets/iconos/facturas.png'

</script>

<body class="bg-gray-100 text-gray-900 flex flex-col min-h-screen">

    <header class=" bg-zinc-950 text-white p-4">
        <h1 class="text-xl"> Nombre empresa</h1>
    </header>

    <main class="flex-grow container mx-auto p-4 min-h-screen-with-footer">
        <div class="sticky top-0 max-w-7xl h-auto bg-blue-500 mx-auto pt-10  rounded shadow-lg">
            <h1 class="text-3xl font-bold mb-4 pl-5 text-white">Información actual</h1>
            <button class="mb-4 text-right pr-4 pl-4 pb-1 absolute top-20 right-5 bg-stone-950 rounded-xl text-white">Agregar</button>
            <div class="flex items-center justify-center w-full h-96 bg-orange-400 mt-10 rounded">
                
                <div class="grid gap-6 gap-x-6 gap-y-4 grid-cols-3 max-w-4xl m-auto  ">
                    <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-52 rounded-3xl text-left">
                        <h2 class="pt-10 text-center font-semibold">Stock bajo</h2>
                        <h4 class="pl-2">Productos menos vendidos</h4>
                         <img src={imagenProducto} alt="icono" class="m-auto pt-2">
                    </div>
                    <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                        <h2 class="pt-10 text-center font-semibold">Stock alto</h2>
                        <h4 class="pl-2">Productos más vendidos</h4>
                        <img src={imagenReportes} alt="icono" class="m-auto pt-2 ">
                    </div>
                    <div class=" shadow-lg bg-white min-h-60 max-w-xs min-w-42 rounded-3xl text-left">
                        <h2 class="pt-10 text-center font-semibold">Registrar producto</h2>
                        <h4 class="pl-2">Crear producto o servicio</h4>
                        <img src={imagenFacturas} alt="icono" class="m-auto pt-2">
                    </div>
                </div>
            </div>
            
        </div>
    </main>



</body>