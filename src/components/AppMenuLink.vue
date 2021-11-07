<script lang="ts">
import defineComponent from 'vue'
export default defineComponent({
    name: "AppMenuLink",
    props: {
        href: {
            type: String,
            required: true,
            default: "/"
        }
    },
    methods: {
        onclickMenuClose() {
            console.log(">>onclickMenuClose")
        }
    }
})
</script>
<template>
    <router-link :to="href" class="AppMenu__link">
        <span @click="onclickMenuClose">
            <slot />
        </span>
    </router-link>
</template>