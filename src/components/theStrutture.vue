<script>
export default {
    data() {
        return {
            currentDate: ''
        };
    },
    mounted() {
        const today = new Date();
        const year = today.getFullYear();
        const month = String(today.getMonth() + 1).padStart(2, '0');
        const day = String(today.getDate()).padStart(2, '0');
        this.currentDate = `${year}-${month}-${day}`;
        
    }
};

</script>

<template>
    <div class="sfondo-strutture text-white">
        <img src="../assets/img/icon-7.png" alt="">
        <h1>TOUR OUR FACILITIES</h1>
        <p class="size-grande">Sed Ut Perspiciatis Unde Omnis Iste Natus Error Sit Voluptatem <br> Accusantium Doloremque
            Laudantium, Totam Rem Aperiam, Eaque <br> Ipsa Quae Ab Illo Inventore Veritatis Et Quasi Architecto Beatae</p>
        <a href="https://www.youtube.com/channel/UC_C7uAOAH9RMzZs-CKCZ62w">
            <img src="../assets/img/play-icon.png" alt="">
        </a>
    </div>


    <div class="text-white">
        <div class="col-12 d-flex justify-content-between">
            <div class="col-4 sfondo-primo distanza">
                <h5>Emergency Care</h5>
                <img class="p-2" src="../assets/img/wave-divider.png" alt="">
                <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam
                    rem aperiam, eaque</p>
                <button class="btn-margin border border-3 border-white text-white"><span class="contenuto-btn">LEARN
                        MORE</span></button>
            </div>
            <div class="col-4 sfondo-secondo distanza">
                <h5>Expert Diagnostics</h5>
                <img class="p-2" src="../assets/img/wave-divider.png" alt="">
                <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam
                    rem aperiam, eaque</p>
                <button class="btn-margin border border-3 border-white text-white"><span class="contenuto-btn">LEARN
                        MORE</span></button>
            </div>
            <div class="col-4 sfondo-terzo distanza">
                <h5>Superb Rehabilitation</h5>
                <img class="p-2" src="../assets/img/wave-divider.png" alt="">
                <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam
                    rem aperiam, eaque</p>
                <button class="btn-margin border border-3 border-white text-white"><span class="contenuto-btn">LEARN
                        MORE</span></button>
            </div>
        </div>
    </div>


    <div class="sfondo-sotto">
        <div class="container-mio text-white">
            <div class="row">
                <h4>Make An Appointment</h4>
                <p>Sed Ut Perspiciatis Unde Omnis Iste Natus Error Sit Voluptatem Accusantium Doloremque Laudantium, Totam
                    Rem Aperiam, Eaque Ipsa Quae Ab Illo Inventore Veritatis Et Quasi Architecto Beatae</p>

            </div>

            <div class="d-flex padding-mio">
                <input class="text-white inpit-mio border border-1 p-2" type="name" placeholder="Name*">
                <div class="mx-2"></div>
                <input class="text-white inpit-mio border border-1 p-2" type="email" placeholder="Email*">
            </div>

            <div class="d-flex ">
                <input class="text-white inpit-mio border border-1 p-2" type="number" placeholder="Phone Number">
                <div class="mx-2"></div>
                <input class="text-white inpit-mio border border-1 p-2" type="date" :placeholder="currentDate"><!--perche pero non me lo mostra nel html , ma nella consol si ?-->
            </div>

            <div class="padding-mio">
                <input class="text-white inpit-mio  border border-1 p-2 input-elp" type="text"
                    placeholder="How can we help?*">
                <button class="btn-cento text-white border border-0 p-2">MAKE AN APPOINTMENT</button>
            </div>
        </div>
    </div>
</template>


<style scoped lang="scss">
.sfondo-strutture {
    background-image: url(../assets/img/paralax-bg-tour-facilities.jpg);
    // height: 80vh;
    text-align: center;
    padding-top: 200px;
    padding-bottom: 200px;
}

.size-grande {
    font-size: 1.3rem;
}

.sfondo-primo {
    background-color: #3BAFBF;
    text-align: center;
}

.sfondo-secondo {
    background-color: #327EC7;
    text-align: center;
}

.sfondo-terzo {
    background-color: #3896C2;
    text-align: center;
}

.distanza {
    padding: 4rem;
}

.btn-margin {
    background-color: transparent;
    // padding-left: 1.4rem;
    // padding-right: 1.4rem;
    padding: 0.5rem 1.4rem;
}

.btn-margin:hover {
    background-color: white;
}

.contenuto-btn:hover {
    color: #3BAFBF;
    // color: black;
    // color: transparent;
}

.sfondo-sotto {
    background-image: url(../assets/img/make-an-appointment.jpg);
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}


.container-mio {
    width: 750px;
    text-align: center;

}

.inpit-mio {
    background-color: transparent;
    width: 100%;
}

.inpit-mio:hover {
    border-color: #3BAFBF;
}

.padding-mio {
    padding: 30px 2px;
}

.btn-cento {
    width: 100%;
    background-color: #3BAFBF;
    margin-top: 20px;
    transition: 1s;
}

.btn-cento:hover {
    background-color: #327EC7;
    transition: 1s;
}

.input-elp {
    height: 130px;
    width: 100%;
    
}
</style>