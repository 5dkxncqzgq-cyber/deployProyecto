<template>
<h1> HOLA {{MI NOMBRE}} </h1>
<button v-on:click="decrementa" >-</button>
<span :class="contColor" id="contador">{{contador}}</span>
<buttonv-on:clock="incrementa">+</button>
<SumBoton>Material button</SumBoton>
</template>
