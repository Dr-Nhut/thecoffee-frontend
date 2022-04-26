<script>
export default {
    props: {
        coffee: { type: Object, required: true },
    },
};
</script>

<template>
    <div>
        <div class="p-1">
            <strong>{{ coffee.name }}</strong>
            
        </div>
        <div class="p-1">
            <i>{{ coffee.price }}</i>
        </div>
        <div class="p-1">
            <p>{{ coffee.description }}</p>
        </div>
        <div class="p-1">
            Số lượng:
        </div>
    </div>

    <div>
        <button id="btn-close" @click="closeProduct">
                    <i class="fa-solid fa-circle-xmark"></i> 
        </button>

        <button id="btn-close" @click="gotoCart">
                    <i class="fa-solid fa-cart-plus"></i> Thêm vào giỏ hàng
        </button>
    </div>
</template>

<style>
    #btn-close{
        border: none;
        border-radius: 5px;
        background-color: #fff;
        color: black;
    }
    #btn-close:hover {
        color: red;
    }
</style>
