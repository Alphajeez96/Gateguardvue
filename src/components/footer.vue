<template>
     <!-- DOWNLOAD APP AND FOOTER SECTIONS -->
 <!-- <div class="col-12 download-footer px-0">
        <div class="col-12 download-app row mx-0">
            <div class="col-12 col-md-5">
                <div class="col-9 download-image-con mt-5 mx-auto">
                    <img src="../../public/download-app-image.png" alt="">
                </div>
            </div>
            <div class="col-12 col-md-7 mb-2">
                <div class="col-10 details-con mx-auto">
                    <h2>DOWNLOAD THE APP</h2>
                    <hr class="green-underline mt-2 ml-0">
                    <p>Worry less abot security saying goodbye to the old scary security <br>
                        system. Monitor every activity at your residence with just one click. <br>
                        GateGUARD is the perfect App that solves every of your security <br> worries.</p>
                    <div class="col-12 download-links row mx-0 px-0 mt-5">
                        <div class="col-12 col-sm-8 mt-2 col-md-5 store-link px-0">
                            <img src="../../public/playstore.png" alt="">
                        </div>
                        <div class="col-12 col-sm-8 mt-2 col-md-5 store-link px-0">
                            <img src="../../public/appstore.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div> -->
        <footer class="border col-12 app-footer">
            <div class="col-11 mx-auto row mx-0 mt-5">
                <div class="col-12 col-md">
                    <ul class="list-group footer-list">
                        <li class="list-group-item pb-2 list-header">Features</li>
                        <li class="list-group-item py-1 footer-links ">Visitor Management</li>
                        <li class="list-group-item py-1 footer-links ">Delivery Management</li>
                        <li class="list-group-item py-1 footer-links ">Communication Management</li>
                    </ul>
                </div>
                <div class="col-12 col-md">
                    <ul class="list-group footer-list">
                        <li class="list-group-item pb-2 list-header">Company</li>
                        <li class="list-group-item py-1 footer-links ">About Us</li>
                        <li class="list-group-item py-1 footer-links ">Contact Us</li>
                        <li class="list-group-item py-1 footer-links ">Frequently Asked Questions</li>
                        <li class="list-group-item py-1 footer-links ">Terms and Conditions</li>
                    </ul>
                </div>
                <div class="col-12 col-md">
                    <ul class="list-group footer-list">
                        <li class="list-group-item pb-2 list-header">Contact</li>
                        <li class="list-group-item py-1 footer-links">Plot 6, Gibbert Avenue, Flutter
                            estate, <br>
                            Agidingbi, Ikeja, Lagos state.</li>
                        <li class="list-group-item py-1 footer-links">+234 705 784 3748</li>
                        <li class="list-group-item py-1 footer-links">contact@gateguard.org</li>
                    </ul>
                </div>
                <div class="col-8 col-sm-6 col-md">
                    <div class="col-12 col-md-8 mt-3 footer-logo">
                        <img src="../../public/gateguard-white.png" alt="">
                    </div>
                    <div class="col-12 col-md-8 mt-3 social-links">
                        <img class="mx-2" src="../../public/instagram.png" alt="">
                        <img class="mx-2" src="../../public/twitter.png" alt="">
                        <img class="mx-2" src="../../public/facebook.png" alt="">
                    </div>
                    <div class="col-12 mt-2 footer-download">
                        <p class="mb-1">Download App</p>
                        <div class="col-12 row mx-0 px-0">
                            <div class="col px-0 app-cons mr-2">
                                <img src="../../public/playstore.png" alt="">
                            </div>
                            <div class="col px-0 app-cons">
                                <img src="../../public/appstore.png" alt="">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </footer>
    </div>
</template>

<style scoped>
    /* Download App CSS */
.download-app{
    min-height: 70vh;
    background: #e5e5e5;
}
.download-image-con {
    height: 55vh;
}
.download-image-con img{
    height: 100%;
    width: 100%;
    object-fit: contain;
}
.details-con{
    margin-top: 15vh;
}
.download-app h2{
    font-weight: bold;
}
.download-app p{
    font-size: 12px;
    font-weight: bold;
}
.store-link {
    height: 9vh;
}
.store-link img{
    height: 100%;
    width: 80%;
}
/* Footer CSS */
.app-footer{
    min-height: 40vh;
    background: #49a347;
}
.list-header{
    background: inherit;
    color: white;
    border: none;
    font-size: 16px;
    font-weight: bold;
}
.footer-links {
    background: inherit;
    color: white;
    border: none;
    font-size: 12px;
    cursor: pointer;
}
.footer-logo{
    height: 5vh;
}
.footer-logo img{
    height: 100%;
    width: 100%;
}
.social-links img{
    height: 2vh;
    width: 2vh;
    cursor: pointer;
}
.footer-download{
    height: 10vh;
}
.footer-download p{
    color: white;
    font-size: 12px;
}
.app-cons {
    height: 5vh;
}
.app-cons img{
    height: 100%;
    width: 100%;
}

.login{
    background: #fff;
    height: 250px;
    margin-top: 80px;
    margin-bottom: 60px;
    border-radius: 5px;
    display: flex;
    flex-flow: column nowrap;
}

.login h3{
    font-weight: bold;
    padding: 20px 0px;
    text-align: center;
}
.green-underline {
  width: 3vw;
  border-top: 4px solid #49a347;
}

</style>