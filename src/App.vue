<template>
  <div class="q-pa-md">
    <q-toolbar class="bg-purple text-white shadow-2 rounded-borders">
      <q-btn flat label="ROLLERVERSE" />
      <q-space />
    
    </q-toolbar>
  </div>

  <div class="q-pa-md">
    <div class="q-gutter-md row">

      <q-btn color="primary" label="DS5">
        <q-menu
          transition-show="flip-right"
          transition-hide="flip-left"
        >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>Having fun</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Crazy for transitions</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Mind blown</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>

      <q-btn color="primary" label="DS4">
        <q-menu
          transition-show="scale"
          transition-hide="scale"
        >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>Having fun</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Crazy for transitions</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Mind blown</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>

      <q-btn color="primary" label="Xbox One">
        <q-menu
          transition-show="jump-down"
          transition-hide="jump-up"
        >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>Having fun</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Crazy for transitions</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Mind blown</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>

      <q-btn color="primary" label="Nintendo">
        <q-menu
          transition-show="rotate"
          transition-hide="rotate"
        >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>Having fun</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Crazy for transitions</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Mind blown</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>

    </div>
  </div>

  <div class="q-pa-md">
    <div class="q-col-gutter-md row items-start">
      <div class="col-6">
        <q-img src="DS5.jpg">
          <div class="absolute-bottom text-subtitle1 text-center">
            PLAYSTATION 5 CONTROLLER
          </div>
        </q-img>
      </div>

      <div class="col-6">
        <q-img src="ds4.jpg">
          <div class="absolute-bottom text-subtitle1 text-center">
            PLAYSTATION 4 CONTROLLER
          </div>
        </q-img>
      </div>

      <div class="col-6">
        <q-img src="XBOX.jpg">
          <div class="absolute-bottom text-subtitle1 text-center">
            XBOX ONE CONTROLLER
          </div>
        </q-img>
      </div>

      <div class="col-6">
        <q-img src="nintendo.jpg">
          <div class="absolute-bottom text-subtitle1 text-center">
            NINTENDO SWITCH CONTROLLER
          </div>
        </q-img>
      </div>
    </div>
  </div>

  <q-layout view="hHh lpR fFf">


<!-- Main Content -->
<q-page-container>
  <router-view />
</q-page-container>

<!-- Footer -->
<q-footer class="bg-grey-8 text-white">
  <q-toolbar>
    <q-toolbar-title>
      &copy; 2024 Daffa Khaiza Irawan
    </q-toolbar-title>
    
  </q-toolbar>
</q-footer>

</q-layout>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      tab: ref('')
    }
  }
}
</script>

<style scoped>
.q-footer {
  padding: 10px 20px;
}
</style>