<template>
  <b-card-footer>
    <div class="d-flex justify-content-center">
      <b-button pill variant="outline-primary" @click="modalShow = !modalShow">Share</b-button>

      <b-modal v-model="modalShow">
        <div align="center">
          <!-- AddToAny BEGIN -->
          <div class="a2a_kit a2a_kit_size_32 a2a_default_style">
            <a class="a2a_dd" href="https://www.addtoany.com/share"></a>
            <a class="a2a_button_facebook"></a>
            <a class="a2a_button_twitter"></a>
            <a class="a2a_button_whatsapp"></a>
            <a class="a2a_button_linkedin"></a>
            <a class="a2a_button_telegram"></a>
            <a class="a2a_button_google_gmail"></a>
          </div>
          <script async src="https://static.addtoany.com/menu/page.js"></script>
          <!-- AddToAny END -->
        </div>
      </b-modal>
    </div>
  </b-card-footer>
</template>

<script>
export default {
  data() {
    return {
      modalShow: false,
    };
  },
};
</script>

<style scoped>
</style>