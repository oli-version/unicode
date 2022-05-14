<script>
	let url = 'https://minotar.net/helm/';
	let name = '';
</script>

<main>
	<p>Unicode Copy and Paste</p>
	<input bind:value="{name}" class="input" type="text" placeholder="unicode (example: e067)"> <br>
    <iframe src="https://www.fileformat.info/info/unicode/char/{name}/browsertest.htm" width="1000px" height="1000" frameborder="0"></iframe>
</main>

<style>

</style>