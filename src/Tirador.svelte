<script>
    export let tirador = {};
  </script>
  
  <style>
    /* Aquí el código CSS */
    /* Consultar el código fuente */
  </style>
  
  <div class="card">
    <input bind:value={tirador.nombre} class="title" />
    <input bind:value={tirador.apellidos} class="title" />
    <slot />
  </div>