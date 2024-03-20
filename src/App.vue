<script>
export default{
  data(){
    return{
      title: ['hello', 'ciao', 'hola', ]
    }
  }
}
</script>


<template>
<div>
  <ul v-for="saluto in  title" class="list-group">
  <li class="list-group-item">{{ saluto }}</li>
  <!-- <li class="list-group-item">A second item</li>
  <li class="list-group-item">A third item</li>
  <li class="list-group-item">A fourth item</li>
  <li class="list-group-item">And a fifth one</li> -->
</ul>
</div>
</template>


<style>

</style>
