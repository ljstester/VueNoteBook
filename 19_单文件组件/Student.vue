<template>
    <div>
        <h2>学生的名称是：{{ name }}</h2>
        <h2>学生的年龄是：{{ age }}</h2>
    </div>

</template>

<script>
    export default {
        name:School,
        data() {
            return {
                name:'ljs',
                age:30
            }
        },

    }
</script>