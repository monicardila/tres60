<header class="sticky top-0 z-20">
    <div class=" w-full h-16 bg-slate-900 text-slate-100 flex"> 
        <p>TRES60 logo</p>
        <p><a href="/" class="absolute top-0 right-96 pt-5"> Inicio</a></p>
        <p><a href="contact" class="absolute top-0  right-60 pt-5"> Contacto</a></p>
        <p><a href="aboutUs" class="absolute top-0  right-32 pt-5"> Nosotros</a></p>   
        <p><a href="login" class="absolute top-0  right-10 pt-5"> Log in</a></p>
    </div>
</header>
<body class="bg-gray-100 p-10">
    <div class="max-w-4xl mx-auto bg-white p-8 shadow-lg rounded-lg">
        <h1 class="text-3xl font-bold mb-6">Contacto</h1>
        <form>
            <div class="mb-4">
                <label for="name" class="block text-sm font-medium text-gray-700">Nombre</label>
                <input type="text" id="name" name="name" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Tu nombre">
            </div>
            <div class="mb-4">
                <label for="email" class="block text-sm font-medium text-gray-700">Correo Electrónico</label>
                <input type="email" id="email" name="email" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Tu correo electrónico">
            </div>
            <div class="mb-4">
                <label for="subject" class="block text-sm font-medium text-gray-700">Asunto</label>
                <input type="text" id="subject" name="subject" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Asunto de tu mensaje">
            </div>
            <div class="mb-4">
                <label for="message" class="block text-sm font-medium text-gray-700">Mensaje</label>
                <textarea id="message" name="message" rows="4" class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Tu mensaje"></textarea>
            </div>
            <div class="flex justify-end">
                <button type="submit" class="bg-indigo-600 text-white px-4 py-2 rounded-md shadow-sm hover:bg-indigo-700">Enviar</button>
            </div>
        </form>
    </div>
</body>