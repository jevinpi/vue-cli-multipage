<template>
    <div>
        list
        <button @click="changePage">go to index</button>
    </div>
</template>

<script>
    export default {
        data () {
            return {

            }
        },
        methods: {
            changePage () {
                window.open('/')
            }
        }
    }
    
</script>