<template>
    <button class="AppHeader__trigger" @click="onClickMenuToggle">
        <span class="_visuallyHidden">メニューを開く</span>
        <span class="AppHeader__triggerBar -top"></span>
        <span class="AppHeader__triggerBar -center"></span>
        <span class="AppHeader__triggerBar -bottom"></span>
    </button>
</template>

<script lang="ts">
import { defineComponent} from 'vue'
export default defineComponent({
    name: "AppMenuTrigger",
    methods: {
        onClickMenuToggle() {
            console.log(">>onClickMenuToggle")
        }
    }
})
</script>