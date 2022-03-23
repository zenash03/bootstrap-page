<template>
  <v-app>
    <v-app-bar
      app
      color="deep-purple"
      dark
    >
      <div class="d-flex align-center mr-16">
        <v-toolbar-title>Bootstrap</v-toolbar-title>
      </div>
        <div v-for="item in items" :key="item">
            <v-btn text @click="directTo(item)">
                <v-toolbar-items>
                    {{ item }}
                </v-toolbar-items>
            </v-btn>
        </div>
      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
        outlined
        elevation="2"
      >
        <span class="mr-2 yellow--text">Download</span>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
    <v-footer color="grey lighten-5">
      <v-container>
        <v-row class="mt-16 grey--text">
          <v-col cols="3">
            <h3 class="black--text mb-2">Bootstrap</h3>
            <p>Designed and built with all the love in the world by the Bootstrap team with the help of our contributors.</p>
            <p>Code licensed MIT, docs CC BY 3.0.</p>
            <p>Currently v5.1.3.</p>
          </v-col>
          <v-col col="3">
            <h4 class="black--text mb-2">Link</h4>
            <p>Home</p>
            <p>Docs</p>
            <p>Example</p>
            <p>Themes</p>
            <p>Blog</p>
          </v-col>
          <v-col col="3">
            <h4 class="black--text mb-2">Guides</h4>
            <p>Getting Started</p>
            <p>Starter template</p>
            <p>Webpack</p>
            <p>Parcel</p>
          </v-col>
          <v-col col="3">
            <h4 class="black--text mb-2">Project</h4>
            <p>Bootstrap 5</p>
            <p>Bootstrap 4</p>
            <p>Icons</p>
            <p>RFS</p>
            <p>npm starter</p>
          </v-col>
          <v-col col="3">
            <h4 class="black--text mb-2">Community</h4>
            <p>Issues</p>
            <p>Discussions</p>
            <p>Corporate sponsors</p>
            <p>Open Collective</p>
            <p>Slack</p>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    items : [
      'Home',
      'Docs',
      'Example',
      'Icons',
      'Themes',
      'Blog'
    ]
  }),
};
</script>
