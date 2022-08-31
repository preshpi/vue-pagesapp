<template>
  <header>
    <div>
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          
           <a class="navbar-brand text-4xl font-bold" href="#">BizTech</a>
           <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarNav">
               <ul class="navbar-nav lg:text-right">
                    <li class="nav-item hover:text-blue-500  mb-2 lg:mx-3">
                      <router-link to="/">Home</router-link> 
                      </li>
                      <li class="nav-item hover:text-blue-500  mb-2 lg:mx-3 ">
                        <router-link to="/about">About</router-link>
                       </li>   
                       <li class="nav-item hover:text-blue-500  mb-2 lg:mx-3 ">
                        <router-link to="/contact">Contact</router-link>
                       </li>           
                </ul>
            </div>
        </div>


      </nav>
    </div>
  </header>

  <router-view/>
</template>

<!-- <style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style> -->
