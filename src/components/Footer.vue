<template>
    <footer class="">
        <section class="container py-5 text-white">
            <div class="row row-cols-1 row-cols-lg-3 mx-auto">
                <div class="col d-flex align-items-center justify-content-center flex-column my-2">
                    <img src="../assets/images/a/โลโก้.jpg" alt="" class="img-fluid rounded-3" id="logo-footer">
                </div>
                <div class="col d-flex align-items-center justify-content-center flex-column my-2">
                    <h4>บริการ</h4>
                    <ul style="list-style: none;">
                        <li>ติดตั้งระแนง</li>
                        <li>ติดตั้งกันสาด</li>
                        <li>ต่อเติมบ้าน</li>
                        <li>สร้างบ้าน</li>
                    </ul>
                </div>
                <div class="col d-flex align-items-center justify-content-center flex-column my-2">

                </div>
            </div>
        </section>
    </footer>
</template>
<script>
import { defineComponent } from 'vue';
export default defineComponent(
    {
        name:"footer"
    }
)
</script>

<style>
footer {
    background-color: #004aad;
}
#logo-footer {
    max-width: 200px;
}
</style>