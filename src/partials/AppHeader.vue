<script>
export default {
    name: 'AppHeader',
}
</script>

<template>
    <header class="site-header">
        <div class="container">
            <nav class="d-flex align-items-center justify-content-between py-3">
                <a href="">
                    <img src="../../public/img/header/icon.png" alt="Boolean and Dragons Logo" class="logo">
                </a>
                <!-- /.logo -->

                <div class="" id="navbarSupportedContent">
                    <ul class="list-unstyled d-flex gap-3 w-100 justify-content-center m-0">
                        <li class="nav-item">
                            <a class="nav-link fs-4 header-text" href="">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link fs-4 link-underline-opacity-75-hover header-text" href="">Character</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link fs-4 link-underline-opacity-75-hover header-text" href="">Items</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link fs-4 link-underline-opacity-75-hover header-text" href="">Types</a>
                        </li>
                    </ul>
                </div>

                <div>
                    <br>
                </div>

            </nav>
            <!-- Right Side Of Navbar -->
        </div>
        <!-- /.container-header -->
    </header>
    <!-- /.site-header -->
</template>