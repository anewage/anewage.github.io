<template>
  <v-footer height="auto" color="primary lighten-1">
    <v-layout justify-center row wrap>
      <span style="color: white;">To be completed soon...</span>
      <v-btn nuxt v-for="link in links" :key="link" :to="link.to" color="white" flat round>
        {{ link.title }}
      </v-btn>
      <v-flex primary lighten-2 py-3 text-xs-center white--text xs12>
        <iframe src="https://ghbtns.com/github-btn.html?user=rajabiseraji&repo=rajabiseraji.github.io&type=star&count=true" frameborder="0" scrolling="0" width="90px" height="20px"></iframe> <br>
        <tiny>Built with <span class="red--text">&#9829;</span> using Vue, Nuxt and Vuetify by: <a href="https://rajabiseraji.github.io" style="color: rgba(252,255,186,0.99);">Mohammad Rajabi</a></tiny>
      </v-flex>
    </v-layout>
  </v-footer>
</template>

<script>
export default {
  data () {
    return {
      links: [
        // { icon: 'apps', title: 'Home', to: '/', image: '/menu.svg' },
        // { icon: 'info', title: 'About me', to: '/story', image: '/information.svg' },
        // { icon: 'school', title: 'Education', to: '/education', image: '/mortarboard.svg' },
        // { icon: 'language', title: 'Language', to: '/language', image: '/translate.svg' },
        // { icon: 'work', title: 'Experience', to: '/experience', image: '/briefcase.svg' },
        // { icon: 'work', title: 'Projects and Research', to: '/projects', image: '/analytics.svg' },
        // { icon: 'color_lens', title: 'Skills', to: '/skills', image: '/skills.svg' },
        // { icon: 'attach_money', title: 'Honours and Awards', to: '/awards', image: '/cup.svg' },
        // { icon: 'attach_money', title: 'Gallery', to: '/gallery', image: '/attach.svg' },
        // { icon: 'contacts', title: 'Contact', to: '/contact', image: '/contact.svg' },
        // { icon: 'contacts', title: 'About This Site', to: '/about', image: '/question.svg' }
      ]
    }
  }
}
</script>

<style scoped>
</style>
