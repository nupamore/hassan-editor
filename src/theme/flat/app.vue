
<template>

  <div class="container">
    <header>
      <h1>{{ title }}</h1>
      <player></player>
    </header>

    <section>
      <toolbar
        :dialogues="dialogues"
        :renderer="renderer">
      </toolbar>
      <hr>
      <dialogues
        :dialogues="dialogues">
      </dialogues>
    </section>
  </div>

</template>



<style lang="less">
  body {
    height: 100%;
  }

  .container {
    margin: 0 auto;
    max-width: 900px;
  }
</style>



<script>
  import app from '../../model/app'

  export default app
</script>
