<script lang="ts" setup>
    console.log('loaded')
</script>

<template>
    <section class="grid" style="min-height: 100vh;">
        <LayoutSidebar />
        <div class="">
            <slot></slot>
        </div>
    </section>
</template>

<style scoped>
    .grid {
        display: grid;
        grid-template-columns: 1fr 6fr;
    }
</style>