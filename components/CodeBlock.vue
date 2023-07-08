<template>
	<pre class="pre"><code class="language-css">.class {
	property: value
}</code></pre>
</template>

<script setup>
import Prism from 'prismjs'
import '../styles/prism-atom-dark.css'
import 'prismjs/components/prism-css'

onMounted(() => {
	Prism.highlightAll()
})
</script>

<style scoped>
.pre {
	tab-size: 2;
	border-radius: 10px;
}
</style>