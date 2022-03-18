<template>
    <div class="com-text-tip">
        <div class="com-selector-tip">
            {{topTip}}
        </div>
        <div class="com-text">{{textTip}}</div>
        <div class="com-selector-bottom">
            {{bottomTip}}
        </div>
    </div>
</template>

<script>
    export default {
        name: "TextTip",
        props: {
            textTip: String,
        },
        data() {
            return {
                topTip: 'text',
                bottomTip: 'This is a text-tip.'
            }
        },
        methods: {

        }
    }
</script>

<style scoped>
.com-text {
    text-align: left;
}
</style>