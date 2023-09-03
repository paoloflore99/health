
<script>
	export default {

}
</script>

<template>
    <div class="colore-sfondo">
        <div class="container p-5">
            <div class="introduzzione-dottori">
                <img src="../assets/img/icon-5.png" alt="">
                <h2 class="titolo-doctos">MEET OUR DOCTORS</h2>
                <!--da mettere la linea sotto-->
                <div class="paragrafo-doctos">
                    <p>Sed Ut Perspiciatis Unde Omnis Iste Natus Error Sit Voluptatem</p>
                    <p>Accusantium Doloremque Laudantium, Totam Rem Aperiam, Eaque</p>
                    <p>Ipsa Quae Ab Illo Inventore Veritatis Et Quasi Architecto Beatae</p>
                </div>

            </div>
            <div class="row container-dottori">
                <div class="col-4">
                    <div class="card border border-0 rounded-0" style="width: 22rem;">
                        <img src="../assets/img/doctor-1.jpg" class="card-img-top rounded-0" alt="...">
                        <div class="card-body">
                            <div class="p-3 titolo-card">
                                <p class="card-title">JON SNOW</p>
                                <p  class="card-title">Anesthesiologist</p>
                            </div>
                            <div class="p-3 color-paragrafo">
                                <p class="card-text">At vero eos et accusamus et iusto</p>
                                <p class="card-text">odio dignissimos ducimus qui</p>
                                <p class="card-text">blanditiis praesentium voluptatum</p>
                                <p>deleniti atque</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-4">
                    <div class="card border border-0 rounded-0" style="width: 22rem;">
                        <img src="../assets/img/doctor-2.jpg" class="card-img-top rounded-0 img-hover" alt="...">
                        <div class="card-body">
                            <div class="p-3 titolo-card">
                                <p class="card-title">TONY STARK</p>
                                <p  class="card-title">Cardiologist</p>
                            </div>
                            <div class="p-3 color-paragrafo">
                                <p class="card-text">At vero eos et accusamus et iusto</p>
                                <p class="card-text">odio dignissimos ducimus qui</p>
                                <p class="card-text">blanditiis praesentium voluptatum</p>
                                <p>deleniti atque</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-4" >
                    <div class="card border border-0 rounded-0" style="width: 22rem;">
                        <img src="../assets/img/doctor-3.jpg" class="card-img-top rounded-0" alt="...">
                        <div class="card-body">
                            <div class="p-3 titolo-card">
                                <p class="card-title">ANNA SMITH</p>
                                <p  class="card-title">Nurse Practitioner</p>
                            </div>
                            <div class="p-3 color-paragrafo">
                                <p class="card-text">At vero eos et accusamus et iusto</p>
                                <p class="card-text">odio dignissimos ducimus qui</p>
                                <p class="card-text">blanditiis praesentium voluptatum</p>
                                <p>deleniti atque</p>

                                <div class=""><!--icone social-->
                                    <i class="fa-brands fa-facebook-f"></i>
                                    <i class="fa-brands fa-twitter"></i>
                                    <i class="fa-brands fa-square-instagram"></i>
                                </div>

                            </div>


                            <!-- <a href="#" class="btn btn-primary">Go somewhere</a> -->
                        </div>
                    </div>
                </div>

                
            </div>

        </div>
    </div>
</template>

<style lang="scss" scoped>
.colore-sfondo {
    background-color: #E5E5E5;
    height: 130vh;
}

.color-paragrafo {
    color: #747373;
}

.introduzzione-dottori {
    text-align: center;
    margin-bottom: 100px;
}
.titolo-card {
    font-size: 1.1rem;
}


img {
    transition: 1s;
}
.img-hover:hover {
    transition: 1s;
}

.paragrafo-doctos {
    font-size: 1.3rem;
}

.titolo-doctos {
    font-size: 2.5rem;
}


</style>