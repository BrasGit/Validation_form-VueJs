<template>
    <div>
        <h4>Car name: Ford</h4>
        <h5>Car year: 2019</h5>

        <div class="scroll"></div>

        <h6 id="scroll" >Hello from the bottom</h6>
    </div>
</template>

<script>
export default {
    beforeRouteEnter(to, from, next){
                        console.log('beforeRouteEnter')
                        next(true)
                    }
}
</script>

<style scoped>
.scroll{
    width:100px;
    height: 1000px;
    background: #ccc;
}
</style>