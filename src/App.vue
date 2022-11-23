<template>
  <div id="app">
    
    <h1>{{title}}</h1> 
    <Input />
    <!-- <input v-model="email" type="text" />
    <h1>{{email}}</h1>
   <input v-model="username" type="text" />
    <span :title="spanTitle">{{username}}</span>
    
    <h1 v-if="true">conmdutional true text</h1>
    <h1 v-else>conmdutional true text</h1>-->
    <div>
      {{ textOnScreen }}
    </div>
    </div>
</template>

<script>
  import input from "./components/Input.vue"
  export default{
    name : "AppComponent",
    data(){
        return{
          title : "First Page",
          /*username : "default value",
          email : "payal.kamde@yash.com",
          spanTitle : "user name is here",*/

        };
    },
    components:{
      input,
    },
    computed:{
      textOnScreen(){
        return "hello";
        //const x = this.username;
        //return x.toUpperCase();
      },
    },
  };

</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

  h1{
    color:green
  }
</style>
