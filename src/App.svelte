<script>
	import { Router } from "svelte-routing";
	import Header from "./Header.svelte";
	import Main from "./Main.svelte";

	import { setContext } from "svelte";

	const URL = {
    armas: "https://apuntapistola.herokuapp.com/api/armas/",
    tiradores: "https://apuntapistola.herokuapp.com/api/tiradores/",
  };

  setContext("URL", URL);
</script>

<Router>
	<Header />
	<Main />
</Router>

<style>
	.backc-nav {
		background-color: #7a8765;
	}
</style>
