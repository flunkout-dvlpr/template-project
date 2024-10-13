<template>
  <q-page class="flex flex-center column">
    <q-card
      rounded
      class="q-ma-auto bg-primary"
      style="width: 350px; border-radius: 30px"
    >
      <!-- <img src="https://cdn.quasar.dev/img/mountains.jpg" /> -->
      <q-card-section
        class="bg-dark q-ma-md green-shadow"
        style="border-radius: 30px"
      >
        <div class="text-h6 text-center">Simple Web App</div>
        <div class="text-subtitle2 text-center">by flunkout_devlpr</div>
      </q-card-section>
      <q-card-actions align="center" class="q-mx-md">
        <q-btn
          rounded
          no-caps
          color="accent"
          label="Sign-In"
          class="text-weight-light"
          style="width: 300px"
        />
      </q-card-actions>
      <q-card-section>
        <q-list dark="true" bordered>
          <q-item
            class="bg-dark q-mb-md"
            clickable
            v-ripple
            style="border-radius: 30px"
          >
            <q-item-section avatar>
              <q-avatar
                size="xl"
                text-color="accent"
                color="secondary"
                icon="playlist_add"
              />
            </q-item-section>
            <q-item-section>
              <q-item-label>CREATE</q-item-label>
              <q-item-label caption>creat a record on the db</q-item-label>
            </q-item-section>
          </q-item>
          <q-item
            class="bg-dark q-my-md"
            clickable
            v-ripple
            style="border-radius: 30px"
          >
            <q-item-section avatar>
              <q-avatar
                size="xl"
                text-color="accent"
                color="secondary"
                icon="notes"
              />
            </q-item-section>
            <q-item-section>
              <q-item-label>READ</q-item-label>
              <q-item-label caption>read a record on the db</q-item-label>
            </q-item-section>
          </q-item>
          <q-item
            class="bg-dark q-my-md"
            clickable
            v-ripple
            style="border-radius: 30px"
          >
            <q-item-section avatar>
              <q-avatar
                size="xl"
                text-color="accent"
                color="secondary"
                icon="edit_note"
              />
            </q-item-section>
            <q-item-section>
              <q-item-label>UPDATE</q-item-label>
              <q-item-label caption>update a record on the db</q-item-label>
            </q-item-section>
          </q-item>
          <q-item
            class="bg-dark q-my-md"
            clickable
            v-ripple
            style="border-radius: 30px"
          >
            <q-item-section avatar>
              <q-avatar
                size="xl"
                text-color="accent"
                color="secondary"
                icon="delete_sweep"
              />
            </q-item-section>
            <q-item-section>
              <q-item-label>DELETE</q-item-label>
              <q-item-label caption>delete a record on the db</q-item-label>
            </q-item-section>
          </q-item>
        </q-list>
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
