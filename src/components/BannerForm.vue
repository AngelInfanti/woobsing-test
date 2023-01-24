<template>
  <div class="bg-img">
    <form action="#" class="container bg-sky-700">
        <div class="flex justify-center mb-2">
            <h1 class="mr-2 text-white font-bold">Inscribase </h1>
            <h1 class="text-orange-600 font-bold">GRATIS</h1>
        </div>

      <input type="text" placeholder="Nombre" name="name" required />

      <input type="text" placeholder="Numero de Documento" name="doc" required />

      <input type="text" placeholder="Profesion" name="prof" required />

      <input type="text" placeholder="Entidad donde Labora" name="lab" required />

      <input type="number" placeholder="Celular" name="number" required />

      <input type="email" placeholder="Email" name="email" required />

      <button type="submit" class="btn bg-orange-600 text-white">ENVIAR INSCRIPCION</button>
    </form>
  </div>
</template>

<style scoped>
* {
  box-sizing: border-box;
}

.bg-img {
  /* The image used */
  background-image: url("https://www.w3schools.com/howto/img_nature.jpg");

  min-height: 650px;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

/* Add styles to the form container */
.container {
  position: absolute;
  right: 0;
  margin: 20px;
  max-width: 300px;
  padding: 16px;
}

/* Full-width input fields */
input {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  border: none;
  background: #f1f1f1;
}

input[type="text"]:focus,
input[type="password"]:focus {
  background-color: #ddd;
  outline: none;
}

/* Set a style for the submit button */
.btn {
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

.btn:hover {
  opacity: 1;
}
</style>
