<script lang="ts" setup>
    import drawerHead from './drawerHead.vue'
    import cartListItem from './cartListItem.vue'
</script>


<template>
    <div class="drawer"></div>
    <div class="cart-menu">
        <drawer-head/>
        <cartListItem/>
        <div class="flex flex-col gap-4 mt-7">
            <div class="flex gap-2">
                <span>Итого:</span>
                <div class="flex-1 border-b border-dashed"></div>
                <b>12990 руб.</b>
            </div>
            <div class="flex gap-2">
                <span>Налог 5%</span>
                <div class="flex-1 border-b border-dashed"></div>
                <b>900 руб.</b>
            </div>
        </div>
        <button disabled="" class="mt-4 transition bg-lime-500 w-full cursor-pointer rounded-xl py-3 text-white disabled:bg-slate-400 hover:bg-lime-600 active:bg-lime-700">
            Оформить заказ
        </button>   
    </div>
</template>