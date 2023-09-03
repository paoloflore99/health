<script>

</script>

<template>

    <nav class=" sfondo-nav text-white">
        <div class=" d-flex justify-content-between">
            <div class="p-5">
                <a href="#"><img src="../assets/img/medical_logo_1x_light.png" alt=""></a>
            </div>
            
            <div class="p-5">
                <ul class=" list-inline align-items-center d-flex">
                    <li class="list-inline-item"><a class="link-nav nav-link" href="#">HOME</a></li>
                    <li class="list-inline-item"><a class="nav-link" href="#">ABOUT</a></li>
                    <li class="list-inline-item"><a class="nav-link" href="#">DEPARTMENTS</a></li>
                    <li class="list-inline-item"><a class="nav-link" href="#">ARTICLES</a></li>
                    <li class="list-inline-item"><button class="btn-nav p-2 text-white border border-0"><strong>MAKE APPOINTMENT</strong></button></li>
                </ul>

            </div>
        </div>


        <div class="container">
            <div class="row">
                <div class="col-8">
                    <h1 class="size-titolo">Caring<span class="color-uno"> For Life</span></h1>
                    <p class="size-paragrafo">Kind words can be short and easy to speak, but their echoes are truly endless. Avada Health focuses on you as if it was our own family.</p>
                    <button class="btn-nav p-3 text-white border border-0">LEARN MORE</button>
                </div>
                <div class="col-4">
                    <!--DA METTERE IL RIQUADRO // NON NECESSARIO-->
                </div>


            </div>
        </div>
    </nav>


</template>

<style lang="scss" scoped>
.color-uno {
    color: #3bafbf;
}

.sfondo-nav {
    background-image: url(../assets/img/header-image-homepage.jpg);
    height: 95vh;
}

ul.list-inline li {
    margin-right: 30px; 
}

.link-nav {
    color: #3bafbf;
}

a:hover {
    color: #3bafbf;
    transition: 0.5s;
}

a {
    transition: 0.5s;
}

.btn-nav {
    background-color: #3bafbf;
    transition: 0.5s;
}

.btn-nav:hover {
    background-color: #327ec7;
    transition: 0.5s;
}

.size-titolo {
    font-size: 4rem;
}

.size-paragrafo {
    font-size: 30px;
}

</style>