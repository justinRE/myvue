<template>
    <div class="additional">
        <h1>This is the updated information</h1>
        <h2> This is a secret key: {{ Key }}</h2>
    </div>
</template>

<script>
export default{
    name:'AdditionalView',
computed:{
    Key(){
        return process.env.VUE_APP_KEY
    }
}
}
</script>