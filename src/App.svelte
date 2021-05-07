<script>
	import { Router, Link, Route } from "svelte-routing";
	import Skills from "./views/Skills.svelte";
	import Home from "./views/Home.svelte";
	import Me from "./views/Me.svelte";
</script>

<Router>
	<Route path="/">
		<Home />
	</Route>
	<Route path="/aboutSkills">
		<Skills />
	</Route>
	<Route path="/aboutMe">
		<Me />
	</Route>
</Router>
