<script>
	let name = '';
</script>

<main>
	<h1>Oli's unicode copy&paste</h1>
	<p>Just enter the unicode below and it will automatically update (Example: E067)</p>
	<p>You can view the very messy source code <a target="_blank" href="https://github.com/oli-version/unicode">here</a>.</p>
	<input bind:value="{name}" class="input" type="text" placeholder="unicode (example: e067)"> <br>
    <iframe src="https://www.fileformat.info/info/unicode/char/{name}/browsertest.htm" width="1000px" height="550" frameborder="0" style="border-radius: 10px;"></iframe>
</main>

<style>

</style>