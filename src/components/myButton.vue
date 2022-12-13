<template>
    <div>
        <h2>我爱你，中国</h2>
        <button @click="count++">今天爱了{{count}}次</button>
    </div>
</template>

<script>
    export default {
        name:'',
        data(){
            return{
                count:0
            }
        }
    }
</script>
<style>
    h2{
        color: hotpink;
        font-size: 35px;
    }
</style>