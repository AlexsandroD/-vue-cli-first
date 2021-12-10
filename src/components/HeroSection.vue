<template>
    <div class="main-container">
        <div class="jumbo"></div>
        <div class="thumbs">
            <ul>
                <li></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name:"HeroSection",
    components:{},
    data(){
        return{
            something:['ciao','bella']
        }
    },
}

</script>


<style scoped>
.jumbo{
    width: 100%;
    background-position: 50%;
    background-image:url("http://www.cheatsheet.com/wp-content/uploads/2015/11/Justice-League.jpg") ;
    background-size: cover;
    height: 500px;
    border-radius: 10px;
}
</style>
