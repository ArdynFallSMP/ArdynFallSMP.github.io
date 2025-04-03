
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <div class="d-flex align-items-center">
            <div class="navbar-brand"><a href="/" class="nav-link text-light">ShopSearch</a></div>
            <a href="/manage_shops" class="btn btn-secondary ms-3">
                Manage Shops
            </a>
        </div>
        <div class="ms-auto">
            <form>
                <!-- Register buttons -->
                <div class="text-end">
                    <!-- svelte-ignore a11y_consider_explicit_label -->
                    <button type="button" data-mdb-button-init data-mdb-ripple-init class="btn btn-primary btn-block mb-1">
                        <i class="fa-brands fa-discord fs-3 mx-3"></i>
                    </button>
                </div>
            </form>
        </div>
    </div>
</nav>

<div class="d-flex align-items-center justify-content-center m-5">
    <h1>Hello username! It's good to see you!</h1>
</div>
<!-- TODO: CHANGE THIS INTO -->
<div class="row m-4">
    <div class="col-sm-4">
        <div class="card">
        <div class="card-body">
            <h5 class="card-title">Shop 1</h5>
            <p class="card-text">Sus</p>
            <a href="/manager" class="btn btn-primary">Manage</a>
        </div>
        </div>
    </div>
    <div class="col-sm-4">
        <div class="card">
        <div class="card-body">
            <h5 class="card-title">Shop 2</h5>
            <p class="card-text">Sus</p>
            <a href="/manager" class="btn btn-primary">Manage</a>
        </div>
        </div>
    </div>
    <div class="col-sm-4">
        <div class="card">
        <div class="card-body">
            <h5 class="card-title">Shop 3</h5>
            <p class="card-text">Sus</p>
            <a href="/manager" class="btn btn-primary">Manage</a>
        </div>
        </div>
    </div>
</div>

<div class="row m-4">
    <div class="d-flex align-items-center justify-content-center">
        <button class="btn btn-primary btn-block mb-1">Create new shop</button>
    </div>
</div>


<footer>
    <div class="container">
        <p class="mb-0">&copy; 2025 Copyright: <a class="text-white" target="_blank" href="https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode.txt">ArdynFallSMP & KaiyWhiteSnow.</a></p>
    </div>
</footer>