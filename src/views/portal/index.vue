<template>
    <div id="portal">
        <nav>
            <logo />
        </nav>
        <div>
            <!-- <h1>portal</h1> -->
            <tab></tab>
            <search></search>
        </div>
    </div>
</template>

<script>
import logo from '../common/logo.vue';
import tab from '../component/tab.vue';
import search from '../component/search.vue';

export default {
    name: '',
    data: () => ({}),
    components: {
        logo,
        tab,
        search
    },
    methods: {}
};
</script>

<style lang="scss" scoped></style>