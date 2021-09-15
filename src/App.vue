<template> 
  <div> 
    <!-- Nav bar ---> 
    <nav 
      class="navbar navbar-dark bg-primary justify-content-between flexnowrap flex-row" 
    > 
      <div class="container"> 
        <a class="navbar-brand float-left">Agenda Telefonica  </a> 
        <ul class="nav navbar-nav flex-row float-right"> 
          <li class="nav-item"> 
            <router-link class="nav-link pr-3" to="/" 
              >Agregar contacto</router-link 
            >
            <router-link class="nav-link pr-3" to="/" 
              >Consultar contacto</router-link 
            >
            <router-link class="nav-link pr-3" to="/" 
              >Modificar contacto</router-link 
            >
            <router-link class="nav-link pr-3" to="/" 
              >Eliminar contacto</router-link 
            >
          </li> 
          <li class="nav-item"> 
            <router-link class="nav-link" to="/view">Vista general</router-link>
          </li> 
        </ul> 
      </div> 
    </nav> 
 
    <!-- Router view --> 
    <div class="container mt-5"> 
      <router-view></router-view> 
    </div>
  </div> 
</template>