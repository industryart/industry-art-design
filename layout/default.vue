<template>
  <div class="mainLayout">
    <section class="mainContainer">
     <slot />
    </section>
  </div>
  </template>

  <style scoped>
    .mainContainer{
      background-color:#000;
      height:100%;
      border: 1px red;
    }
  </style>