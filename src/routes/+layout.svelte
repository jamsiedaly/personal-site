<script>
    import "../app.css";
</script>

<div class="navbar bg-base-100">
    <div class="navbar-start">
        <div class="dropdown">
            <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
            </div>
            <ul class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52">
                <li><a href="https://github.com/jamsiedaly" target="_blank">My Github</a></li>
                <li><a href="https://twitter.com/jamsiedaly1" target="_blank">My Twitter</a></li>
                <li><a href="https://www.linkedin.com/in/james-daly-ab1754118/" target="_blank">My LinkedIn</a></li>
                <li><a href="https://rust.amsterdam/" target="_blank">Rust Amsterdam</a></li>
            </ul>
        </div>
        <a class="btn btn-ghost text-xl" href="/">James Daly</a>
    </div>
    <div class="navbar-center hidden lg:flex">
        <ul class="menu menu-horizontal px-1">
            <li><a href="https://github.com/jamsiedaly" target="_blank">My Github</a></li>
            <li><a href="https://twitter.com/jamsiedaly1" target="_blank">My Twitter</a></li>
            <li><a href="https://www.linkedin.com/in/james-daly-ab1754118/" target="_blank">My LinkedIn</a></li>
            <li><a href="https://rust.amsterdam/" target="_blank">Rust Amsterdam</a></li>
        </ul>
    </div>
    <div class="navbar-end">
        <a class="btn btn-accent" href="https://broadstack.dev/" target="_blank">Broadstack.dev</a>
    </div>
</div>

<slot />