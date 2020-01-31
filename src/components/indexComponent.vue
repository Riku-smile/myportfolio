<template lang="html">
  <article class="container mx-auto">
    <!-- background -->
    <div id="bg" class="flex flex-col items-center h-screen">
      <h2 class="text-center text-4xl">Welcome MyPortFolio!!</h2>
      <p class="text-center text-3xl">↓下へスクロール↓</p>
    </div>
    <!-- // -->
    <section class="container mx-auto">
      <!-- policy -->
      <div id="policy" class="container bg-orange-100 py-4">
        <h2 class="font-thin text-center text-4xl border-b border-orange-400 border-dashed">Policy</h2>
        <div class="flex justify-around flex-col lg:flex-row">
          <div class="bg-white my-8 py-8 w-full lg:w-5/12">
          <h3 class="text-2xl pl-8 font-bold border-l-8 border-red-500">最適なページをお作りいたします。</h3>
          <p class="text-lg px-8 py-4">様々な種類の商売があり、それぞれが異なるターゲティングをしています。
          私は、そんな１つ１つのターゲティング層、ニーズに合わせたページを作ることをお約束いたします。</p>
          </div>
          <div class="bg-white my-8 py-8 w-full lg:w-5/12">
            <h3 class="text-2xl pl-8 font-bold border-l-8 border-red-500">報連相の徹底</h3>
            <p class="text-lg px-8 py-4">改善した方が良いと感じた点、納期のご相談など、クライエント様とのコミュニケーションを欠かさず行います。
            また、都合によりお電話の対応ができなかった場合は24時間以内に折り返しご連絡させていただきます。</p>
          </div>
        </div>
      </div>
      <!-- service -->
      <div id="service" class="container bg-orange-200 py-4">
        <h2 class="font-thin text-center text-4xl border-b border-orange-400 border-dashed">Service</h2>
        <!-- coding -->
        <div class="mt-4">
          <h3 class="text-center text-2xl">コーディング作業</h3>
          <p class="text-center text-xl font-bold tracking-wider text-gray-500">HTML / CSS</p>
          <div class="flex flex-col lg:flex-row">
            <div class="irast flex justify-around w-full lg:w-1/2 h-auto">
            <svg xmlns="http://www.w3.org/2000/svg" width="225" height="225" viewBox="221.807 89.47 440 621.061" enable-background="new 221.807 89.47 440 621.061"><filter id="a" width="150%" height="150%" x="-5%" y="-5%"><feFlood flood-color="#000" result="floodFill" flood-opacity=".5"/><feComposite in="floodFill" in2="SourceAlpha" operator="in" result="coloredAlpha"/><feGaussianBlur in="coloredAlpha" result="blur" stdDeviation="8"/><feComposite in="blur" in2="SourceGraphic" operator="out" result="maskedOffsetBlur"/><feMerge><feMergeNode in="maskedOffsetBlur"/><feMergeNode in="SourceGraphic"/></feMerge></filter><g filter="url(#a)"><path fill="#e44d26" d="M261.849 660.647l-40.042-449.125h440l-40.086 449.054-180.184 49.954z"/><path fill="#f16529" d="M441.807 672.348l145.596-40.367 34.258-383.735H441.807z"/><path fill="#ebebeb" d="M441.807 414.82h-72.888l-5.035-56.406h77.923V303.33H303.683l1.32 14.778 13.538 151.794h123.266zM441.807 557.876l-.242.066-61.346-16.566-3.922-43.93h-55.294l7.718 86.489 112.834 31.323.252-.071z"/><path d="M262.745 89.47h27.992v27.656h25.606V89.47h27.993v83.75h-27.993v-28.044h-25.606v28.044h-27.99l-.002-83.75zM381.149 117.244h-24.642V89.47H433.8v27.774h-24.654v55.976H381.15v-55.976h-.001zM446.065 89.47h29.19l17.955 29.428 17.938-29.428h29.2v83.75h-27.882v-41.512l-19.259 29.778h-.481l-19.272-29.778v41.512h-27.39V89.47zM554.277 89.47h28v56.068h39.368v27.682h-67.368V89.47z"/><path fill="#fff" d="M441.617 414.82v55.082h67.83l-6.395 71.44-61.435 16.58v57.307l112.924-31.294.826-9.309 12.946-145.014 1.344-14.792h-14.842zM441.617 303.33v55.084H574.67l1.103-12.382 2.51-27.924 1.318-14.778z"/></g></svg>
            <svg enable-background="new 0 0 1771 2499.8" width="225" height="225" viewBox="0 0 1771 2499.8" xmlns="http://www.w3.org/2000/svg"><path d="m1387.8 92.5h-146.9l152.8 165.9v78.9h-314.8v-92.4h152.8l-152.8-165.9v-79h309zm-371.4 0h-147.1l153 165.9v78.9h-314.9v-92.4h152.8l-152.8-165.9v-79h309zm-367.8 3.8h-158.5v144.8h158.5v96.3h-271.3v-337.4h271.3z" fill="#131313"/><path d="m161.2 2299.1-161.2-1807.7h1771l-161.4 1807.4-725.2 201z" fill="#1572b6"/><path d="m885.5 2346.2 586-162.5 137.8-1544.5h-723.8z" fill="#33a9dc"/><path d="m885.5 1294.1h293.4l20.2-227h-313.6v-221.6h556l-5.3 59.5-54.5 611h-496.2z" fill="#fff"/><path d="m886.7 1869.9h-1l-246.9-66.7-15.8-176.8h-222.4l31.1 348.1 454.2 126.4h1.3v-231z" fill="#ebebeb"/><path d="m1160.1 1506.3-26.7 296.7-247.3 66.7v231l454.5-126 3.3-37.5 38.6-431h-222.4z" fill="#fff"/><path d="m886.3 845.5v221.7h-535.4l-4.6-49.8-10.1-112.4-5.3-59.5zm-.8 448.6v221.7h-244.1l-4.3-49.8-10.1-112.4-5.3-59.5h263.7z" fill="#ebebeb"/></svg>
            </div>
            <div class="text text-left text-xl items-center  w-full lg:w-1/2">
                <p>私はHTML及びにCSSを学習しています。そのため、クライエントが作りたい静的なサイトを作成することが可能です。</p>
            </div>
          </div>
          <!-- // -->
          <!-- JavaScript -->
          <div class="mt-4">
            <h3 class="text-center text-2xl">動的サイト</h3>
            <p class="text-center text-xl font-bold tracking-wider text-gray-500">JavaScript / PHP</p>
            <div class="flex flex-col lg:flex-row">
              <div class="irast flex justify-around items-center w-full lg:w-1/2 h-auto">
              <svg width="225" height="225" viewBox="0 0 256 256" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMinYMin meet"><path d="M0 0h256v256H0V0z" fill="#F7DF1E"/><path d="M67.312 213.932l19.59-11.856c3.78 6.701 7.218 12.371 15.465 12.371 7.905 0 12.89-3.092 12.89-15.12v-81.798h24.057v82.138c0 24.917-14.606 36.259-35.916 36.259-19.245 0-30.416-9.967-36.087-21.996M152.381 211.354l19.588-11.341c5.157 8.421 11.859 14.607 23.715 14.607 9.969 0 16.325-4.984 16.325-11.858 0-8.248-6.53-11.17-17.528-15.98l-6.013-2.58c-17.357-7.387-28.87-16.667-28.87-36.257 0-18.044 13.747-31.792 35.228-31.792 15.294 0 26.292 5.328 34.196 19.247L210.29 147.43c-4.125-7.389-8.591-10.31-15.465-10.31-7.046 0-11.514 4.468-11.514 10.31 0 7.217 4.468 10.14 14.778 14.608l6.014 2.577c20.45 8.765 31.963 17.7 31.963 37.804 0 21.654-17.012 33.51-39.867 33.51-22.339 0-36.774-10.654-43.819-24.574"/></svg>
              <svg width="225" height="225" viewBox="0 0 256 134" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMinYMin meet"><g fill-rule="evenodd"><ellipse fill="#8993BE" cx="128" cy="66.63" rx="128" ry="66.63"/><path d="M35.945 106.082l14.028-71.014H82.41c14.027.877 21.041 7.89 21.041 20.165 0 21.041-16.657 33.315-31.562 32.438H56.11l-3.507 18.411H35.945zm23.671-31.561L64 48.219h11.397c6.137 0 10.52 2.63 10.52 7.89-.876 14.905-7.89 17.535-15.78 18.412h-10.52zM100.192 87.671l14.027-71.013h16.658l-3.507 18.41h15.78c14.028.877 19.288 7.89 17.535 16.658l-6.137 35.945h-17.534l6.137-32.438c.876-4.384.876-7.014-5.26-7.014H124.74l-7.89 39.452h-16.658zM153.425 106.082l14.027-71.014h32.438c14.028.877 21.042 7.89 21.042 20.165 0 21.041-16.658 33.315-31.562 32.438h-15.781l-3.507 18.411h-16.657zm23.67-31.561l4.384-26.302h11.398c6.137 0 10.52 2.63 10.52 7.89-.876 14.905-7.89 17.535-15.78 18.412h-10.521z" fill="#232531"/></g></svg>
              </div>
              <div class="text text-left text-xl items-center  w-full lg:w-1/2">
                  <p>JavaScriptを用いた簡易的な動きや、サイト側からメールを送信できるお問い合わせフォームを作成することができます。</p>
                  <!-- appMove -->
                  <div id="example-1" class="text-center">
                    <button @click="show = !show" class="border">
                      こちらをクリック
                    </button>
                    <transition name="slide-fade">
                      <p v-if="show">Thank you :)</p>
                    </transition>
                  </div>                      <!-- // -->
              </div>
            </div>
          </div>
          <!-- // -->
        </div>
      </div>
    </section>
  </article>
</template>

<script>
export default {
  name: 'indexComponent',
  data: function(){
    return{
      show: false
    }
  }
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

.slide-fade-enter-active {
  transition: all .3s ease; }

.slide-fade-leave-active {
  transition: all 0.8s cubic-bezier(1, 0.5, 0.8, 1); }

.slide-fade-enter, .slide-fade-leave-to
 {
  transform: translateX(10px);
  opacity: 0; }

</style>
