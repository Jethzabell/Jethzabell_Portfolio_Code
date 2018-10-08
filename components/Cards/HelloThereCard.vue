<template>
    <section id="hello-there">
        <b-card overlay
            img-alt="Card Image"
            text-variant="white"
            sub-title="HELLO THERE!"
            class="test">

            <p class="card-text" data-aos="fade-left" data-aos-delay="500" >
            I'm a young professional, making and learning things on the web.
            </p>
        </b-card>
    </section>
</template>

<style scoped>

@media (min-width: 768px) {
  .test p {
    font-size: 2rem;
  }
}

.test{
  height: 100px;
  position: relative;
  padding: 20px;
  margin: 4%;
  border:0px;
}

.card-text{
    padding-top:.5rem;
  color:#464d89;
}

.wOutShadow{
    box-shadow:20px 20px 50px grey;
    margin-bottom: 3rem;
}
.theItemSpace{
    margin-right:3rem;
}
.buttonMargin{
    margin-left:1rem;
}
</style>
