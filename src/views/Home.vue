<template>
    <div class="home">
        <Main />
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Main from '@/components/Main.vue' // @ is an alias to /src

export default defineComponent({
    name: 'Home',
    components: {
        Main,
    },
})
</script>
