<template>
    <div id="app">
        <h3>测试slot</h3>
        <rx-slot-sub>
            <p>NoSlotName:我没有slot name</p>
            <p slot='firstSlot1'>FirstSlot1Name:我有slot name,但是这个name在子组件不存在</p>
            <p slot='firstSlot'>FirstSlotName:我是first slot,我将替换子组件的first slot</p>
            <rx-slot-replace inputMsg='NoSlotName:我是一个自定义组件: 我没有slot name'></rx-slot-replace>
            <rx-slot-replace inputMsg='SecondSlotName:我是一个自定义组件: 我的slot name是secondSlot, 我将替换子组件的name是secondSlot' slot='secondSlot'></rx-slot-replace>
            <p>NoSlotName:我也没有slot name</p>
            <rx-slot-replace inputMsg='SecondSlotName:我是一个自定义组件: 我的slot name也是secondSlot, 我和上面的那个name也是secondSlot将组合在一起,然后替换子组件的name是secondSlot' slot='secondSlot'></rx-slot-replace>
            <rx-slot-replace inputMsg='FirstSlotName:我是一个自定义组件: 我的slot name是firstSlot, 我将替换子组件的name是firstSlot' slot='firstSlot'></rx-slot-replace>
        </rx-slot-sub>
    </div>
</template>

<script>
    import RxSlotSub from '@/components/slot/RxSlotSub'
    import RxSlotReplace from '@/components/slot/RxSlotReplace'
    export default {
        data () {
            return {

            }
        },
        components: {
            RxSlotSub,
            RxSlotReplace
        }
    }
</script>

<style>

</style>
