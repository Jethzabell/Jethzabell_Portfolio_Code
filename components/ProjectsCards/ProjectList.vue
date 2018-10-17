<template>
     <b-container>     
            <ul class="list-inline" style="padding-top:3rem;">
                    <li class="list-inline-item">
                        <nuxt-link to="/">
                        <h6>About Me</h6>
                        </nuxt-link>
                    </li>
                    <li class="list-inline-item" >
                       <h6> > </h6>
                    </li>
                    <nuxt-link to="/projects">
                    <li class="list-inline-item" >
                       <h6 style="font-weight: bold;">Projects</h6>
                    </li>
                    </nuxt-link>
                </ul>
            <h1>Projects</h1>
        <b-row>
            <b-card-group deck>
                <ProjectPreview
                    title="Pizza Planet"
                    thumbnail="/pizzaPlanet.png"
                    hashtags1="#vue/vuex"
                    hashtags2="#firebase"
                    hashtags3="#auth"
                    uriHeroku="https://github.com/Jethzabell"
                    uriGH="Pizza-DashBoard"
                />
                <ProjectPreview
                    title="Chat App"
                    thumbnail="/chatApp.png"
                    hashtags1="#node"
                    hashtags2="#googleapi"
                    hashtags3="#socket.io"
                    uriHeroku="https://jnodechatapp.herokuapp.com/"
                    uriGH="node-chat-app"
                />
                <ProjectPreview
                    title="Developer Profiles"
                    thumbnail="/devProfiles.png"
                    hashtags1="#bcryptjs"
                    hashtags2="#mongodb "
                    hashtags3="#react"
                    uriHeroku="https://blooming-mountain-77808.herokuapp.com/"
                    uriGH="profiles"
                />
            </b-card-group>
        </b-row>
        <b-row>    
            <b-card-group deck>
                <ProjectPreview
                    title="Munchkin"
                    thumbnail="/munchkin.png"
                    hashtags1="#firebase"
                    hashtags2="#auth "
                    hashtags3="#2014"
                    uriHeroku="https://jethzabell.github.io/MunchkinV2/"
                    uriGH="https://github.com/Jethzabell/MunchkinV2"
                />
                <ProjectPreview
                    title="Computer Graphics"
                    thumbnail="/webGl.png"
                    hashtags1="#WebGL"
                    hashtags2="#linearAlgebra"
                    hashtags3="#2014"
                    uriHeroku="https://jethzabell.github.io/computergraphics/"
                    uriGH="computergraphics"
                />
                <ProjectPreview
                    title="Kitty"
                    thumbnail="/kittyBrowser.png"
                    hashtags1="#react"
                    hashtags2="#node"
                    hashtags3="#smartContracts"
                    uriHeroku="https://kitty-browser.herokuapp.com/"
                    uriGH="kittyBrowser"
                />
            </b-card-group>
        </b-row>
     </b-container>
</template>


<script>
    import ProjectPreview from '@/components/ProjectsCards/ProjectPreview'

    export default {
        components:{
            ProjectPreview
        }
    }
</script>

<style scoped>
    h1{
        padding:3rem 0 0 3rem;
        color:#464d89;
        font-size:  3rem;
        margin-left: -2.5rem;
    }
    
    h6{
       color:#464d89b9; 
    }
</style>
