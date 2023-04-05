<template>
    <div class="outside">
        <div class="container left">
            <Category/>
        </div>
        <div class="container right">
            <TheWelcome/>
        </div>
    </div>
</template>

<script>
import Category from "@/components/Category.vue";
import TheWelcome from "@/components/Tutorial.vue";

export default {
    name: "BodyContent",
    components: {TheWelcome, Category},
    props: {
        title: String,
    }
}
</script>

<style scoped>
.outside {
    display: flex;
    padding: 0 30px 0 30px;
    border: 1px solid var(--color-border);
    border-radius: 8px;
}
.left {
    width: 20%;

}
.right {
    width: 80%;
    margin: 3rem 1rem 3rem 1rem;
    display: flex;
    padding-left: 100px;
    flex-wrap: wrap;

}
</style>