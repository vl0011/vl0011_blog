<script context="module">
	export const prerender = true;
</script>

<script>
    import CategoryCard from "$lib/category/Card.svelte"
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
    <div class="category-card-list">
        <CategoryCard/>
        <CategoryCard/>
        <CategoryCard/>
        <CategoryCard/>

    </div>

</section>

<style>
    .category-card-list{
        display: flex;
        flex-wrap: wrap;
        margin-top: 20px;
        padding-left: 50px;
        padding-right: 50px;
        margin-left: auto;
        margin-right: auto;
        max-width: calc(1130px + 8vw);

    }
</style>
