<template>
    <div class="navbar color-white">
        <h1>Logo</h1>
        <nav class="items">
            <ul>
                <li>Home</li>
                <li>Video</li>
                <li>Photos</li>
            </ul>
        </nav>
        <nav>
            <ul>
                <li class="contact">
                    <v-icon color="#fff" x-large>{{Phone}}</v-icon>
                    <label>+99 999 99 99</label>
                </li>
                <li class="contact">
                    <v-icon color="#fff" size="28px" x-large>{{ Email }}</v-icon>
                    <label>nothing@nothing.com</label>
                </li>
                <div class="social">
                    <li><v-icon color="#fff">{{ Facebook }}</v-icon></li>
                    <li><v-icon color="#fff">{{ Google }}</v-icon></li>
                </div>
            </ul>
        </nav>
    </div>
</template>

<style lang="scss" scoped>
    @import '../scss/navbar.scss';
</style>

<script>
import { mdiPhone, mdiEmail, mdiFacebook, mdiGoogle } from '@mdi/js'

export default {
    name: "Navbar",
    data: () => ({
        Phone: mdiPhone,
        Email: mdiEmail,
        Facebook: mdiFacebook,
        Google: mdiGoogle
    })
}
</script>