<template>
  <div class="container">
    <header-comp></header-comp>

    <div class="row">
      <!-- 여기 컨텐츠 -->
      <section id="page1" data-role="page">
        <div class="content" data-role="content">컨텐츠</div>
      </section>
    </div>

    <footer-comp></footer-comp>
  </div>
</template>
<script>
import Header from "./Header";
import Footer from "./Footer";
export default {
  data() {
    return {
      msg: "HELLO"
    };
  },
  components: {
    "header-comp": Header,
    "footer-comp": Footer
  }
};
</script>