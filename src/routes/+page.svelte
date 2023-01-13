<svelte:head>
	<title>Svelte-Exec</title>
</svelte:head>

<header>
	<h1>Svelte-Exec</h1>
</header>
<main>
	<p>A tiny svelte component to emit a `load` event when the component is loaded.</p>
	<p>Installation:</p>
	<pre>npm install svelte-exec</pre>
	<p>Usage:</p>
	<pre>
    <code>
&lt;script&gt;
  import Exec from 'svelte-exec';
&lt;/script&gt;

&lt;Exec on:load=&#x7B;() => &#x7B;
  console.log('Hello World!');
&#x7D;&#x7D; /&gt;
    </code>
  </pre>
</main>

<footer>
	<p>
		<a href="https://github.com/amr3k/svelte-exec" rel="external">GitHub</a>
	</p>
</footer>

<style>
	* {
		box-sizing: border-box;
	}
	h1 {
		font-size: 2em;
		margin: 0;
		text-align: center;
	}
	main {
		max-width: 600px;
		margin: 0 auto;
	}
	pre {
		background: #eee;
		padding: 1em;
		border-radius: 5px;
	}
	pre code {
		display: block;
	}
	footer {
		text-align: center;
	}
</style>
