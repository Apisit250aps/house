
<script setup>
import Flicking from "@egjs/vue3-flicking";
import { Perspective } from "@egjs/flicking-plugins";

const options = {
    circular: true,
    align: 'center',
    horizontal: true,
}
const plugins = [
    new Perspective({ rotate: 0 }),
    
]

</script>
<template>
    <section class="container my-3">
        <h2 class="text-center primary-text my-3">Our Products</h2>
        <div class="d-none d-lg-block">
            <div class="row row-cols-1 row-cols-lg-4 mx-auto">
                <div class="col our-product">
                    <img src="../assets/images/a/รูประแนง 8.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">ระแนง</p>
                </div>
                <div class="col our-product">
                    <img src="../assets/images/a/กันสาด 5.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">หลังคากันสาด</p>
                </div>
                <div class="col our-product">
                    <img src="../assets/images/a/รูปต่อเติม 3.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">ต่อเติม</p>
                </div>
                <div class="col our-product">
                    <img src="../assets/images/a/ก่อสร้างบ้าน.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">สร้างบ้าน</p>
                </div>
            </div>
        </div>
        <div class="d-block d-lg-none">
            <Flicking ref="products" :options="options" :plugins="plugins" >
                <div class="card-panel panel our-product">
                    <img src="../assets/images/a/รูประแนง 8.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">ระแนง</p>
                </div>
                <div class="card-panel panel our-product">
                    <img src="../assets/images/a/กันสาด 5.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">หลังคากันสาด</p>
                </div>
                <div class="card-panel panel our-product">
                    <img src="../assets/images/a/รูปต่อเติม 3.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">ต่อเติม</p>
                </div>
                <div class="card-panel panel our-product">
                    <img src="../assets/images/a/ก่อสร้างบ้าน.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">สร้างบ้าน</p>
                </div>
            </Flicking>
        </div>
    </section>
</template>


<style>
.panel img {
    max-width: 250px;
    object-fit: cover;
}

.panel {
    margin: 0 .5rem;

}

.caption {
    position: relative;
    z-index: 5;
    top: -30px;
    background-color: var(--secondary);
    color: white;
}
</style>