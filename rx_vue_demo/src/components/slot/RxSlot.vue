<template>
    <div id="app">
        <rx-slot-sub>
            <span>我是父组件里的文字，但是我要被放到子组件里</span>
        </rx-slot-sub>
    </div>
</template>

<script>
    import RxSlotSub from '@/components/slot/RxSlotSub'
    export default {
        data () {
            return {

            }
        },
        components: {
            RxSlotSub
        }
    }
</script>

<style>

</style>
