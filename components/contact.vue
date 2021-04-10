<template>
  <div class="container">
    <h1 class="title">¡QUEREMOS SABER DE TI!</h1>
    <div class="content">
      <form
        name="contact"
        action=""
        netlify-honeypot="bot-field"
        method="post"
        netlify
        data-netlify="true"
      >
        <div>
          <input type="hidden" name="form-name" value="contact" />
          <p class="hidden">
            <label>Don’t fill this out: <input name="bot-field" /></label>
          </p>

          <input id="name" class="form-field" name="name" type="text" /><br />
          <label class="form-label" for="name"> NOMBRE Y APELLIDOS </label>

          <input id="phone" class="form-field" name="phone" type="tel" /><br />
          <label class="form-label" for="phone"> TELÉFONO </label>

          <input id="mail" class="form-field" name="mail" type="email" /><br />
          <label class="form-label" for="mail"> CORREO ELECTRÓNICO </label>

          <input
            id="company"
            class="form-field"
            name="company"
            type="text"
          /><br />
          <label class="form-label" for="company">
            NOMBRE DE TU EMPRESA O NEGOCIO
          </label>

          <select id="size" name="size" class="form-field">
            <option value="1 - 10 EMPLEADOS">1 - 10 EMPLEADOS</option>
            <option value="10 - 30 EMPLEADOS">10 - 30 EMPLEADOS</option>
            <option value="30 - 60 EMPLEADOS">30 - 60 EMPLEADOS</option>
            <option value="60+ EMPLEADOS">60+ EMPLEADOS</option>
          </select>
          <br />
          <label class="form-label" for="size">Tamaño de empresa</label>
        </div>
        <div>
          <input
            id="activity"
            class="form-field"
            name="activity"
            type="text"
          /><br />
          <label class="form-label" for="activity">
            ACTIVIDAD DE TU EMPRESA O NEGOCIO
          </label>

          <input
            id="date"
            class="form-field"
            type="date"
            name="date"
            value="aaaa-mm-dd"
            min="2018-01-01"
            max="2030-12-31"
          /><br />
          <label class="form-label" for="date"
            >¿CUÁNDO PODEMOS HABLAR CONTIGO?</label
          ><br />

          <input class="form-button" type="submit" value="ENVIAR" />
        </div>
      </form>
    </div>
  </div>
</template>

<style scoped>
.hidden {
  display: none;
}
.title {
  font-family: sifonn;
  font-size: 3.6rem;
  text-align: center;
  color: var(--yellow);
  margin: 6rem 0 5rem 0;
}
form {
  display: flex;
  justify-content: space-around;
}
form div {
  margin: 1rem 8rem;
  padding: 0 4rem;
}
.form-label {
  color: #ec008c;
  font-family: c-gothic;
  font-size: 2.8rem;
}
.form-field {
  border: 1px solid #ec008c;
  border-radius: 20px;
  width: 60rem;
  height: 4rem;
  color: #ec008c;
  margin-top: 3.5rem;
  margin-bottom: 1rem;
  padding: 1rem 2rem;
  font-size: 1.9rem;
  outline-color: #ec008c;
}
select {
  /* reset */
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-appearance: none;
  -moz-appearance: none;
}
select.form-field {
  background-image: linear-gradient(45deg, transparent 50%, #ec008c 50%),
    linear-gradient(135deg, #ec008c 50%, transparent 50%),
    linear-gradient(to right, #ec008c, #ec008c);
  background-position: calc(100% - 25px) calc(0.8em + 2px),
    calc(100% - 15px) calc(0.8em + 2px), calc(100% - 2.5em) 0.5em;
  background-size: 10px 10px, 10px 10px, 1px 1em;
  background-repeat: no-repeat;
}
select.form-field:focus {
  background-image: linear-gradient(45deg, #ec008c 50%, transparent 50%),
    linear-gradient(135deg, transparent 50%, #ec008c 50%),
    linear-gradient(to right, #ec008c, #ec008c);
  background-position: calc(100% - 15px) 0.8em, calc(100% - 25px) 0.8em,
    calc(100% - 2.5em) 0.5em;
  background-size: 10px 10px, 10px 10px, 1px 1em;
  background-repeat: no-repeat;
  outline: 0;
}
select:-moz-focusring {
  color: transparent;
  text-shadow: 0 0 0 #ec008c;
}
.form-button {
  font-family: b-gothic;
  font-size: 4.5rem;
  color: #fff;
  background-color: var(--yellow);
  padding: 1rem 7rem;
  border: none;
  border-radius: 5rem;
  margin-top: 25rem;
  outline-color: #ec008c;
  transition: 300ms;
  cursor: pointer;
}
.form-button:hover {
  background-color: #ec008c;
  color: var(--yellow);
}
option {
  background-color: #ec008c;
  color: #fff;
  width: 20rem;
  padding: 1rem;
  -webkit-box-shadow: inset 0px 10px 30px -10px rgb(0 0 0 / 75%);
  -moz-box-shadow: inset 0px 10px 30px -10px rgb(0 0 0 / 75%);
  box-shadow: inset 0px 10px 30px -10px rgb(0 0 0 / 75%);
}
</style>
