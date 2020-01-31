<template lang="html">
  <article class="container mx-auto">
    <!-- background -->
    <div id="bg" class="h-screen flex flex-col items-center">
      <h2 class="text-center text-4xl">Welcome MyPortFolio/WORKS!!</h2>
      <p class="text-center text-3xl">↓下へスクロール↓</p>
    </div>
    <!-- // -->
    <section class="container mx-auto bg-orange-200">
      <h2 class="text-2xl text-center pt-8 pb-4 border-b border-orange-400 border-dashed">過去作品 一覧</h2>
      <ul class="text-center">
        <li class="my-8 text-2xl list-none pl-0 text-blue-600 opacity-50 hover:opacity-100 hover:underline"><a href="#">＞</a></li>
        <li class="my-8 text-2xl list-none pl-0 text-blue-600 opacity-50 hover:opacity-100 hover:underline"><a href="#">＞</a></li>
        <li class="my-8 text-2xl list-none pl-0 text-blue-600 opacity-50 hover:opacity-100 hover:underline"><a href="#">＞</a></li>
      </ul>
    </section>
  </article>
</template>

<script>
export default {
  name: 'workComponent'
}
</script>

<style lang="css" scoped>
#bg {
background-color: white;
opacity: 0.8;
background-size: cover;
position: sticky;
top: 0;
left: 0;
z-index: -10;
}
</style>
