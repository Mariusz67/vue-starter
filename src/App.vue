
<template>
  <div >
    <h>Twój email to {{email}}</h>
    {{email.length}}
    <input type="text" v-model="email">
  </div>

</template>

<script>


export default{
  data(){
    return {
      email:'',
    };
  }
}

</script>

<style>

</style>