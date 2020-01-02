<template>
    <div>
         <div class="main">
        <div class="kc-first-cont">
            <h1>Estate Partners Using <br> GateGuard</h1>
            <p>Get to know our partners and their properties</p>
            <button>become a partner</button>
        </div>
        <div class="our-part-cnt">
            <div class="kc-cont-holder">
                <div class="kc-text">
                    <p>our partners</p>
                    <hr class="hr-partners hr">
                </div>
                <div class="switch-cont" id="toggleCont">
                    <span class="toggle-active" id="resident">Residential</span>
                    <span id="comm">Commericial</span>
                    <!-- <span id="corporate">Commericial</span> -->
                </div>
    </div>
        </div>
         </div>
         <div class="residenial-holder" id="resCont">
                    <div class="res-showcase-cont">
                        <div class="showcase">
                            <div class="logo-btn">
                                <img src="../../../public/fortis.png" alt="fortis-logo" class="logo">
                                 <router-link to="/coming">
                                <button class="view-estate">view           
                                </button>
                                 </router-link>
                                
                            </div>
                        </div>
                        <div class="showcase john">
                            <div class="logo-btn">
                                <img src="../../../public/John.png" alt="fortis-logo" class="logo">
                                   <router-link to="/coming">
                                <button  class="view-estate">view</button>
                                   </router-link>
                            </div>
                        </div>
                        <div class="showcase real">
                            <div class="logo-btn">
                                <img src="../../../public/real.png" alt="" class="logo">
                                   <router-link to="/coming">
                                <button  class="view-estate">view</button>
                                   </router-link>
                            </div>
                        </div>
                        <div class="showcase wind ">
                            <div class="logo-btn">
                                <img src="../../../public/windermere.png" alt="" class="logo">
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase king ">
                            <div class="logo-btn">
                                <img src="../../../public/king.png" alt="" class="logo">
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase alex">
                            <div class="logo-btn">
                                <img src="../../../public/Alex.png" alt="" class="logo">
                                <button class="view-estate">view</button>
                            </div>
                        </div>
                    </div>
                    <div class="res-showcase-cont hide">
                        <div class="showcase">
                            <div class="logo-btn">
                                <img src="../../../public/fortis.png" alt="fortis-logo" class="logo">
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase john">
                            <div class="logo-btn">
                                <img src="../../../public/John.png" alt="fortis-logo" class="logo">
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase real">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase wind ">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase king wind">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase alex">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                    </div>
                    <div class="res-showcase-cont hide">
                        <div class="showcase">
                            <div class="logo-btn">
                                <img src="images/Fortis.png" alt="fortis-logo" class="logo">
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase john">
                            <div class="logo-btn">
                                <img src="images/John.png" alt="fortis-logo" class="logo">
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase real">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase wind ">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase king wind">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase alex">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  class="view-estate">view</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="commercial-holder hide" id="commCont">
                    <div class="comm-showcase-cont ">
                        <div class="showcase">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase john">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase real">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase wind ">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase king wind">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase alex">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                    </div>
                    <div class="comm-showcase-cont hide">
                        <div class="showcase">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase john">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase real">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase wind ">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button   class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase king wind">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase alex">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                    </div>
                    <div class="comm-showcase-cont hide">
                        <div class="showcase">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase john">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase real">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase wind ">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logoComm</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase king wind">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                        <div class="showcase alex">
                            <div class="logo-btn">
                                <!-- <img src="" alt=""> -->
                                <p>logo</p>
                                <button  t class="view-estate">view</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="slider" id="carouselHolder">
                </div>
            </div>
        
        

</template>
<script>
export default {
    data(){
        return{

        }

    } ,
    computed: {
        rest() {
            
                // this.$router.push('contact');
            
        }
    }
}
</script>

<style scoped>
    .main{
    display: grid;
    grid-template-rows: repeat(3, auto);
    width: 100%;
}
.kc-first-cont{
    width: 100%;
    height: 70vh;
    background: url(../../../public/partners-img-01.png), #000000a4;
    background-size: cover;
    opacity: .9;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: #fff;
    padding: 0px 10px;
}
.kc-first-cont h1 {
    font-size: 30px;
    line-height: 1em;
    text-align: center;
}
.kc-first-cont p {
    margin: 10px 0px;
    font-size: 20px;
    text-align: center;
}
.kc-first-cont button {
    border: none;
    background-color:#49A347;
    color: #fff;
    padding: .7em 1.2em;
    margin: 20px 0px;
    text-transform: uppercase;
    border-radius: 0.25em;
    font-size: 12px;
}
.our-part-cnt{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.kc-cont-holder{
    width: 85%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 20px 0px;
}
.kc-text p {
    font-size: 2em;
    color: #000;
    text-transform: uppercase;
    font-weight: bold;
    margin: 0%;
    padding: 0%;
}
.hr {
    border: none;
    width: 50px;
    height: 2px;
    background-color: #49A347;
    margin-top: 0%;
}

.switch-cont{
    width: 100%;
    display: flex;
    margin-bottom: 2rem;
}
.switch-cont span {
    border: 1px solid #49A347;
    padding: .5em 1em;
    font-weight: bold;
}
.toggle-active {
    color: #fff;
    background-color: #49A347;
}
.commercial-holder, .residenial-holder{
    width: 100%;
}
.res-showcase-cont, .comm-showcase-cont{
    display: grid;
    grid-template-columns: repeat( auto-fit, minmax(250px, 400px) );
    grid-gap: 3rem;
    justify-content: center;
    align-items: center;
    width: 100%;
    transition: .4s ease-in-out;
}
.hide{
    display: none;
    /* transform: scale(0%); */
}
#resident, #comm {
    cursor: pointer;
    transition: .4s ease-in-out;
}
.showcase{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 350px;
    height: 350px;
    background: url(../../../public/fortis-bg.png);
    background-size:cover;
}
.real{
    background: url(../../../public/real-estate.png);
}
.john{
    background: url(../../../public/j-l-scott.png);
}
.wind{
    background: url(../../../public/win.png);
}
.alex{
    background: url(../../../public/alexandria.png);
}
.king{
    background: url(../../../public/king-estate.png);
}
.logo-btn{
    width: 80%;
    height: 80%;
    background-color: #0000009d;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: #fff;
}
.logo{
    width: 100px;
    height: 70px;
    object-fit: contain;
    margin-bottom: 10px;
    color: #fff;
}
.view-estate{
    padding: .5em 1.5em;
    border: 1px solid #fff;
    color: #fff;
    background-color: transparent;
    margin-top: 10px;
}


/* ------------------------------------ */

.slider{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    height:100px;
}

.span-carousel {
    width: 50px;
    height: 5px;
    margin-right: 5px;
    background-color: #979797;
    border-radius: 3px;
}
.slider-active{
    background-color: #000 !important;
}

/* ------------------------------ */
.download{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height:500px;
    background-color:rgba(196, 196, 196, 0.32);
    padding: 7px;;
}
.download-cont{
    width: 80%;
    display: grid;
    justify-content: center;
    align-items: center;
    grid-template-columns: repeat( auto-fit, minmax(250px, 1fr) );
    background-color:transparent;
}

.phone-pics{
    display: flex;
    justify-content: space-around;
}
.splash-1{
    margin-bottom: 4em;
}
.splash-2{
    margin-top: 4em;
}
/* MEDIA QUERY */
@media screen and (max-width: 768px) {
    .kc-first-cont h1 {
        font-size: 2em;
        line-height: 1em;
        text-align: center;
    }
    .kc-first-cont p {
        margin: 5px 0px;
        font-size: 15px;
    }

}
@media screen and (max-width: 450px) {
    .showcase{
    width: auto;
    }
}

/* ---------------- */
.margin{
    margin-bottom: 5px;
}

</style>