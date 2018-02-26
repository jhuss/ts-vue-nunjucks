<template>
    <div>
        <div class="greeting">Hello {{name}}</div>
    </div>
</template>

<script lang="ts">
    import Vue from 'vue'
    import Component from 'vue-class-component'

    @Component({
        props: {
            name: String
        }
    })
    export default class HelloDecorator extends Vue {
    }
</script>

<style>
    .greeting {
        font-size: 20px;
    }
</style>
