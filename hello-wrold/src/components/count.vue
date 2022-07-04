<template>
  <div>
     <h1>{{count}}</h1>
     <button @click="increment">+1</button>
  </div>
</template>

<script>
export default {
    name: 'MyCount',
    data() {
        return {    
            count: 0,
        }
    },
    methods:{
        increment() {
            this.count++
        },
    }        

}
</script>

<style>

</style>