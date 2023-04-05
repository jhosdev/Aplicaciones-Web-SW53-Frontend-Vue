<template>
    <div class="item">
        <h3>
            <slot name="heading"></slot>
        </h3>
        <img src="https://icon-library.com/images/black-and-white-folder-icon/black-and-white-folder-icon-5.jpg" alt="img" width="100">
        <div class="details">
            <p>
                Full Description
                <br>
                Category
            </p>
        </div>
    </div>
</template>

<style scoped>
.item {
    border: 1px solid var(--color-border);
    border-radius: 8px;
    box-sizing: border-box;
    width: 30%;
    margin: 1rem 5rem 1rem 1rem;
    align-items: center;
    display: flex;
    flex-direction: column;
}

h3 {
    font-size: 1.2rem;
    font-weight: 500;
    margin-bottom: 0.4rem;
    color: var(--color-heading);
}
</style>
<script setup>
</script>