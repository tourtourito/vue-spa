<template>
  <div>  
    <h1>{{ number}}</h1>
    <button @click="iAmClicked()">Click me!</button>
  </div>
</template>
 
<script>
    export default {
        data() {
            return {title: 'Not clicked yet',number:0}
        },
        methods: {
            iAmClicked() {
                this.title = 'Clicked';
                this.number++ ;
            }
        }
    };
</script>
