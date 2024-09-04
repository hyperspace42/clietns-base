<script>
	import '../app.css';
	import Header from '@components/header/Header.svelte';
    import ClientField from '@components/field/ClientField.svelte';
</script>

<div class="container ml-a mr-a">
	<Header />
    <div class="flex flex-col gap-4">
        <ClientField />
        <ClientField />
        <ClientField />
        <ClientField />
        <ClientField />
        <ClientField />
    </div>
</div>

<style>
	.container {
		max-width: 70%;
	}
</style>
