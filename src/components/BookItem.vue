<template>
    <ul>
        <li v-for="book in books">{{book.title}}: {{book.author}}</li>
    </ul>
</template>

<script>
    export default {
        name: 'BookItem',
        props: ['book']
    }
</script>

<style></style>