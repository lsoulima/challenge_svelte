<script>
  import Login from "./Login.svelte";
  import Register from "./Register.svelte";
</script>

<style>
  main {
    display: flex;
    align-items: center;
	flex-direction: column;
	font-family: sofia-pro, sans-serif;
	text-align: center;
  }

  h1 {
    font-family: gothic-open-shaded, sans-serif;
    font-weight: 400;
    font-style: normal;
  }
</style>

<main>

  <h1>Sign In</h1>
  <Login />
  <h1>Sign Up</h1>
  <Register />
</main>
