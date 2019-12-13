# Introduction to VueJS

Prepared by:  
\- Harikrushan V. Adiecha  
<small>Senior Software Engineer @ Improwised Technologies Pvt. Ltd.</small>



# What is vue

VueJS is a prgrassive framework for building user interface.
Vue is perfectly capable for building Single Page Application. 



# Evan you
#### Founder of Vue

Currently he is an independent Software developer and the creator of open source javascript framework vue.js. Previously he was working as creative technologiest @ google.

#### Releases

v0.10 - Initial release on 2014  
v1.0 - on 2015  
v2.0 - on 2016  



# Why Vue
- Easy to learn
- Light weight 
- Reactivity (two way data binding)
- Reusable component
- Virtual dom



# Prerequisites

This course assumes a foundational knowledge in HTML, CSS and JavaScript.



# Installation

<pre><code class="hljs" data-line-numbers><!-- development version -->
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js">
</script>
</code></pre>

or

<pre><code class="hljs" data-line-numbers><!-- production version -->
<script src="https://cdn.jsdelivr.net/npm/vue"></script>
</code></pre>
  
That's it.



# Hello World

HTML  
<pre><code data-line-numbers><div id="app">
	{{ greetings }}
</div>
</code></pre>

JavaScript  
<pre><code data-line-numbers>new Vue({
  el: '#app',
  data: {
    greetings: 'Hello Vue, Rajkot!'
  }
})
</code></pre>



# Hello World
### Output:
<div style="background-color: white; color: black; min-height: 200px; text-align: left;">
	Hello Vue, Rajkot!
</div>



# Hello World
### Vue Instance
<pre><code data-line-numbers>new Vue({
	// Options
})
</code></pre>



# Hello World
### Options
> Some thing
