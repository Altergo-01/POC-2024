<script>
 
export default {
    props: ['buttonName', 'idA'],

    data() {
        return {
        
        };
    },
    methods: {

        
    },

};
</script>

<template> 

    <a :href="idA" class="button-wrapper" >

        <span>{{ buttonName }}</span>

    </a>

</template>

<style scoped>

a{
    border-radius: 50px;
    background-color: var(--color-mr-N);
    border: 2px solid var(--color-mr-N);
    width: 60%;
    height: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: 0.300s;
    color: var(--color-cream-N);
    text-decoration: none;
}

a:hover {
    border: 2px solid var(--color-mr-N);
    background-color: var(--color-cream-N);
    transition: 0.300s;
    color: var(--color-mr-N);
}

</style>