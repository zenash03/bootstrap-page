<template>
<div>
  <v-container>
    <v-row class="py-14" id="home">
      <v-col cols="7">
        <h1 class="display-3 font-weight-medium mb-4">Build fast, responsive sites with Bootstrap</h1>
        <h2 class="font-weight-light mb-4">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.</h2>
        <v-btn color="deep-purple white--text mr-4" x-large>Get Started</v-btn>
        <v-btn color="grey" x-large outlined>Download</v-btn>
        <v-spacer></v-spacer>
        <p class="mt-3 grey--text">Currently v5.1.3 · <span class="text-decoration-underline">v4.6.x docs</span> · <span class="text-decoration-underline">All releases</span></p>
      </v-col>
      <v-col cols="4">
        <img src="../assets/bootstrap.png" width="550px" />
      </v-col>
    </v-row>
    <v-row class="mb-10">
      <v-col cols="12">
        <v-btn x-large color="green" class="white--text" icon elevation="1">
          <v-icon>mdi-code-tags</v-icon>
        </v-btn>
      </v-col>
      <v-col cols="6">
        <h2 class="font-weight-light mb-4 display-2">Installation</h2>
        <h3 class="mb-3">Install Bootstrap’s source Sass and JavaScript files via npm, Composer, or Meteor.</h3>
        <p>Package managed installs don’t include documentation or our full build scripts. You can also <span class="blue--text text-decoration-underline">use our npm template repo</span> to quickly generate a Bootstrap project via npm.</p>
        <v-btn outlined color="blue" x-large class="text-capitalize">
          Read installation docs
        </v-btn>
      </v-col>
      <v-col cols="6">
        <img src="../assets/code.png" width="700px" />
      </v-col>
    </v-row>
    <v-row class="mb-10">
      <v-col cols="12">
        <v-btn x-large color="blue" class="white--text" icon elevation="1">
          <v-icon>mdi-cloud</v-icon>
        </v-btn>
      </v-col>
      <v-col cols="6">
        <h2 class="font-weight-light mb-4 display-2">jsDelivr</h2>
        <h3 class="mb-3">When you only need to include Bootstrap’s compiled CSS or JS, you can use <span class="blue--text text-decoration-underline">jsDelivr</span>.</h3>
        <p>See it in action with our simple<span class="blue--text text-decoration-underline"> starter template</span>, or <span class="blue--text text-decoration-underline">browse the examples</span> jumpstart your next project. You can also choose to include Popper and our JS <span class="blue--text text-decoration-underline">separately</span>.</p>
        <v-btn outlined color="blue" x-large class="text-capitalize">
          Explode the docs
        </v-btn>
      </v-col>
      <v-col cols="6">
        <img src="../assets/code2.png" width="700px" />
      </v-col>
    </v-row>
    <v-row class="mb-10">
      <v-col cols="12">
        <v-btn x-large color="purple" class="white--text" icon elevation="1">
          <v-icon>mdi-circle</v-icon>
        </v-btn>
      </v-col>
      <v-col cols="6">
        <h2 class="font-weight-light mb-4 display-2">Bootstrap Icons</h2>
        <h3 class="mb-3">For the first time ever, Bootstrap has its own open source SVG icon library, designed to work best with our components and documentation.</h3>
        <p>Bootstrap Icons are designed to work best with Bootstrap components, but they’ll work in any project. They’re SVGs, so they scale quickly and easily, can be implemented in several ways, and can be styled with CSS.</p>
        <v-btn outlined color="blue" x-large class="text-capitalize">
          Get Bootstrap Icons
        </v-btn>
      </v-col>
      <v-col cols="6">
        <img src="../assets/bootstrap-icons.png" width="700px" />
      </v-col>
    </v-row>
    
  </v-container>
</div>
</template>

<script>
  import HelloWorld from '../components/HelloWorld'

  export default {
    name: 'Home',

    components: {
      HelloWorld,
    },
  }
</script>
