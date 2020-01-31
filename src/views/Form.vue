<template>
  <div class="home">
    <header>
      <Header/>
    </header>
    <main>
      <formComponent/>
    </main>
    <footer>
      <Footer topLink="form" />
    </footer>
  </div>
</template>

<script>
// @ is an alias to /src
import formComponent from '@/components/formComponent.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'form',
  components: {
    formComponent,
    Header,
    Footer
  }
}
</script>
