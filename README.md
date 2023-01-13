# Svelte-Exec

<div align=center>
  <img src="./static/favicon.png">
</div>

A tiny svelte component to emit a `load` event when the component is loaded.

## Installation

- npm

```bash
npm install svelte-exec
```

## Usage

```js
<script>
	import Exec from 'svelte-exec';
</script>

<Exec on:load={() => {
  console.log('Hello World!');
}} />
```

In this example, when the component is loaded it will emit a load event, which can be listened to using the on:load syntax in the parent component.

## Events

- `load`: emitted when the component is loaded.
