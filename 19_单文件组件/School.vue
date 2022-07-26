<template>
    <div class="demo">
        <h2>学校的名称是：{{ name }}</h2>
        <h2>学校的地址是：{{ adress }}</h2>
        <button @click="click_button">这是一个点击按钮</button>
    </div>

</template>

<script>
    export default {
        name:School,
        data() {
            return {
                name:'hljwgyxy',
                adress:'hrb'
            }
        },
        methods: {
            'click_button'(){
                alert('一个点击的方法')
            }
        },

    }
</script>

<style>
    .demo {
        color: red;
    }
</style>