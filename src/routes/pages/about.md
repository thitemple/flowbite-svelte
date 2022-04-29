---
layout: docLayout
---

<script>
  import Htwo from '../utils/Htwo.svelte'
  import { Breadcrumb } from '$lib/index'
  let crumbs = [
    {
      label:'Home',
      href:'/'
    },
    {
      label:'About',
      href:'/about'
    }
  ]
</script>

<Breadcrumb {crumbs}/>

<h1 class="text-3xl w-full dark:text-white py-8">About Flowbite-Svelte</h1>

<Htwo label="Svelte" />

<p class="dark:text-white w-full text-lg py-2">
  Svelte is a modern and growing front-end compiler. Developers build boilerplate-free components using languages HTML, CSS and JavaScript. Svelte compiles your code to tiny, framework-less vanilla JS.</p>

<Htwo label="Flowbite Svelte" />

<p class="dark:text-white w-full text-lg py-2"><a href="/">Flowbite-Svelte</a> is an unofficial Flowbite component library for Svelte. All interactivities are handled by Svelte.
</p>


<p class="dark:text-white w-full text-lg py-2">This website uses Flowbite-Svelte components except the <a href="https://github.com/shinokada/svelte-sidebar" target="_blank">sidebar menu</a>.</p>
