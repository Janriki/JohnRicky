<template> 
  <div class="flex justify-center">
    <div class="w-1/4 flex flex-col">
      <div class="flex flex-wrap bg-gray-100 pt-8">
        <label class="text-left w-full">{{ msg }}</label>
        <input type="text" id="fname" class="w-full"/>
      </div>
      <div class="flex justify-end bg-gray-400 w-full p-8">
          <button class=" text-black rounded bg-gray-700">Create</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
