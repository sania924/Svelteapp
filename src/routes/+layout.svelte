<script>
    import Reuse from "../lib/reuse.svelte";
    
</script>
<header>
  <p>header</p>
    <Reuse />
</header>
 
<main>
  <p>body</p>

   <slot></slot> 
</main>

<footer>
  <p>footer</p> 
</footer>