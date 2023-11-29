<script>
  export let data;
</script>

<!-- {#each data.categories as category}
  {category.title}
  <p>{@html category.content.html}</p>
  {category.knowledgeClip.url}
{/each} -->
<main>

{#each data.categories as category}

  <article class="category">
    <h2>{category.title}</h2>
    <p>{@html category.content.html}</p>


    <aside>
    <button>
    <img
    class="left-arrow"
    src="./arrow.svg"
    alt="Knop met pijl naar volgende video"
    />
    </button>

    <a href={category.knowledgeClip.url}>{category.knowledgeClip.url}</a>
    
    <button>
    <img
    class="right-arrow"
    src="./arrow.svg"
    alt="Knop met pijl naar volgende video"
    />
    </button>
    </aside>

  </article>
{/each}

</main>




<style>

</style>
