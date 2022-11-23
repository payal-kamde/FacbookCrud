<template>
<div>
    <input v-model="username" type="text" />
    <span :title="spanTitle">{{username}}</span>
</div>
    
</template>
<script>
export default {
    name: "InputComponent",
    data(){
        return{
            username: "",
            spanTitle : "user name is here",
        };
    },
  
};
</script>
<style>

</style>