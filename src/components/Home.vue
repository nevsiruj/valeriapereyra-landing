<template>
  <header class="bg-gradient-to-r from-red-500 to-black py-4">
    <div class="container mx-auto flex justify-between items-center">
      <a href="#" class="text-white font-bold text-xl ml-2">Valeria Pereyra</a>
      <nav>
        <a href="#" class="text-white hover:underline mx-4">Inicio</a>
        <a href="#" class="text-white hover:underline mx-4">Servicios</a>
        <a href="#" class="text-white hover:underline mx-4">Contacto</a>
      </nav>
    </div>
  </header>
  <section class="bg-gray-100 py-12">
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap -mx-4">
        <div
          class="
            card
            bg-gradient-to-br
            from-red-900
            to-red-500
            rounded-lg
            overflow-hidden
            shadow-lg
            mb-8
            m-2
          "
        >
          <div class="p-4">
            <h2 class="text-3xl font-bold text-white mb-4">
              <i class="fas fa-chart-line"></i> Mejora la presencia de tu marca
              en las redes sociales
            </h2>
            <h3 class="text-xl font-bold text-white mb-4">
              <i class="fas fa-paint-brush"></i> Diseño gráfico y gestión de
              redes sociales
            </h3>
            <p class="text-lg text-white mb-4">
              ¿Quieres que tu marca tenga una presencia profesional y atractiva
              en las redes sociales? Soy Valeria Pereyra, community manager y
              diseñadora gráfica, y estoy aquí para ayudarte a alcanzar tus
              objetivos en las redes sociales. <i class="fas fa-check"></i>
            </p>
            <p class="text-lg text-white mb-4">
              En mi servicio de diseño gráfico y gestión de redes sociales, te
              brindaré estrategias personalizadas para aumentar tu visibilidad
              en las redes y mejorar la interacción con tus seguidores.
              Trabajaremos juntos para crear una imagen de marca cohesiva y
              atractiva que se destaque en la multitud en las redes sociales.
              <i class="fas fa-user-friends"></i>
            </p>
            <a
              href="#"
              class="bg-white hover:bg-gray-200 text-red-500 py-2 px-4 rounded"
              ><i class="fas fa-arrow-circle-right"></i> ¡Contrata mis servicios
              ahora!</a
            >
          </div>
        </div>

        <div class="w-full md:w-1/2 px-4 mb-8">
          <h2 class="text-3xl font-bold text-gray-800 mb-4">
            Sobre mis servicios
          </h2>
          <p class="text-lg mb-4">
            Ofrezco un servicio completo de gestión de redes sociales que
            incluye diseño gráfico, programación de publicaciones, creación de
            contenido y estrategias personalizadas para tu marca.
          </p>
          <p class="text-lg mb-4">
            Me aseguraré de que tu marca tenga una presencia sólida y atractiva
            en las redes sociales y que alcance a tu audiencia objetivo. Con mi
            servicio, podrás centrarte en tu negocio mientras yo me encargo de
            la gestión de tus redes sociales.
          </p>
          <p class="text-lg mb-4">
            También ofrezco servicios de diseño gráfico personalizado, como
            diseño de logotipos, diseño de banners y diseño de publicaciones
            para redes sociales. Trabajaré contigo para asegurarme de que el
            diseño gráfico de tu marca sea cohesivo y atractivo.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section class="bg-black text-red-500 py-16">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-8">Servicios</h2>
      <div class="flex flex-wrap -mx-4">
        <div class="w-full md:w-1/3 px-4 mb-8">
          <div class="bg-white rounded-lg shadow-lg p-8">
            <h3 class="font-bold text-xl mb-4">Diseño gráfico</h3>
            <p class="text-gray-700 mb-4">
              Creamos diseños gráficos únicos y personalizados para tu negocio o
              marca, adaptados a tus necesidades y objetivos.
            </p>
            <a href="#" class="text-red-500 font-bold hover:text-red-600"
              >Ver más</a
            >
          </div>
        </div>
        <div class="w-full md:w-1/3 px-4 mb-8">
          <div class="bg-white rounded-lg shadow-lg p-8">
            <h3 class="font-bold text-xl mb-4">Gestión de redes sociales</h3>
            <p class="text-gray-700 mb-4">
              Te ayudamos a manejar y mejorar la presencia de tu marca en las
              redes sociales, aumentando el engagement y llegando a más
              personas.
            </p>
            <a href="#" class="text-red-500 font-bold hover:text-red-600"
              >Ver más</a
            >
          </div>
        </div>
        <div class="w-full md:w-1/3 px-4 mb-8">
          <div class="bg-white rounded-lg shadow-lg p-8">
            <h3 class="font-bold text-xl mb-4">Producción audiovisual</h3>
            <p class="text-gray-700 mb-4">
              Realizamos videos promocionales, publicitarios y corporativos para
              tu marca o negocio, desde la idea hasta la postproducción.
            </p>
            <a href="#" class="text-red-500 font-bold hover:text-red-600"
              >Ver más</a
            >
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="bg-gradient-to-r from-red-500 to-red-900 text-white py-6">
    <div class="container mx-auto px-4">
      <p class="text-center">Valera Pereyra &copy; 2023.</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Home',
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
  border-radius: 5px; /* ajusta este valor para modificar la curvatura de las esquinas de la tarjeta */
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}
</style>
