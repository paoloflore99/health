<script>

import TheFooter from './components/TheFooter.vue'
import TheHeader from './components/TheHeader.vue'
import TheNavbar from './components/TheNavbar.vue'


export default {
    components : {
	TheNavbar,
    TheFooter,
    TheHeader,
	}
};
</script>

<template>
	<TheNavbar></TheNavbar>
	<TheFooter></TheFooter>
	<TheHeader></TheHeader>
</template>

<style scoped>

</style>
