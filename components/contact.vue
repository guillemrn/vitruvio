<template>
  <div class="container">
    <h1>¡QUEREMOS SABER DE TI!</h1>
    <div class="content">
      <form name="contact" action="" method="post" netlify>
        <input type="hidden" name="form-name" value="contact" />
        <label class="form-label" for="name"> NOMBRE Y APELLIDOS </label>
        <input id="name" class="form-field" name="name" />
        <label class="form-label" for="phone"> TELÉFONO </label>
        <input id="phone" class="form-field" name="phone" />
        <label class="form-label" for="mail"> CORREO ELECTRÓNICO </label>
        <input id="mail" class="form-field" name="mail" />
        <label class="form-label" for="company">
          NOMBRE DE TU EMPRESA O NEGOCIO
        </label>
        <input id="company" class="form-field" name="company" />
        <label class="form-label" for="activity">
          ACTIVIDAD DE TU EMPRESA O NEGOCIO
        </label>
        <input id="activity" class="form-field" name="activity" />

        <input class="form-button" type="submit" value="ENVIAR" />
      </form>
    </div>
  </div>
</template>
