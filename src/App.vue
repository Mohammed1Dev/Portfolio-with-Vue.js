<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">My-Resume</router-link> 
    </div>
    <router-view />
  </div>
</template>

<style>
      #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
      }
      #nav {
        background-color: #0ca5e2 !important;
        text-align: center;
        color: #2c3e50;
        height: 65px;
        display: flex;

      }
      a{
      color: rgb(13, 73, 100) !important;
      text-align: center;
      margin-top: 10px;
      font-size: 30px;
      margin-left: 55rem;

      }

      label {
        color: rgb(250, 243, 243);
        font-size: 20px;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
      }

      .form-control {
          display: block;
          width: 60%;
          height: calc(2.5em + 0.75rem + 2px) !important;
          padding: 0.375rem 0.75rem;
      }
      .home {
        background-image: url('bg.jpg');
        background-size: cover;
      }

      .btn.btn-danger{
        background-color: #1ee789;
        border-color: #108f4b;
        margin-bottom: 20px;
        padding: 20px;
      }
      .btn.btn-danger:hover {
        color: white;
        background-color: #c7957e;
          border-color: #c7957e;

      }
      h1 {
        color: #41be8a;
      }

</style>
