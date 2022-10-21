<template>
  <q-page class="constrain q-pa-md">
    <q-card class="card-post" flat bordered>
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://cdn.quasar.dev/img/boy-avatar.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label>enes_can</q-item-label>
          <q-item-label caption>
            Adana, Turkey
          </q-item-label>
        </q-item-section>
      </q-item>

      <q-separator />

      <q-img
          class="col"
          src="https://cdn.quasar.dev/img/mountains.jpg"
        />

        <q-card-section>
        <div>Banjaran Alp</div>
        <div class="text-caption text-grey">October 21 7:18PM </div>
      </q-card-section>

    </q-card>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HomePage',
  data() {
    return {
      posts: [
        {
          id: 1,
          caption: 'Banjaran Alp',
          date: 1666369413255,
          location: 'Adana, Turkey',
          imageUrl: 'https://cdn.quasar.dev/img/mountains.jpg'
        },
        {
          id: 2,
          caption: 'Banjaran Alp',
          date: 1666369413255,
          location: 'Adana, Turkey',
          imageUrl: 'https://cdn.quasar.dev/img/mountains.jpg'
        },
        {
          id: 3,
          caption: 'Banjaran Alp',
          date: 1666369413255,
          location: 'Adana, Turkey',
          imageUrl: 'https://cdn.quasar.dev/img/mountains.jpg'
        },
        {
          id: 1,
          caption: 'Banjaran Alp',
          date: 1666369413255,
          location: 'Adana, Turkey',
          imageUrl: 'https://cdn.quasar.dev/img/mountains.jpg'
        },

      ]
    }
  }
})
</script>

<style lang="sass">
  .card-post
    .q-img
      min-height: 200px
</style>
