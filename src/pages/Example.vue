<template>
  <div class="wrapper-content wrapper-content--fixed">
    <section>
      <div class="container">
        <h1>Example Page</h1>
        <input type="text" v-model="Message">
        <button class="btn btnPrimary" @click="SetMessage">Change Message</button>
        <p> {{ getMessage }} </p>
      </div>
    </section>
  </div>
</template>



