<template>
  <div class="about">
    <header>
      <Header/>
    </header>
    <main>
      <aboutComponent/>
    </main>
    <footer>
      <Footer />
    </footer>
  </div>
</template>
<script>
// @ is an alias to /src
import aboutComponent from '@/components/aboutComponent.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'about',
  components: {
    aboutComponent,
    Header,
    Footer
  }
}
</script>
