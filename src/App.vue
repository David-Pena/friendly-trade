<template>
  <div class="container">
    <div class="columns is-multiline">
      <div class="column has-text-centered">
        <img src="./assets/logo.png" width="200" height="200" />
      </div>
      <div class="column">
        <h1 class="title is-size-5">Iniciar Sesión</h1>
      </div>
      <div class="column">
        <div class="field">
          <p class="control">
            <input class="input" type="email" placeholder="Email" />
          </p>
        </div>
      </div>
      <div class="column">
        <div class="field">
          <p class="control">
            <input class="input" type="password" placeholder="Contraseña" />
          </p>
        </div>
      </div>
      <div class="column has-text-centered">
        <button class="button is-dark">Iniciar Sesión</button>
        <p class="muted mt-3">Registrarse</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style>
.container {
  padding: 50px;
}

.muted {
  color: rgb(182, 181, 181);
  font-weight: 400;
  font-size: 0.9em;
}
</style>
