<script>
    import Reuse from "../lib/reuse.svelte";
    import '../styles/global.css'
    let title="new title"
    const updateTitle= ()=>{
        title="update title"
    }
</script>
<svelte:head>
    <title>home</title>
</svelte:head>
<div class="page">
<Reuse></Reuse>
<h1>{title}</h1>
<button on:click={updateTitle}>button</button>
<a href="/about">About</a>
<a href="/service">service</a>

</div>
