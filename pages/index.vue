<template>
  <div>
    <nav class="navbar navbar-expand-md bg-warning justify-content-between">
      <div class="container-fluid">
        <a class="navbar-brand">
          <img class="icon-main" src="https://raw.githubusercontent.com/PokeAPI/media/master/logo/pokeapi_256.png"
            alt="POKEMON" />
        </a>
        <ul class="navbar-nav ms-auto">
          <form class="form-inline">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn bg-success my-2 my-sm-0" type="submit">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search"
                viewBox="0 0 16 16">
                <path
                  d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
              </svg>
            </button>
          </form>
        </ul>
      </div>
    </nav>
    <b-card>
      <b-card-body>
        <div class="container-fluid">
          <MainIndex />
        </div>
      </b-card-body>
    </b-card>
  </div>
</template>

<style scoped>
  .icon-main {
    width: 50%;
    height: 50%;
  }

</style>

<script>
  import MainIndex from '../components/MainIndex.vue'

  export default {
    components: {
      MainIndex,
    },
  }

</script>
