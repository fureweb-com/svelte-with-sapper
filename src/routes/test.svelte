<script>
  export let pageName = 'test'
</script>

<style lang="scss">
  $color: red;

  h1 {
    color: $color;
  }

  div {
    background: blue;

    > p {
      color: #fff;
    }
  }
</style>

<h1>page: {pageName}!</h1>

<div>
  <p>SASS is working!</p>
</div>