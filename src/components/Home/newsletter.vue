<template>
     <div class="col-12 download-footer px-0">
                <div class="col-12 download-app row mx-0">
                    <div class="col-12 col-md-5">
                        <div class="col-12 col-md-9 download-image-con mt-5 mx-auto">
                            <img src="../../../public/download-app-image.png" alt="">
                        </div>
                    </div>
                    <div class="col-12 col-md-7 mb-2">
                        <div class="col-10 details-con mx-auto">
                            <h2>DOWNLOAD THE APP</h2>
                            <hr class="green-underline mt-2 ml-0">
                            <p >Worry less abot security saying goodbye to the old scary security <br>
                                system. Monitor every activity at your residence with just one click. <br>
                                GateGUARD is the perfect App that solves every of your security <br> worries.</pc>
                            <div class="col-12 download-links row mx-0 px-0 mt-5">
                                <div class="col-12 col-sm-8 mt-2 col-md-5 store-link px-0">
                                    <img src="images/playstore.png" style="cursor: pointer" alt=""
                                        onclick="location.href='https://play.google.com/store/apps/details?id=com.hng.xgateapp'">
                                </div>
                                <div class="col-12 col-sm-8 mt-2 col-md-5 store-link px-0">
                                    <img src="images/appstore.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 subscribe row mx-0">
                    <div class="col-12 col-sm-8 col-md-6 subscribe-words mx-auto">
                        <div class="col-12 col-md-8 mt-5 mx-auto">
                            <h2>SUBSCRIBE TO OUR <br> NEWSLETTER</h2>
                            <hr class="green-underline mt-2 ml-0">
                            <div class="col-12 row mx-0 px-0 breakdown-feature">

                                <ul class="pt-2 col-12">
                                    <li class="pt-2 col-12 list-star">Guards real time notifications on visitors coming
                                        to visit.</li>

                                    <li class="pt-2 col-12 list-star">Get real time notifications on visitors coming to
                                        your home.</li>

                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-md-6 subscribe-form mb-5">
                        <div class="col-12 col-sm-8 col-md-10 mx-auto">
                            <form id="form-submit">
                                <div class="form-group">
                                    <input type="text" id="name" class="form-control" placeholder="Name">
                                </div>
                                <div class="form-group">
                                    <input type="email" id="email" class="form-control" placeholder="Email">
                                </div>
                                <button type="submit" id="submit" class="btn col-12">Submit</button>
                            </form>
                        </div>
                    </div>
                </div>
     </div>
</template>

<style scoped>
    .subscribe {
  min-height: 60vh;
}
.subscribe h2{
  font-weight: bold;
}
.subscribe-form > div {
  margin-top: 15vh;
}
.subscribe-form input {
  color: black;
  /* border-radius: 0px; */
  border: 1px solid black;
}
.subscribe-form input::placeholder {
  color: black;
}
.subscribe-form input:focus {
  box-shadow: none;
  border: 1px solid black;
}
.subscribe-form button {
  background: #49a347;
  color: white;
  border: none;
  /* border-radius: 0px; */
}
/* .subscribe-form button:hover {
  background: white;
  color: #49a347;
  border: 1px solid #49a347;
  border-radius: 0px;
} */
.subscribe-form button:focus {
  background: #49a347;
}
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
.details-cont{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight: 900;
    font-size: 80px;
}
</style>