<template>
<div class ="flex justify-center">
    
  <div class="flex flex-col bg-gray-300 ">
      <div>
    <h1>John Ricky</h1>
    </div>
    <div class="flex justify-center" >
      <label class="justify-center">Basic Information</label>
    </div>
    <div class="flex">
      <div class="w-1/2 p-5">
        <h3>Organization Name:</h3>
        <input type="text"/>
        <h3>Email:</h3>
        <input type="text" />
      </div>

      <div class="w-1/2 p-5">
        <h3>Facility Name:</h3>
        <input type="text"/>
        <h3 class="">Phone:</h3>
        <input type="text" />
      </div>
    </div>
    <div class="flex justify-end p-8">
    <button class="bg-green-400" >Update</button></div>
  </div>
</div>
</template>

<script>
export default {
  name: "Employee",
  props: {
    msg: String
  }
};
</script>

<style>
</style>