<script>

import TheFooter from './components/TheFooter.vue'
import TheHeader from './components/TheHeader.vue'
import TheNavbar from './components/TheNavbar.vue'
import TheDoctor from './components/TheDoctor.vue'
import TheService from './components/TheService.vue'


export default {
    components : {
	TheNavbar,
    TheFooter,
	TheDoctor,
    TheHeader,
	TheService,
	}
};
</script>

<template>

	<TheNavbar></TheNavbar>
	<TheFooter></TheFooter>
	<TheDoctor></TheDoctor>
	<TheService></TheService>
	<TheHeader></TheHeader>

</template>

<style scoped>

</style>
