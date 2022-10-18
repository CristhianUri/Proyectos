<template>
  <div class="container mt-3" >
    <Header />

    <Form />
  </div>

</template>

<script>
  import Header from "./component/Header.vue";
  import Form from "./component/Form.vue";
  export default {
    components: {
      Header,
      Form,
    },
  }
</script>

