<template>
    <div id="tab">
        <h2>.</h2>
        <h1>html</h1>
        <tabHtml :tabMessage="value" @ToTab="transform"></tabHtml>
    </div>
</template>

<script>
import tabHtml from '../component/tabHtml.vue';

export default {
    name: 'tab',
    data() {
        return {
            value: '我是来自父组件的消息'
        };
    },
    components: {
        tabHtml
    },
    methods: {
        transform(msg) {
            alert(msg);
        }
    }
};
</script>

