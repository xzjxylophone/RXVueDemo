
<template>
    <div id="app">
        <rx-slot>
        </rx-slot>
    </div>
</template>

<script>
// https://blog.csdn.net/kingov/article/details/78293384
    import RxSlot from '@/components/slot/RxSlot'
    export default {
        data () {
            return {

            }
        },
        components: {
            RxSlot
        }
    }
</script>

<style>

</style>
