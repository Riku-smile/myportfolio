<template lang="html">
  <article class="container mx-auto">
    <!-- background -->
    <div id="bg" class="h-screen flex flex-col items-center">
      <h2 class="text-center text-4xl">Welcome MyPortFolio/ABOUT!!</h2>
      <p class="text-center text-3xl">↓下へスクロール↓</p>
    </div>
    <!-- // -->
    <section class="container mx-auto my-4 bg-orange-200">
      <h2 class="text-2xl text-center font-semibold pt-8 pb-4 border-b border-orange-400 border-dashed">好きなもの紹介</h2>
      <div class="wrapper flex justify-around flex-wrap mx-auto my-6">
        <!-- card1 -->
        <div class="max-w-sm rounded overflow-hidden shadow-lg m-4">
          <img class="w-full" src="./images/cat.jpeg" alt="Sunset in the mountains">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">My pet :)</div>
            <p class="text-gray-700 text-base">
              実家で飼っている猫(メス)です。去勢していないので発情期にはとても甘えん坊になります。
            </p>
          </div>
          <div class="px-6 py-4">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#cat</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#lovely</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">#cute</span>
          </div>
        </div>
        <!-- card2 -->
        <div class="max-w-sm rounded overflow-hidden shadow-lg m-4">
          <img class="w-full" src="./images/PC.jpg" alt="Sunset in the mountains">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">My PC</div>
            <p class="text-gray-700 text-base">
              使用しているパソコンになります。
              MacbookProの13インチです。かなり使いやすいです。
              もうWindowsでの作業はできないかも...
            </p>
          </div>
          <div class="px-6 py-4">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#PC</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#apple</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">#useful</span>
          </div>
        </div>
        <!-- card3 -->
        <div class="max-w-sm rounded overflow-hidden shadow-lg m-4">
          <img class="w-full" src="./images/バスケ.jpg" alt="Sunset in the mountains">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">My hobby</div>
            <p class="text-gray-700 text-base">
              小学校の頃にバスケをやっていました！
              今でも友人とバスケをして遊んでいます。
            </p>
          </div>
          <div class="px-6 py-4">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#hobby</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#basketball</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">#exciting</span>
          </div>
        </div>
        <!-- card4 -->
        <div class="max-w-sm rounded overflow-hidden shadow-lg m-4">
          <img class="w-full" src="./images/いけふくろう.jpg" alt="Sunset in the mountains">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">Caracter of Ikebukuro St'</div>
            <p class="text-gray-700 text-base">
              池袋駅にあるいけふくろうです。
              東口の待ち合わせ場所として需要があるようで、いつ見ても人がいます。
            </p>
          </div>
          <div class="px-6 py-4">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#Ikebukuro</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#station</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">#favorite</span>
          </div>
        </div>
        <!-- // -->
      </div>
    </section>
  </article>
</template>

<script>
export default {
  name: 'aboutComponent'
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
