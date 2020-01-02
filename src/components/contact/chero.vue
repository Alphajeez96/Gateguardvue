<template>
    <div>
         <div class="col-12 welcome-image border-bottom">
                <!--  -->
                <div class="col-12 col-md-6 mx-auto welcome-image-words text-center">
                    <h1 class="mt-5 mb-4">Gate Guard<br>Surely Secure</h1>
                    <p class="mb-4">Get to know about our Partners and and their properties.</p>
                    <button class="btn request-demo-btn mb-5">REQUEST DEMO</button>
                </div>
        </div>
                <div class="col-12 contact-form-section">
                <h1 class="text-center mt-5 mb-0 bold">CONTACT US</h1>
                <hr class="green-underline mt-2">
                <div class="contact-con col-12 col-md-11 mx-auto row mx-0 mt-5">
                    <div class="col-12 col-md-6 always-here">
                        <h1 class="bold mb-4">We are always here <br> for you!</h1>
                        <p>Do you have any questions or you want to make an enquiry?
                            Tell us about yourself and your query. We promise to answer you within 6 business hours.</p>

                        <ul class="list-group list-group-flush">
                            <li class="list-group-item bold list-title">Contact hours:</li>
                            <li class="list-group-item py-2">Mon 8:00am - 5:00pm</li>
                            <li class="list-group-item py-2">Tue 8:00am - 5:00pm</li>
                            <li class="list-group-item py-2">Wed 10:00am - 8:00pm</li>
                            <li class="list-group-item py-2">Mon 8:00am - 5:00pm</li>
                            <li class="list-group-item py-2">Mon 9:00am - 3:00pm</li>
                        </ul>
                    </div>
                    <div class="col-12 col-md-6 contact-form">
                        <form class="border col-12 col-md-10 mt-5 px-4">
                            <h5 class="text-center mt-5">Reach out to us</h5>
                            <div class="form-group">
                                <input type="text" class="form-control" placeholder="Name*">
                            </div>
                            <div class="form-group">
                                <input type="tel" class="form-control" placeholder="Phone*">
                            </div>
                            <div class="form-group">
                                <input type="email" class="form-control" placeholder="Email*">
                            </div>
                            <div class="form-group">
                                <textarea type="text" class="form-control" placeholder="Comment"></textarea>
                            </div>
                            <div class="col-12 text-center mb-5">
                                <button type="submit" class="btn usual-btn mt-3 text-center">SUBMIT</button>
                            </div>
                        </form>
                    </div>
                    <div class="col-12 col-md-6">
                        <div class="col-12 embedded-map my-5">
                                <iframe src="https://maps.google.com/maps?q=agidingbi%2Cikeja&t=&z=19&ie=UTF8&iwloc=&output=embed"></iframe>
                        </div>
                    </div>
                    <div class="col-12 col-md-6 mb-5">
                        <div class="col-12 col-md-8 mx-auto mt-5 contact-info">
                            <h4 class="bold mt-5 mb-3">Walk in for a cup of coffee</h4>
                            <p class="mb-3">Plot 6, Gibbert Avenue, Flutter estate, Agidingbi, Ikeja, Lagos state.</p>
                            <span>+234 705 784 3748</span>
                        </div>
                    </div>
                </div>
            </div> 
    </div>
</template>

<style scoped>
    .welcome-image {
  min-height: 60vh;
  background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url("../../../public/contact-header.png");
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
.contact-con {
    min-height: 100vh;
}
.always-here {
    min-height: 40vh;
}
.always-here p {
    font-size: 18px;
    line-height: 5vh;
}
.always-here li {
    border: 0;
}
.always-here .list-group-item {
    font-size: 14px;
}
.always-here .list-title{
    font-size: 18px;
}
.contact-form form {
    border-radius: 12px;
}
.contact-form input,.contact-form textarea {
    border: none;
    border-bottom: 1px solid grey;
    border-radius: 0px;
    overflow: hidden;
}
.contact-con button {
    font-size: 14px;
}
.embedded-map {
    height: 50vh;
}
.embedded-map iframe {
    height: 100%;
    width: 100%;
    border: 1px solid black;
}
.contact-info {
    border: 1px solid transparent
}
</style>