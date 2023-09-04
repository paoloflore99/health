
<script>
export default {

}
</script>

<template>
    <div class="ultima-sezzione">
        <div class="carosello ">
            <div class="container text-center">
                <img src="../assets/img/client-logos-1-200x188.png" alt="">
                <img src="../assets/img/client-logos-2-200x188.png" alt="">
                <img src="../assets/img/client-logos-3-200x188.png" alt="">
                <img src="../assets/img/client-logos-4-200x188.png" alt="">
            </div>
            
        </div>

        <div class="col-12 meta d-flex justify-content-between ">
            <div class="col-4 p-4">
                <img src="../assets/img/medical_logo_1x_dark.png" alt="">
                <p class="color">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium dolemue launti
                    totam aperiam, eaque ipsa quae abillo. Invente veriatis et quasi architecto beatae luptatem accusantium,
                    remaperiamsiat. Voluptatem accusest etsium doloremque laudaien. Lorem ipsum sits dolores ets unser.</p>
                <p>LEARN MORE ABOUT US</p>
                <div class="d-flex"><!--icone social-->
                    <div class="rounded-2 P-1 facebook icona spazzio">
                        <a href="#">
                            <i class="fa-brands fa-facebook-f  "></i>
                        </a>

                    </div>

                    <div class="rounded-2 P-1 twitter icona spazzio">
                        <a href="#">
                            <i class="fa-brands fa-twitter  "></i>
                        </a>

                    </div>

                    <div class=" rounded-2 P-1 instagram icona spazzio">
                        <a href="#">
                            <i class="fa-brands fa-instagram"></i>
                        </a>

                    </div>

                    <div class=" rounded-2 P-1 youtube icona">
                        <a href="#">
                            <i class="fa-brands fa-youtube"></i>
                        </a>
                    </div>

                </div>
            </div>
            <div class="col-4 p-4">
                <h5>CONTACT INFORMATION</h5>
                <div class="linitta">
                    <!-- <img class="border border-1 " src="../assets/img/image (1).png" alt=""> -->
                </div>
                
                <p class="color">121 King Street, London United Kingdom</p>
                <p class="color">1.800.458.556</p>
                <div class="card-mio">
                    <p class="color p-4">For privacy reasons Google Maps needs your permission to be <br> loaded.</p>
                    <button class="btn-Header p-3 text-white border border-0 container-fluid">I ACCEPT</button>
                </div>
            </div>
            <div class="col-4 p-4">
                <h5>MEDICAL DEPARTMENTS</h5>
                <!-- <img src="../assets/img/image (1).png" alt=""> -->
                <ul>
                    <li><i class="fa-solid fa-check cerchio p-1"></i> Cardiology</li>
                    <li><i class="fa-solid fa-check cerchio p-1"></i> Pediatrics</li>
                    <li><i class="fa-solid fa-check cerchio p-1"></i> Diabetes Care</li>
                    <li><i class="fa-solid fa-check cerchio p-1"></i> Pre-natal Care</li>
                    <li><i class="fa-solid fa-check cerchio p-1"></i> Ultrasound Echocardiogram</li>
                </ul>
                <div class="btn-centrare text-center p-5">
                    <button class="btn-Header p-3 text-white border border-0 container-fluid">VIEW OUR DEPARTMENTS</button>
                </div>

            </div>
        </div>

        <div class="chiusura">
            <p class="ultima-parte"><span class="color">© Copyright 2012 - 2023 |</span> Avada Website Builder by
                ThemeFusion <span class="color">| All Rights Reserved | Powered by </span> WordPress</p>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.ultima-sezzione {
    height: 100vh;
}

.carosello {
    height: 30vh;
    background-image: url(../assets/img/rgb-gradient-bar-for-logo-carrasel.jpg);
}

.meta {
    height: 62vh;
    padding-top: 50px;
    padding-bottom: 50px;
    align-items: center;
}

.chiusura {
    height: 8vh;
    background-color: #e5e5e5;
    align-items: center;
    // margin-left: 100px;
}

.card-mio {
    background-color: #DDDDDD;
    width: 90%;
    // height: 70%;
    // padding-bottom: 100px;
}

.btn-Header {
    background-color: #3bafbf;
    transition: 0.5s;
    // margin-left: 10px;
    // margin-right: 10px;
    // padding: 10px;
    width: 100%;
    
}

.btn-Header:hover {
    background-color: #327ec7;
    transition: 0.5s;
}

.cerchio {
    width: 1.7rem;
    height: 1.7rem;
    background-color: #3bafbf;
    color: white;
    text-align: center;
    align-items: center;
    border-radius: 50%;

}

.color {
    color: #949494;
}

.color {
    line-height: 3rem;
}

li {
    list-style-type: none;
    color: #949494;
    padding-top: 1rem;
}

.ultima-parte {
    margin-left: 100px;
    font-size: 14px;

}

a {
    text-decoration: none;
    color: white;
}

.facebook {
    background-color: #2a71b4;
}

.twitter {
    background-color: #1e8db9;
}

.instagram {
    background-color: #3b7a97;
}

.youtube {
    background-color: red;
}

.icona {
    width: 2rem;
    height: 2rem;
    color: white;
    text-align: center;
    font-size: 1.2rem;
}

.spazzio {
    margin-right: 10px;
}


.linetta {
    
    border: 5px solid black;
    width: 30px;
}
// .btn-centrare {

// }
</style>