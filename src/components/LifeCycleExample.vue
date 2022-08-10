<template>
    <div>

    </div>
</template>

<script>
    export default {
        beforeCreate () {
            console.log(`currently in before create`);
        },

        created () {
            console.log(`currently in created`);
        },

        beforeMount () {
            console.log(`currently in before mount`);
        },

        mounted () {
            console.log(`currently in mounted`);
        },
    }
</script>

<style scoped>

</style>