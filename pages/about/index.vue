<template>
    <div class="container">
        <Logo></Logo>
        <h1> {{ title }} </h1>
    </div>
</template>
<script>
import Logo from '../../components/Logo'
export default {
    asyncData() {
        return {
            title: 'About Pragra'
        }
    }
}
</script>