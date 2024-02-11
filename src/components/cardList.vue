<script lang="ts" setup>
import card from './card.vue'


const onClickAdd = () =>{
    alert('Добавить')
}
</script>


<template>
    <div class="grid-sneak">
        <card img-url="/sneakers/sneakers-1.jpg" 
        title="Мужские кроссовки Nike Blazer Mid Suede" 
        :price="5990"
        /> 

    </div>
</template>