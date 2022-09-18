<script>
    import Home from "./lib/pages/Home.svelte";
    import SignIn from "./lib/pages/SignIn.svelte";
    import { Router, Route } from "svelte-navigator";

</script>

<Router>
	<div>
        <Route path="/">
            <Home/>
        </Route>
        <Route path="/sign-in">
            <SignIn/>
        </Route>
    </div>
</Router>