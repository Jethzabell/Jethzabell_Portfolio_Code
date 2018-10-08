<template>
    <b-card class="txtCenter">
        <div style="box-shadow:20px 20px 50px grey;border-radius:20px;">

            <b-img center class="imageStyle" :src="`${thumbnail}`"/>

            <div style="background:white;border-radius:20px;">

                <h2>{{ title }}</h2>

                <ul class="list-inline">
                    <li class="list-inline-item" data-aos="fade-left" data-aos-delay="300">
                        <a :href="`${uriHeroku}`"><b-img src="/www.png"/></a>
                    </li>
                    <li class="list-inline-item" data-aos="fade-up" data-aos-delay="300">
                        <a :href="`https://github.com/Jethzabell/${uriGH}`"><b-img src="/github.png"/></a>
                    </li>
                    <li class="list-inline-item" data-aos="fade-right" data-aos-delay="300">
                        <a :href="`https://github.com/Jethzabell/${uriGH}/blob/master/package.json`"><b-img src="/npm.png"/></a>
                    </li>
                </ul>

                <b-card-body> 
                    <b-button size="sm" class="buttonSpace" >{{hashtags1}}</b-button>
                    <b-button size="sm" class="buttonSpace" >{{hashtags2}}</b-button>
                    <b-button size="sm" class="buttonSpace" >{{hashtags3}}</b-button>
                </b-card-body> 
                
            </div>
        </div>
    </b-card>
</template>

<script>
export default {
  name: 'ProjectPreview',
  props: {
    title: {
      type: String,
      required: true
    },
    thumbnail: {
      type: String,
      required: true
    },
    hashtags1: {
        type: String,
        required: true
    },
    hashtags2: {
        type: String,
        required: true
    },
    hashtags3: {
        type: String,
        required: true
    },
    uriHeroku:{
        type: String,
        required: true
    },
    uriGH:{
        type: String,
        required: true
    }
  }
}
</script>

<style scoped>
.txtCenter{
    text-align:center;
    border:0;
    border-radius:20px;
    padding: 0 0 2rem 0;
}

.buttonSpace{
    margin-right: .5rem;
    border-radius: 10px;
    padding: 1px 10px 1px 10px;
    background-color: #474747;
}

.imageStyle{
    background:#474747;
    padding:.5rem;
    border-top-right-radius: 20px;
    border-top-left-radius: 20px;
    width:100%;
}

h2{
    padding:1rem 0 1rem 0;
}
</style>