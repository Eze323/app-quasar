<template>
  <div class="q-pa-md row justify-center">
    <div style="width: 100%; max-width: 600px">
      <q-chat-message
        name="me"
        avatar="https://cdn.quasar.dev/img/avatar1.jpg"
        :text="['Hola cachorra como estas?? tanto tiempo que no te veia']"
        stamp="7 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="Jane"
        avatar="https://cdn.quasar.dev/img/avatar5.jpg"
        :text="['Que haces perdido, todo muy tranquilo. Cuando nos juntamos a charlar, tengo muchas cosas para contarte']"
        stamp="4 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="me"
        avatar="https://cdn.quasar.dev/img/avatar2.jpg"
        :text="['Hola cachorra como estas?? tanto tiempo que no te veia']"
        stamp="7 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="Jane"
        avatar="https://cdn.quasar.dev/img/avatar3.jpg"
        :text="['Que haces perdido, todo muy tranquilo. Cuando nos juntamos a charlar, tengo muchas cosas para contarte']"
        stamp="4 minutes ago"
        text-color="black"
        bg-color="secundary"
      />
    </div>
  </div>
</template>

<script setup lang="ts">

</script>
