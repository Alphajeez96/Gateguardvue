<template>
    <nav class="navbar navbar-expand-lg navbar-light our-nav col-12 border-bottom">
    <a class="navbar-brand app-logo" href="index.html">
        <img src="../../public/Logo.png" alt="">
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
                    <a class="dropdown-item" href="web-providers.html">Service Directory</a>
                    <a class="dropdown-item" href="#">Resident App</a>
                    <a class="dropdown-item" href="#">Guard App</a>
                </div>
            </li>
            <li class="nav-item mx-1">
                <a class="nav-link" href="partners.html">Partners</a>
            </li>
            <li class="nav-item mx-1">
                <a class="nav-link" href="aboutus.html">About Us</a>
            </li>
            <li class="nav-item mx-1">
                <a class="nav-link" href="contactus.html">Contact Us</a>
            </li>

        </ul>
        <button class="btn btn-success login-btn mx-2" onclick="location.href='login.html'">LOGIN</button>
        <button class="btn btn-outline-success signup-btn mx-2"
            onclick="location.href='https://play.google.com/store/apps/details?id=com.hng.xgateapp'">DOWNLOAD</button>
    </div>
</nav>
</template>

<style scoped>
    /* Navbar CSS */
.app-logo{
    margin-left: 7vw;
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