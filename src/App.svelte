<script>
	import jquery from 'jquery'
	import LeftContainer from "./layout-components/LeftContainer.svelte";
	import MiddleContainer from "./layout-components/MiddleContainer.svelte";
	import RightContainer from "./layout-components/RightContainer.svelte";

	import { onMount } from "svelte";
	const apiURL = "https://supreme-server.herokuapp.com/accounts_summary"

	// let sidebarStatus = false;
	// let sidebarToggle = () => {
	// 	if(state.sidebar === false){
	// 		state.sidebar = true;
	// 		console.log(jquery('main').css())
	// 	}
	// }

</script>

<main>
	<LeftContainer />
	<MiddleContainer />
</main>

<style lang="scss">
	main {
		display: grid;
		grid-template-columns: 20vw 80vw;
		background-color: #B6BEC3;
		width: 99vw;
		height: 99vh;
		border: 0;
		padding: 0;
		margin: 0 auto;
		position: absolute;
	}
</style>