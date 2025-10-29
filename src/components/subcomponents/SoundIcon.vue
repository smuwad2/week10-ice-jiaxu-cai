<script>
    export default { 
        data() {
            return {
                soundEmojis: ['🔇', '🔈', '🔉', '🔊']
            }
        },
        // TODO: add code to define a necessary prop
        props:{
            level: Number // defined in <v-model="soundLevel"> 
        }
    }
</script>

<template>
    <!-- TODO: add your template code here. Use span element. --> 
     {{ soundEmojis[level]}}
    
</template>