<script>
	import AlertComponent from '../components/AlertComponent.svelte';
	import Employement from '../components/Employement.svelte';
</script>

<div class="grid grid-cols-12 w-full">
	<div class="col-span-3 bg-red-400 h-screen">
		<AlertComponent />
		<Employement />
	</div>
	<div class="col-span-9 bg-blue-400" />
</div>
