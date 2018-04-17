<template>
    <div class="{{name | kebabCase}}">
        <h1>{{name | kebabCase}} Component</h1>
    </div>
</template>

<script>
export default {
    name: '{{name | camelCase}}',
    props: {},
    data() {
        return {

        }
    },
    computed: {

    },
    mounted() {

    },
    methods: {

    }
}
</script>

<style lang="{{ filesType.style }}" scoped>
.{{name | kebabCase}} {

}
</style>
