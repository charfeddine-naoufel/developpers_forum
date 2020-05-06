<template>
    <div >
<h1 class="text-3xl text-blue-500">{{ showTitle }}</h1>
    </div>
</template>

<script>
    export default {
        computed:{
            showTitle(){
                return this.$store.getters.showTitle
            }
        }
    }
</script>
