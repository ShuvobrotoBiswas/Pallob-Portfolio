<template>
  <div class="q-pa-md justify-center items-center">
    <q-img
      src="~assets/img1.jpeg"
      spinner-color="white"
      style="height: 400px; max-width: 600px"
      img-class="my-custom-image"
      class="rounded-borders"
    >
      <div class="absolute-bottom text-subtitle1 text-center">
        Hey Man <br>
        Welcome to my Website <br>
        <q-btn
          color="black"
          icon="facebook"
          label="Checkout my facebook"
          href="https://www.facebook.com/Pallob.Vau71"
          />
      </div>
    </q-img>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageIndex",
});
</script>
