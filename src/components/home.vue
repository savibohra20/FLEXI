<!--<template>
     <div>
        <h1>converting dollar in intoo ruppesss</h1>
        <input type="Number" v-model="dollar" placeholder="enter your data">
        <h2>{{dollar}}</h2>
        <input type="number" v-model="ruppeesss" placeholder="enter your msg">
        <h2>{{ruppeesss}}</h2>
        <p>{{ result }}</p>
    </div> -->
    
    <!-- <div>
    <h1>Dollar to INR Converter</h1>
    <div>
      <label for="dollar">Enter dollar amount:</label>
      <input type="number"  v-model="dollar">
    </div>-->


    <!-- <div>
      <label for="inr">INR:</label>
       <span >{{ converted }}</span> -->
      <!-- <h1>{{ converted }}</h1> -->
    <!--<div>
     <button @click="convertToINR">Convert to INR</button>
    <hr>
    <h1>INR to Dollar Converter</h1> -->
    <!--<div>
      <label for="inr2">Enter INR amount:</label>
      <input type="number" id="inr2" v-model="inr">
    </div>-->
    <!--<div>
      <label for="dollar2">Dollar:</label>
      <span id="dollar2">{{ converted2 }}</span>
    </div>-->
    <!-- <button @click="convertToDollar">Convert to Dollar</button> -->
  <!--</div>-->

  <!-- <div>
    <button @click="increment()" @mouseover="increment()">Click Me</button>
    <h1>You have pressed button {{counter}} times</h1>
</div> -->
    
</template>-->

<script>
// import { ProgressPlugin } from 'webpack';

export default {
    name : 'home',

    data( )
    {
        return {
            dollar : 0 , 
            ruppeesss : 0,
            // result :'',
            converted : 0,
            converted2 : 0,
            exchangerates :70 ,
            counter: 0
        }
    },
    methods : {
        // convertToINR()
        // {
        //     this.converted = (this.dollar * this.exchangerates ) +'INR' ;
        //     return this.converted;
        // },
        // convertToDollar()
        // {
        //     this.converted2 = (this.ruppeesss / this.exchangerates ) +'DOLLAR' ;
        //     this.converted2;
        // },
        increment() {
            this.counter++
        },
    },

}
</script>
-->
