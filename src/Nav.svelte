<script>
    import { Link } from "svelte-routing";
</script>

<nav class="navbar navbar-expand-lg navbar-dark backc-nav">
    <div class="container">
        <img src="img/revolver.png" width="100px" alt="" class="ms-4" />
        <a class="navbar-brand" href="index.html"
            ><strong>APUNTAPISTOLA</strong> API-REST</a
        >

        <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNavDarkDropdown"
            aria-controls="navbarNavDarkDropdown"
            aria-expanded="false"
            aria-label="Toggle navigation"
        >
            <span class="navbar-toggler-icon" />
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDarkDropdown">
            <ul class="navbar-nav">
                <!-- Home está activo -->
                <li>
                    <a
                        class="nav-link active"
                        href="index.html"
                        id="navbarDarkDropdownMenuLink"
                        role="button"
                        aria-expanded="false"
                    >
                        Home
                    </a>
                </li>
                <li class="nav-item dropdown">
                    <a
                        class="nav-link dropdown-toggle"
                        href="index.html"
                        id="navbarDarkDropdownMenuLink"
                        role="button"
                        data-bs-toggle="dropdown"
                        aria-expanded="false"
                    >
                        Others
                    </a>
                    <ul
                        class="dropdown-menu dropdown-menu-light"
                        aria-labelledby="navbarDarkDropdownMenuLink"
                    >
                        <li>
                            <a class="dropdown-item" href="index.html"
                                >Frontend</a
                            >
                        </li>
                        <li>
                            <a
                                class="dropdown-item"
                                target="_blank"
                                href="https://github.com/fco-veragua/apuntapistola-API-REST.git"
                                >Código Fuente</a
                            >
                        </li>
                    </ul>
                </li>
                <li
                    class="nav-link"
                    id="navbarDarkDropdownMenuLink"
                    role="button"
                    aria-expanded="false"
                >
                    <Link to="/">Inicio</Link>
                </li>
                <li
                    class="nav-link"
                    id="navbarDarkDropdownMenuLink"
                    role="button"
                    aria-expanded="false"
                >
                    <Link to="/armas">Armas</Link>
                </li>
                <li
                    class="nav-link"
                    id="navbarDarkDropdownMenuLink"
                    role="button"
                    aria-expanded="false"
                >
                    <Link to="/tiradores">Tiradores</Link>
                </li>
            </ul>
        </div>
    </div>
</nav>

<style>
</style>
