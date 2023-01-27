<template>
<div class="form-body">
    <signup_form />

</div>
</template>

<script>
import signup_form from './components/SignupForm.vue'

export default {
    name: 'App',

    data() {
        return {
            email: "",
            password: ""
        }

    },
    components: {
        signup_form

    }
}
</script>

<style>
.form-body {
    width: 500px;
    height: 850px;
    background-color: aqua;
    border-radius: 10px;
    align-self: center;

}
</style>
