<template>
  <div class="welcome-msg">

    <h1>{{ msg }}</h1>

  </div>
</template>

<script>
    export default {
        name: 'HelloDHC',
        props: {
            msg: String
        }
    }
</script>

