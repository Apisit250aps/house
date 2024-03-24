<template>
    <section class="container my-3">
        <h2 class="text-center primary-text my-3">Our Products</h2>
        <div class="d-none d-lg-block">
            <div class="row row-cols-4 mx-auto">
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
            <Flicking :options="{ circular: true }" :plugins="plugins">
                <div class="panel">
                    <img src="../assets/images/a/รูประแนง 8.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">ระแนง</p>
                </div>
                <div class="panel">
                    <img src="../assets/images/a/กันสาด 5.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">หลังคากันสาด</p>
                </div>
                <div class="panel">
                    <img src="../assets/images/a/รูปต่อเติม 3.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">ต่อเติม</p>
                </div>
                <div class="panel">
                    <img src="../assets/images/a/ก่อสร้างบ้าน.jpg" alt="" class="img-fluid">
                    <p class="text-center caption fs-3">สร้างบ้าน</p>
                </div>
            </Flicking>
        </div>
    </section>
</template>

<script>
import { defineComponent } from 'vue';
import Flicking from "@egjs/vue3-flicking";
import { Perspective,AutoPlay } from "@egjs/flicking-plugins";

export default defineComponent(
    {
        name:"Ourproducts",
        components:{
            Flicking: Flicking
        },
        data(){
            return {
                plugins: [
                new Perspective({ rotate: -1, scale: 2, perspective: 600 }),
                new AutoPlay({ duration: 2000, direction: "NEXT", stopOnHover: false })
                ]
            }
        }
    }
)

</script>

<style>
.panel img {
    max-width: 300px;
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