<template>
    <div class="about-container">
        <h3>Unleashing your Beauty</h3>
        <p>
            Welcome to Arty MakeUp. 
            You’re in the hands of Abidjan’s finest makeup artists! 
            Whether it's a natural look or a bold statement, 
            our talented team is ready to take you to new heights of glamour.
        </p>
    </div>

</template>

<style scoped>
.about-container {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 10%;
    width: 60%;
    margin: auto;
}

.about-container h3 {
    font-family: var(--font-secondary);
    margin: auto;
    font-weight: 700;
    font-size: calc(.59rem + 2.5vw);
    margin-right: 20%;
}

.about-container p {
    font-family: var(--font-primary);
    margin: auto;
    font-size: calc(.59rem + 1.1vw);
}

@media screen and (max-width: 1000px) {
    .about-container {
        display: flex;
        flex-direction: column;
    }
}


</style>