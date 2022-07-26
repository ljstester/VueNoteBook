<template>
    <div>
        <School/>
        <Student/>
    </div>

</template>

<script>
    import SchoolVue from '../19_单文件组件 copy/School.vue'
    import StudentVue from './Student.vue'
    
    export default {
        name:App,
        components:{School,Student}
    }
</script>