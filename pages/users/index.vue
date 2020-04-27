<template>
<div>
    <input type="text" v-model="userId">
    <button @click="onloaduser">load user</button>
</div>
    
    
</template>
<script>
export default {
    data(){
        return{
            userId:''
        }
},
methods: {
    onloaduser(){
        this.$router.push('/users/' +this.userId)
        }
        }
}
</script>