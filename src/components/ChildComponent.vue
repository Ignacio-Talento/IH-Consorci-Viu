<script setup>
defineProps({
    message: String
});
</script>

<template>
    <section class="child">
        <h3>Child Component</h3>
        <h4>{{ message }}</h4>

    </section>
</template>

<style>
.child {
    border: 2px dotted blue;
    padding: 10px;
    margin: 10px;
}
</style>