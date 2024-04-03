<template lang="">
    <div>
        {{ $route.params.name }} [name ]
    </div>
</template>


<script setup lang="ts">

    const route = useRoute()
    console.log(route.params.name, route)

</script>


<style lang="">
    
</style>