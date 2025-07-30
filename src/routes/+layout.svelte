

<script lang="ts">
	let { children } = $props();
</script>
<div style="text-align: center;">
  <nav>
	<a href="/"><button>Hello</button></a>
	<a href="/about"><button>About Me</button></a>
    <a href="/Projects"><button>My Projects</button></a>
  </nav>
</div>

{@render children()}