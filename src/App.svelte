<script>
  import NavBar from "~/components/NavBar.svelte";
  import Footer from "~/components/Footer.svelte";
  import routes from "~/routes/index.js";
  import Router, {location} from "svelte-spa-router";
  import {fade} from "svelte/transition";
</script>

<div id="wrapper" class="clearfix">
  <NavBar />
{#key location}
  <div in:fade>
   <Router {routes} restoreScrollState={true} />
  </div>
{/key}
  <Footer />
</div>
<!-- #wrapper end -->
<div id="gotoTop" class="icon-angle-up" />

<style lang="scss">
</style>
