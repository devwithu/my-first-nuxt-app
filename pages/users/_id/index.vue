<template>
  
    <h1>The single user view {{ $route.params.id}}</h1>
  
</template>

<script>
export default {
    validate(data) {
        return /^\d+$/.test(data.params.id)
    }
}
</script>