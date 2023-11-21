<script>
  let title = "Deal singh"
  const changeTitle = () => {
    title = "Yo Yo Honey Singh"
  }
</script>

<div class="main">
  <h1>{title}</h1>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil nostrum ipsa aliquam corrupti modi expedita, dolores aperiam et mollitia dolorem perferendis minus sunt id tempore, iusto veritatis ad, temporibus reprehenderit!</p>

  <button on:click={changeTitle}>Change Title</button>
  <input type="text" bind:value={title} />
</div>

<style>
  .main {
    text-align: center;
    margin: 20px auto;
  }
</style>