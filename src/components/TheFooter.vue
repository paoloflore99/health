<script>
	export default {

}
</script>

<template>
    <footer class="footer-blocco-uno">
        <div class="container">
            <div class="row centratura-paragrafo titolo-benvenuto">
                <h2>Welcome To Avada Health</h2>
                <p class="p-3 size-testo">Sed Ut Perspiciatis Unde Omnis Iste Natus Error Sit Voluptatem <br>Accusantium Doloremque Laudantium, Totam Rem Aperiam, Eaque <br>Ipsa Quae Ab Illo</p>
            </div>
                <div class="d-flex justify-content-between">
                    <div class="centratura-paragrafo">
                        <img class="p-3" src="../assets/img/icon-1.png" alt="">
                        <h5><a href="#">SAME DAY <br> APPOINTMENTS</a></h5>
                        <p class="testo-griggio">Sed ut perspiciatis unde omnis iste</p>
                        <p class="testo-griggio">natus error sit voluptam accusantim</p>
                    </div>
                    <div class="centratura-paragrafo">
                        <img class="p-3" src="../assets/img/icon-2.png" alt="">
                        <h5><a href="#">WORLD CLASS <br>FACILITIES</a></h5>
                        <p class="testo-griggio">Sed ut perspiciatis unde omnis iste</p>
                        <p class="testo-griggio">natus error sit voluptam accusantim</p>
                    </div>
                    <div class="centratura-paragrafo ">
                        <img class="p-3"  src="../assets/img/icon-3.png" alt="">
                        <h5><a href="#">EXPERT DOCTORS</a></h5>
                        <p class="testo-griggio">Sed ut perspiciatis unde omnis iste</p>
                        <p class="testo-griggio">natus error sit voluptam accusantim</p>
                    </div>
                    <div class="centratura-paragrafo">
                        <img class="p-3" src="../assets/img/icon-4.png" alt="">
                        <h5><a href="#">COMPLEMENTARY <br> THERAPIES</a></h5>
                        <p class="testo-griggio">Sed ut perspiciatis unde omnis iste</p>
                        <p class="testo-griggio">natus error sit voluptam accusantim</p>
                    </div>
                </div>
        </div>
    </footer>

</template>

<style lang="scss" scoped>

.footer-blocco-uno {
    height: 60vh;
}

.centratura-paragrafo {
    text-align: center;
}

.titolo-benvenuto {
    margin-top: 100px;
}

.testo-griggio {
    color: #747373;
}

a:hover {
    color: #3bafbf;
    transition: 0.5s;
}

a {
    transition: 0.5s;
    text-decoration: none;
    color: black;
}

.size-testo {
    font-size: 1.5rem;
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



</style>