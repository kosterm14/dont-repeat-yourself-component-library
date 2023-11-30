<script>
  export let data;
</script>

{#each data.categories as category}
  {category.title}
  {category.content.html}
  {category.knowledgeClip.url}
{/each}

