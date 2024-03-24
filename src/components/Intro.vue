<template>
    <section class="container">
        <div class="row mx-auto">
            <div class="col-12 col-lg-6">
                <div id="service-carousel" class="carousel slide">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#service-carousel" data-bs-slide-to="0" class="active"
                            aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#service-carousel" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#service-carousel" data-bs-slide-to="2"
                            aria-label="Slide 3"></button>
                        <button type="button" data-bs-target="#service-carousel" data-bs-slide-to="3"
                            aria-label="Slide 4"></button>
                    </div>
                    <div class="carousel-inner rounded-2" data-bs-interval="10000">
                        <div class="carousel-item active">
                            <img src="../assets/images/services/service1.jpg" class="d-block img-fluid w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="../assets/images/services/service2.jpg" class="d-block img-fluid w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="../assets/images/services/service3.jpg" class="d-block img-fluid w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="../assets/images/services/service4.jpg" class="d-block img-fluid w-100" alt="...">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#service-carousel"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#service-carousel"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
            <div class="col-12 col-lg-6 d-flex flex-column align-items-center justify-content-center">
                <div class="py-3">
                    <p class="text-center fs-4">
                        "ด้วยประสบการณ์งานก่อสร้าง รับเหมาต่อเติมกว่า 10 ปี<br>
                        เรามุ่งมั่น ที่จะสร้างความพึงพอใจสูงสุดต่อลูกค้า<br>
                        ด้วยการมอบสินค้าคุณภาพเยี่ยม และบริการที่เป็นเลิศ<br>
                        สะดวก รวดเร็วทันใจโดยการปรับปรุงพัฒนาอย่างต่อเนื่อง<br>
                        และรับผิดชอบต่อสังคม"
                    </p>
                </div>
                <div class="">
                    <hr>
                    <h3 class="text-center primary-text">สนใจติดต่อ</h3>
                    <img src="../assets/images/contact/line.jpg" alt="" srcset="" class="img-fluid img-thumbnail"
                        id="line">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent(
    {
        name:"Intro",
        
    }
)

</script>

<style>
#line {
    max-width: 200px;
    margin: 0 2.5rem;
}
</style>