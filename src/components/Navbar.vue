<template>
    <nav class="navbar navbar-light navbar-expand-lg">
        <div class="container">
            <a class="d-flex align-items-center nav-link" href="/">
                <img src="/src/assets/images/contact/logo.png" alt="" srcset="" class="img-fluid d-block" id="logo">
                <span class="fs-2 fw-normal d-none d-lg-inline-flex">ช.แทค รับติดตั้งระแนงกันสาด</span>
                <span class="fs-4 fw-normal">ช.แทค รับติดตั้งระแนงกันสาด</span>
            </a>
        </div>
    </nav>
</template>
<script>
import { defineComponent } from 'vue';

export default defineComponent(
{
    name:"Navbar"
}
)
</script>

<style>
#logo {
    max-width: 80px;
}
.navbar {
    background-color: var(--light);
}

.navbar-brand, .offcanvas-title {
    color: var(--primary);
}

.navbar-brand:hover {
    color: #006eff;
}

.nav-link {
    color: #004aad;
}

.nav-link:hover {
    color: #006eff;
}
</style>