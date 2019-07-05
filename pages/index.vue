<template>
  <div>
    <h2> Welcome to my first nuxt app</h2>
  </div>
</template>

<script>


export default {
  head() {
    return{
      title: "Welcome to Dad Jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Your best resource for corny dad jokes"
        }
      ]
    };
  }
};

</script>
