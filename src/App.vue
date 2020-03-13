<template>
    <button type="button" @click="captcha()">点击我</button>
</template>

<script>
import Clickcaptcha from "@/components/index.js";

export default {
    methods: {
        captcha() {
            Clickcaptcha({
                src: "http://localhost/clicaptcha-server/clicaptcha.php",
                callback: () => {
                    alert("yes");
                }
            });
        }
    }
};
</script>