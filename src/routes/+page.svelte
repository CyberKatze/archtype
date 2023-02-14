<script lang="ts" >
export let data: any;
</script>


<h1>Cool Website</h1>
<main>
  <content>
    <h2>{data.title}</h2>
    <p>
      {data.summary}
    </p>

  </content>
</main>
<style>
main {
  max-width: 768px;
  background-color: red;
  margin: 0 auto;
}
</style>
