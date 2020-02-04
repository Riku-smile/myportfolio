<template>
  <div class="home">
    <header>
      <Header/>
    </header>
    <main>
      <indexComponent/>
    </main>
    <footer>
      <Footer />
    </footer>
  </div>
</template>

<script>
// @ is an alias to /src
import indexComponent from '@/components/indexComponent.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'home',
  components: {
    indexComponent,
    Header,
    Footer
  }
}
</script>
