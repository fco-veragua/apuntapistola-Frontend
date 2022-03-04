<script>
    import { Route, Link } from "svelte-routing";
    import Inicio from "./Inicio.svelte";
    import Armas from "./Armas.svelte";
    import Tiradores from "./Tiradores.svelte";
</script>

<style>
</style>

<main>
    <div class="container color-container">
        <Route path="/" component={Inicio} />
        <Route path="/armas" component={Armas} />
        <Route path="/tiradores" component={Tiradores} />
    </div>
</main>

