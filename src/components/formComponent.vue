<template lang="html">
  <div class="form my-8">
    <!-- お問い合わせ -->
    <h2 class="text-2xl text-center w-1/2 m-auto">お問い合わせ<span class="border-b border-red-600">（未実装）</span></h2>
    <form id="form" class="mail" action="index.html" method="post">
      <p class="text-center">メールアドレス<br>
      <input type="email" name="email" placeholder="your mail" class="border border-black"></p>
      <p class="text-center">内容<br>
      <textarea name="naiyo" rows="8" cols="80" placeholder="お問い合わせ内容" class="border border-black w-11/12"></textarea></p>
      <input class="block mx-auto h-10 w-20 hover:opacity-50" type="submit" name="submit" value="送信">
    </form>
  </div>
</template>

<script>
export default {
  name: 'formComponent'
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
