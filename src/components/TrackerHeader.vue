<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<script>
    export default {
        name:'TrackerHeader',
        //  You can define props as an array or an object
        // props: ['title']
      
        // To add a default value:
        // props: {
        //     title: {
        //         type: String,
        //         default: 'Hello World',
        //     }
        // }

          props: {
            title: String
        }
    }
</script>

// Scoped = these styles are only for this component
<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }

</style>