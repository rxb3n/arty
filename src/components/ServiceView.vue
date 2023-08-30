<template>
    <div class="serv-container">
        <h3>Service Highlights</h3>

        <div class="service-wrapper">
            <p class="service-description">
                Experience the finest makeup artistry with our exquisite range of services. 
                Transform your look with impeccable precision 
                and sheer elegance—no occasion is too small or big!
            </p>

            <div class="service-list">

                <div class="serv">
                    <p>Bridal MakeUp</p>
                    <p>50 000 CFA</p>
                </div>

                <div id="divider"></div>

                
                <div class="serv">
                    <p>Fashion Events</p>
                    <p>50 000 CFA</p>
                </div>

                <div id="divider"></div>

                
                <div class="serv">
                    <p>Photoshoots</p>
                    <p>50 000 CFA</p>
                </div>

                <div id="divider"></div>

                
                <div class="serv">
                    <p>MakeUp Masterclass</p>
                    <p>50 000 CFA</p>
                </div>

            </div>
        </div>
    </div>
</template>


<style scoped>
.serv-container {
    width: 100%;
    margin: auto;
}

.serv-container h3 {
    font-family: var(--font-secondary);
    font-size: 2.5vw;
    margin-bottom: 5%;
    text-align: center;
}

.service-wrapper {
    font-family: var(--font-primary);
    width: 100%;
    display: flex;
    justify-content: space-around;
}

.service-description {
    width: 25%;
    font-size: calc(.8rem + 1.1vw);
}

.service-list {
    display: flex;
    flex-direction: column;
    width: 35%;
}

.serv {
    font-size: calc(.8rem + 1.3vw);
    display: flex;
    justify-content: space-between;
}

#divider {
    width: 100%;
    border: 1px solid  var(--color-secondary);
    margin-top: 2%; margin-bottom: 2%;
}

.serv p {
    text-align: start;
}



</style>