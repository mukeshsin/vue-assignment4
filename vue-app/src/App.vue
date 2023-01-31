<template>
<div class="form-body">
    <signup_form />
</div>
</template>

<script>
import signup_form from "./components/SignupForm.vue";

export default {
    name: "App",

    data() {
        return {};
    },
    components: {
        signup_form,
    },
};
</script>

<style>
.form-body {
    height: 100%;
    width: 50%;
    margin-left: 30px;
    padding-left: 30px;
    background-color: white;
    margin-top: 1.5%;
    border-radius: 10px;
    color: #bec2c4;
    margin-bottom: 30px;
    border: 15px #ededed solid;
}
</style>
