<template>
    <footer>
        <p>Daniel Gonzalez </p>  
        <a :href="'https://github.com/danielhumgon'" target="_blank"><i class="fab fa-github"></i></a>  
    </footer>
</template>

<script>
    export default {
        name: 'Footer',
    }
</script>

<style scoped>

.fab {
    color: #283747;
}

a {
    color: inherit;
}

i {
    margin-top: 10px;
    font-size: 2.5em;
}

p {
    color: #5C5F58;
}
footer {
    margin-top: 30px;
    text-align: center;
}

</style>