<template>
    <div>
        <p>Lamp status : {{ status }} </p>
        <button @click="openLamp">Change Lamp Status</button>
        <hr>
    </div>
</template>

<script>
    export default {
        data: function(){
            return{
                status: "Close"
            }
        },
        methods: {
            openLamp(){
                this.status = "Open"
            }
        },
    }
</script>

<style>
    
</style>