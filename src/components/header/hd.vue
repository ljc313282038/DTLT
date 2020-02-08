<template>
  <div>
  <div id="hd">地摊资源网</div>
  <ul>
    <li v-text="msg"></li>
  </ul>
  </div>
</template>

<script>
  export default {
    name: 'hd',
    data :function() {
      var x=1;

      return {
        msg: x+1
      }
    }
  }
</script>

<style>

  #hd{
  width: 100%;
      background: #962727;
      height: 5rem;
      color: aliceblue;
      text-align: center;
      line-height: 5rem;
      color: white;
      font-size: 1.5rem;
  }
</style>
