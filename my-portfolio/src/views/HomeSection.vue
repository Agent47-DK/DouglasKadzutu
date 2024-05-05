<template>
    <div class="page-container">
        <div class="intro">Welcome</div>
        <div class="title">Douglas Kadzutu</div>
        <div class="summary">Who Am I</div>
        <div class="socials">Social Media Links</div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: "HomeSection",
    // components: { to import},
    // props: {},
    setup() {
        const handleButtonClick = () => {
        console.log("menu clicked");
        };

        return {
        handleButtonClick,
        };
    },
})
</script>

<style lang="scss" scoped>
.page-container {
    width: 100%;
}
</style>