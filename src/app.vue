<template>
    <div id="test">{{text}}</div>
</template>

<script>
    export default {
        name: "app",
        data() {
            return {
                text: 'abc'
            }
        }
    }
</script>

<style scoped>
#test{
    color: red;
}
</style>