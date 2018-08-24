
<template>
    <div>
        <slot>默认值:没有slot name</slot>
        <slot name='firstSlot'><p>默认值:firstSlot</p></slot>
        <slot name='secondSlot'><p>默认值:secondSlot</p></slot>
        <slot name='thirdSlot'><p>默认值:thirdSlot</p></slot>
    </div>
</template>
