<template>
  <div class="bg-red-200">
    <header>
      <ul>
        <li><NuxtLink to="/">home</NuxtLink></li>
        <li><NuxtLink to="/about">about</NuxtLink></li>
        <li><NuxtLink to="/profiles/2">id 2</NuxtLink></li>
        <li><NuxtLink to="/profiles/3">id 2</NuxtLink></li>
        <li><NuxtLink to="/profiles/4">id 2</NuxtLink></li>
        <li><NuxtLink to="/profiles/5">id 2</NuxtLink></li>
        <li><NuxtLink to="/profiles/6">id 2</NuxtLink></li>
      </ul>
    </header>
    <h2>hi {{ $route.params.id }}</h2>
    <slot />
  </div>
</template>
<script setup></script>
