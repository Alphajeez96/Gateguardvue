<template>
     <div class="col-12 welcome-image border-bottom">
                <!--  -->
                <div  class="col-12 col-md-6  mx-auto welcome-image-words text-center">
                    <h1 class="pt-5  mb-4">Modern Gate Management <br> That Makes Life Smarter</h1>
                    <p class="mb-4">A fully packaged gate management platform for any infrastructure <br>
                        (Home, Estate, or Office). This module increases your security <br>
                        without hassle.</p>
                    <button class="btn request-demo-btn">REQUEST DEMO</button>
                </div>
            </div>
</template>

<style scoped>
    .welcome-image {
  min-height: 60vh;
  background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url("../../../public/welcome-image.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

}
.welcome-image-words {
  min-height: 50vh;
  margin-bottom: 13vh;
  padding-top: 60px;
}
.welcome-image-words h1 {
  color: white;
  font-weight: bold;
  font-size: 30px;
}
.welcome-image-words p {
  color: white;
}
.request-demo-btn {
  background: #49a347;
  color: white;
  font-size: 12px;
  /* border-radius: 0px; */
}
</style>