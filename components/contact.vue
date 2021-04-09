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
        <label class="form-label" for="size">Tamaño de empresa</label>
        <select id="size" name="size" class="form-field">
          <option value="1 - 10 EMPLEADOS">1 - 10 EMPLEADOS</option>
          <option value="10 - 30 EMPLEADOS">10 - 30 EMPLEADOS</option>
          <option value="30 - 60 EMPLEADOS">30 - 60 EMPLEADOS</option>
          <option value="60+ EMPLEADOS">60+ EMPLEADOS</option>
        </select>
        <label class="form-label" for="activity">
          ACTIVIDAD DE TU EMPRESA O NEGOCIO
        </label>
        <input id="activity" class="form-field" name="activity" />
        <label class="form-label" for="date"
          >¿CUÁNDO PODEMOS HABLAR CONTIGO?</label
        >
        <input
          id="date"
          type="date"
          name="date"
          value="2018-07-22"
          min="2018-01-01"
          max="2030-12-31"
        />

        <input class="form-button" type="submit" value="ENVIAR" />
      </form>
    </div>
  </div>
</template>
