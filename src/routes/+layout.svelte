
<script lang="ts">
	let { children } = $props();
</script>
<div style="text-align: center;">
  <nav>
	<a href="/">Hello</a>
	<a href="/about">About Me</a>
  <a href="/Projects">My Projects</a>
  </nav>
  

</div>

{@render children()}
<style lang="scss">
  a:link, a:visited {
  background-color: #000000;
  color: white;
  padding: 14px 194px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}


  :global(body) {
		background-color: #903390;
		margin: 0;
	}
  :global(p) {
    text-align: center;
  }
  :global(h1) {
    text-align: center;
  }
  :global(h2) {
    text-align: center;
  }
  :global(h3) {
    text-align: center;
  }
  :global(h4) {
    text-align: center;
  }
  :global(h5) {
    text-align: center;
  }
  :global(h6) {
    text-align: center;
  }
  :global(div) {
    text-align: center;
    
  }

</style>
