<template>
<div>

 <h1>this is a id page with id:{{ $route.params.id  }}</h1>

</div>
    
</template>
<script>
export default {
    
    validate(data){
        return /^\d+$/.test(data.params.id)

    },
    
    layout:'users'
}
</script>