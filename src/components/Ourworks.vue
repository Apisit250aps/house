<script setup>


import Flicking from "@egjs/vue3-flicking";
import { Perspective, AutoPlay } from "@egjs/flicking-plugins";

const options = {
    circular: true,
    align: 'center',
    horizontal: true,
}
const plugins = [
    new Perspective({ rotate: 0 }),
    new AutoPlay({ duration: 2500, stopOnHover: true }),
]
</script>

<template>
    <section class="container my-3">
        <div class="d-flex">
            <h4 class="text-center">
                "ภายใต้การควบคุมคุณภาพงานโดยวิศกร<br>
                สถาปนิก และช่างผู้ชำนาญการ<br>
                ไว้ใจได้ถึงคุณภาพ และมาตรฐานการก่อสร้าง"
            </h4>
        </div>
        <h2 class="text-center primary-text my-3">Our Works</h2>
        <Flicking ref="works" :options="options" :plugins="plugins">
            <div class="our-works panel">
                <img src="../assets/images/a/ก่อสร้างบ้าน 1.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/ก่อสร้างบ้าน 3.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/ก่อสร้างบ้าน 4 (1).jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูปกันสาด 3.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูปกันสาด.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูปต่อเติม 1.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูปต่อเติม 6.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูปต่อเติม 8.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูปต่อเติม 9.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูประแนง 1.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูประแนง 3.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูประแนง 5.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูประแนง 6.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูประแนง 7.jpg" alt="" class=" img-fluid">
            </div>
            <div class="our-works panel">
                <img src="../assets/images/a/รูประแนง.jpg" alt="" class=" img-fluid">
            </div>
        </Flicking>
    </section>
</template>

<style>
.our-works img {
    object-fit: cover;
    max-width: 300px;

    margin: 0 .25rem;
}
</style>