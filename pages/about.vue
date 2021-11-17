<template>
  <div>
    <h1>About Dad Jokes</h1>
    <p>This is an app that displays corny dad jokes using a api.</p>
    <p>We've done the dirty work, scouring high and low for the dad jokes of your nightmares/dreams.</p>
    <p>Believe you me, the task was not one of ease, but of struggle, I almost damn near cursed!</p>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'About The App: Dad Jokes App',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'best place for corny dad jokes'
        }
      ]
    }
  }
}
</script>

<style>
* {
    font-family: sans-serif;
}
</style>
