<template>
<div>
        <easy-memory-board size="2">
            <p slot="title">中文标题</p>
            <li>口决1</li>
            <li>口决2</li>
        </easy-memory-board>
</div>
</template>
<script>
import easyMemoryBoard from './easyMemoryBoard.vue'
export default {
    components:{
        easyMemoryBoard
    },
    data() {
        return {
        }
    }
}
</script>
