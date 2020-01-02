<template>
<div>
  <div class="col-12 gateguard-desc row mx-0 mb-5 mt-5">
                <div class="col-12 col-md-7">
                    <div class="col-12 col-md-9 mx-auto what-is-gateguard mt-5">
                        <h1>What is GateGuard?</h1>
                        <hr class="green-underline mt-2 ml-0">
                        <p class="mt-4">An app that makes life easy for everyone, it is a security <br>
                            solution for gated apartment and estates. It helps residents <br>
                            securely manage who goes in and out of the gate. Its fully <br>
                            packed features has helped reduce the challenged faced <br>
                            during visitor authorization to a single click.</p>
                    </div>
                </div>
                <div class="col-12 col-md-5">
                    <div class="col-12 col-md-10 gateguard-image">
                        <img src="../../../public/gateguard-image.png" alt="">
                    </div>
                </div>
            </div>
            <div class="col-12 feature-breakdown">
                <div class="col-12 col-md-11 mx-auto row mx-0 breakdown-con">
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-4">
                            <h3 class="breakdown-header">Residents</h3>
                            <hr class="green-underline mt-2 ml-0">
                            <div class="col-12 row mx-0 px-0 breakdown-feature">

                                <!-- <img class="" src="images/star.png" alt=""> -->
                                <ul class="pt-2 col-12">
                                    <li class="pt-2 col-12 list-star">Residents can update "Expected Visitor" details on
                                        GateGuard mobile app.</li>
                                    <li class="pt-2 col-12 list-star">Get real time notifications on visitors coming to
                                        your home.</li>

                                    <li class="pt-2 col-12 list-star">Staff management service (Cook, Maid, Nanny,
                                        Driver) hire through the app.</li>

                                    <li class="pt-2 col-12 list-star">Residents get alerts whenever their staff checks
                                        in/out the gate.</li>

                                </ul>
                            </div>
                           
                            <div class="col-12">
                                <button class="btn learn-more-btn mb-5"
                                    onclick="location.href='residents learn more.html'">
                                    LEARN MORE
                                </button>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-5 breakdown-image mx-auto px-0">
                            <img src="../../../public/mansion.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-11 mx-auto row mx-0 breakdown-con">
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-5 breakdown-image mx-auto px-0">
                            <img src="../../../public/gate.png" alt="">
                        </div>
                    </div>
                    <div class="col-12 col-md">
                        <div class="col-12 col-md-10 mt-4 ml-auto">
                            <h3 class="breakdown-header">Security Guards</h3>
                            <hr class="green-underline mt-2 ml-0">
                            <div class="col-12 row mx-0 px-0 breakdown-feature">

                                <ul class="pt-2 col-12">
                                    <li class="pt-2 col-12 list-star">Guards can view "Expected Visitors" details on
                                        GateGuard mobile app.</li>

                                    <li class="pt-2 col-12 list-star">Guards real time notifications on visitors coming
                                        to visit.</li>

                                    <li class="pt-2 col-12 list-star">Guards will now have access to the list of
                                        blacklisted staffs to
                                        prevent entry.</li>

                                    <li class="pt-2 col-12 list-star">Faster check-ins at the gate which has eliminated
                                        the long queues.</li>

                                </ul>
                            </div>
                            
                            <div class="col-12">
                                <button class="btn learn-more-btn mb-5" onclick="location.href='guards learn.html'">
                                    LEARN MORE
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div> 
</div>
</template>

<style scoped>
    .what-is-gateguard {
  min-height: 40vh;
}
.what-is-gateguard h1 {
  font-weight: bold;
}
.what-is-gateguard p {
  font-size: 16px;
}
.gateguard-image {
  height: 60vh;
}
.gateguard-image img {
  height: 100%;
  width: 100%;
  object-fit: contain;
}
.feature-breakdown {
  min-height: 100vh;
  background: #e5e5e5;
}
.breakdown-con {
  min-height: 60vh;
}
.breakdown-header {
  color: #49a347;
  font-weight: bold;
}
.breakdown-feature {
}
.breakdown-feature img {
  height: 5vh;
  width: 5vh;
}
.breakdown-feature p {
  font-size: 10px;
  font-weight: bold;
}
.learn-more-btn {
  background: #49a347;
  color: white;
  /* border-radius: 0px; */
}
.breakdown-image {
  height: 45vh;
}
.breakdown-image img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

</style>