<script lang="ts" setup>
defineProps({
    title: String,
    imgUrl: String,
    price: Number,
    isFav: Boolean,
    onClickfav: Function,
    isAdd: Boolean,
    onClickAdd: Function,

})


</script>



<template>
    <div class="">
        <div class="card">
        <img @click="onClickFav" :src="isFav ? '/like-2.svg' : '/like-1.svg'" alt="like" class="like">
        <img :src="imgUrl" alt="sneak" >
        <p class="sneak-name">{{ title }}</p>

        <div class="price">
            <div class="price-text">
                <span class="price-name">Цена:</span>
                <span class="price-num">{{ price }} руб.</span>
            </div>
            <img @click="onClickAdd" :src="isAdd ? '/checked.svg' : '/plus.svg'  " alt="plus">
        </div>
    </div>
    </div>
</template>