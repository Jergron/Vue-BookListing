<template>
    <ul>
        <li>{{book.title}}: {{author.title}}</li>
    </ul>
</template>
<script>
export default {
    name: 'BookItem',
    props: ['book']
}
</script>
<style scoped>
    li {
        display: block;
        margin: 0 10px;
    }
</style>