<template>
  <NavBar/>
  <router-view/>
</template>




<script>
import NavBar from './components/NavBar.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap"
// import $ from 'jquery'


export default {
  components: {
    NavBar
  },
  setup() {
    // $.ajax({
    //   url: "http://127.0.0.1:3000/user/account/token/",
    //   type: "post",
    //   data: {
    //     username: 'name2',
    //     password: "pass2",
    //   },
    //   success(resp){
    //     console.log(resp);
    //   },
    //   error(resp) {
    //     console.log(resp);
    //   }
    // })

    // $.ajax({
    //   url: "http://127.0.0.1:3000/user/account/info/",
    //   type: "get",
    //   headers: {
    //     Authorization: "Bearer " + "eyJhbGciOiJIUzI1NiJ9.eyJqdGkiOiI0NmM2ZmJlYjAzNmM0ZmI0OGIzZWE0MTgwMGQzZTFkNCIsInN1YiI6IjIiLCJpc3MiOiJzZyIsImlhdCI6MTcyNzI0OTIyOSwiZXhwIjoxNzI4NDU4ODI5fQ.9F5wphNJG3sUz_sg4g76GFkt-2YopXVuQbRpkGP278I"
    //   },
    //   success(resp){
    //     console.log(resp);
    //   },
    //   error(resp) {
    //     console.log(resp);
    //   }
    // });

    // $.ajax({
    //   url: "http://127.0.0.1:3000/user/account/register/",
    //   type: "post",
    //   data: {
    //     username: 'name4',
    //     password: "pass4",
    //     confirmedPassword: "pass4",
    //   },
    //   success(resp) {
    //     console.log(resp)
    //   },
    //   error(resp) {
    //     console.log(resp)
    //   }
    // })
  }
}
</script>

<style>
body {
  background-image: url("@/assets/images/background.png");
  background-size: cover;
}
</style>
