<script>

import TheFooter from './components/TheFooter.vue'
import TheHeader from './components/TheHeader.vue'
import TheNavbar from './components/TheNavbar.vue'
import TheDoctor from './components/TheDoctor.vue'


export default {
    components : {
	TheNavbar,
    TheFooter,
	TheDoctor,
    TheHeader,
	}
};
</script>

<template>
	<TheNavbar></TheNavbar>
	<TheFooter></TheFooter>
	<TheDoctor></TheDoctor>
	<TheHeader></TheHeader>
</template>

<style scoped>

</style>
