<template>
  <div class="home">
    <header>
      <Header/>
    </header>
    <main>
      <workComponent/>
    </main>
    <footer>
      <Footer topLink="work" />
    </footer>
  </div>
</template>

<script>
// @ is an alias to /src
import workComponent from '@/components/workComponent.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'work',
  components: {
    workComponent,
    Header,
    Footer
  }
}
</script>
