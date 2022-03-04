<script>
    export let arma = {};
  </script>
  
  <style>
     /* Aquí el código CSS */
    /* Consultar el código fuente */
  </style>
  
  <div class="card">
    <input bind:value={arma.nombre} class="title" />
    <input
      type="number"
      min="0"
      max="9999.99"
      step=".01"
      bind:value={arma.precio} />  €
    <slot />
  </div>