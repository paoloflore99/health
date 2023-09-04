<script>

import TheFooter from './components/TheFooter.vue'
import TheHeader from './components/TheHeader.vue'
import TheNavbar from './components/TheNavbar.vue'
import TheDoctor from './components/TheDoctor.vue'
import TheService from './components/TheService.vue'
import TheStrutture from './components/theStrutture.vue'


export default {
    components : {
	TheNavbar,
    TheFooter,
	TheDoctor,
    TheHeader,
	TheStrutture,
	TheService,
	}
};
</script>

<template>

	<TheNavbar></TheNavbar>
	<TheFooter></TheFooter>
	<TheDoctor></TheDoctor>
	<TheService></TheService>
	<TheStrutture></TheStrutture>
	<TheHeader></TheHeader>

</template>

<style scoped>

</style>


