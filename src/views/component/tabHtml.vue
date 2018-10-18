<template>
    <div id="tabHtml">
        <span>{{ tabMessage }}</span>
        <button @click="toTab">点击向tab传值</button>
    </div>
</template>

<script>
export default {
    props: ['tabMessage'],
    name: 'tabHtml',
    methods: {
        toTab() {
            this.$emit('ToTab', '我是HTML向Tab组件传递的');
        }
    }
};
</script>
