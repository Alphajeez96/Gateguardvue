<template>
    <nav class="navbar navbar-expand-lg navbar-light our-nav col-12 border-bottom">
    <a class="navbar-brand app-logo">
        <router-link to="/" >
        <img src="../../public/Logo.png" alt="">
        </router-link>
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse nav-utilities" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item dropdown mx-1">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
                    aria-haspopup="true" aria-expanded="false">
                    Products
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <a class="dropdown-item" >Service Directory</a>
                    <a class="dropdown-item" >Resident App</a>
                    <a class="dropdown-item" >Guard App</a>
                </div>
            </li>

            <li class="nav-item mx-1">
                <router-link to="/partners">
                <a class="nav-link" >Partners</a>
                </router-link>
            </li>
            <li class="nav-item mx-1">
                <router-link to="/about" >
                <a class="nav-link">About Us</a>
                 </router-link>
            </li>
           
            <li class="nav-item mx-1">
                <router-link to="/contact">
                <a class="nav-link" href="">Contact Us</a>
                </router-link>
            </li>

        </ul>
        <button class="btn btn-success login-btn mx-2" >LOGIN</button>
        <button class="btn btn-outline-success signup-btn mx-2">DOWNLOAD</button>
    </div>
</nav>
</template>

<style scoped>
    /* Navbar CSS */
.app-logo{
    margin-left: 7vw;
}
 .nav-link {
    text-decoration: none;
}
.nav-utilities{
    margin-right: 7vw;
}
.app-logo img{
    width: 10vw;
}
.nav-item .nav-link{
    font-size: 12px;
    font-weight: bold;
    color: black !important;
}
.nav-item .dropdown-menu {
    /* border-radius: 0px; */
}
.nav-item .dropdown-menu .dropdown-item{
    font-size: 12px;
    font-weight: bold;
}
.login-btn{
    font-size: 12px;
    width: 9vw;
}
.signup-btn{
    font-size: 12px;
    width: 9vw;
}
@media screen and (max-width: 992px) {
    .login-btn,  .signup-btn{
        width: 15vw;
    }
}

@media screen and (max-width: 768px) {
    .login-btn , .signup-btn{
        width: 100px;
        margin-left: 0rem !important;
    }
    .app-logo img {
        width: 20vw;
    }
    .app-logo {
        margin-left: 0vw;
    }

}

</style>