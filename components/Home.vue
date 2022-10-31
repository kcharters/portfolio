<template>
  <div>
    <Nav/>
    <section>
      <Landing/>
    </section>
    <section>
      <About/>
    </section>
    <section>
      <Work/>
    </section>
    <section>
      <Services/>
    </section>
    <section>
      <Contact/>
    </section>
  </div>
</template>
<script>
export default {
  methods:{

  }
}
</script>
<style>
section{
  height: 100vh;
  width: 100vw;
}
section:nth-child(odd){
  background-color: #6e07f3;
}
</style>