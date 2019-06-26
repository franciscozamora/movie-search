<template>
  <div>
    <nav class="navbar navbar-light bg-light">
      <form class="form-inline" @submit.prevent="search">
        <input v-model="titulo"
          class="form-control mr-sm-2"
          type="search"
          placeholder="Search"
          aria-label="Search"
        >
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'navBar',
 data() {
  return{
        titulo:'',
     }
  },
 methods: {
   search(){
     console.log('hola')
      },
    }
}
</script>