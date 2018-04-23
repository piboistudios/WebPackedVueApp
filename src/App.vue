<!-- Latest compiled and minified CSS -->
<template lang="jade">
#container(style="text-align: center")
  h1(class="#jumbotron") Vue App Web Packed!
  p {{ testModel.name }} World!
</template>
<script>
export default {
  data() {

    return {
      greeting: "Hello",
    testModel: {
      name: "Bob",
      occupation: "Worker"
    }
  }
  },
  created: function(){
    this.testModel.name = "Rick";
  }

}

</script>

<style lang = "scss">
@import url("https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css");
</style>
