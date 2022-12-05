<template>
   <div>{{msg}}</div>
  </template>
  <script>
  export default {
    name: 'HelloWorld',
    data () {
      return {
      }
    },
    props:{
        msg: {
            default: 'hello',
            type: String
        }
    },
    computed: {
    },
    created () {
    },
    methods: {
    }
  }
  </script>
