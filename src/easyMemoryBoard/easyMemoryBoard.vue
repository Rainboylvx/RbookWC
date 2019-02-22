<style lang="scss">
@import './easyMemoryBoard.scss'
</style>
<template>
<div class="easyMemoryBoard">
    <div class="title">
        <slot name="title"></slot>
    </div>
    <ul :style="{'font-size':size+'rem'}">
        <slot></slot>
    </ul>
</div>
</template>
<script>
export default {
    props:['size'],
    data() {
        return {
        }
    }
}
</script>
