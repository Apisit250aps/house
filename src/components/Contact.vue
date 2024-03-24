<template>
    <section class="container my-5">
        <div class="row row-cols-1 row-cols-lg-2 mx-auto">
            <div class="col">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d3872.663889135458!2d100.66149107591167!3d13.919027493398222!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1zMjg4IOC4i-C4reC4oiDguKrguLLguKLguYTguKvguKEgMTUvMTI4OC8zMSDguJbguJnguJnguKrguLLguKLguYTguKvguKEg4LmB4LiC4Lin4LiH4Liq4Liy4Lii4LmE4Lir4LihIOC5gOC4guC4leC4quC4suC4ouC5hOC4q-C4oSDguIHguKPguLjguIfguYDguJfguJ7guKHguKvguLLguJnguITguKMgMTAyMjA!5e0!3m2!1sth!2sth!4v1711287340814!5m2!1sth!2sth"
                    style="border:0;" allowfullscreen="" loading="lazy" class="w-100 h-100" 
                    referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
            <div class="col">
                <div class="d-flex align-items-center w-100 flex-column">
                    <img src="../assets/images/contact/logo.png" alt="" srcset="" id="logo-contact">
                </div>
                <h4 class="text-center">
                    288/31 ถนนสายไหม แขวงสายไหม เขตสายไหม กรุงเทพมหานคร 10220
                </h4>
                <br>
                <p class="text-center">(Avenue ตลาดวงศกร)</p>
                <p class="text-center">เปิดทำการ จันทร์ - เสาร์ 8.00-18.00 น.</p>
                <hr>
                <p class="text-center">
                    Tel : 095-912-3566 (งานติดตั้ง), 099-293-5369 (งานขายวัสดุ)
                    <br>
                    E-mail : Sirakorn.nu.awe@gmail.com
                    <br>
                </p>
            </div>
        </div>
    </section>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent(
    {
        name:"contact",

    }
)
</script>

<style>
#logo-contact {
max-width: 200px
}
</style>