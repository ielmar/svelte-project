<script>
  import "./app.css";
  export let name;

  let searchTerms = [
    'human','nature','fruit','animal','insect','sky','travel','voyage','city','night','day','flower', 'wallpapers', 'backgrounds', 'happy', 'love', 'cat', 'dog'
  ]
  searchTerms = searchTerms.sort(() => Math.random() - 0.5)
</script>

<main>
  <div class="container px-4 mx-auto border border-indigo-500">    
    <h1 class="text-5xl font-bold">Photo Gallery. Hello, {name}</h1> 

    <section class="px-4 py-8">
      <div class="flex flex-wrap mx-4">
        {#each searchTerms as term, i}
          {#if i < 2}
          <div class="px-4 mb-8 md:w-1/2 md:mb-0"><img class="rounded shadow-md" src={`https://source.unsplash.com/random/1280x720/?${term}`} alt={term}></div>
          {/if}
        {/each}
      </div>
    </section>

    <section class="px-4 pt-8">
      <div class="flex flex-wrap mx-4">
        {#each searchTerms as term, i}
          {#if i > 1 && i < 8}
          <div class="px-4 mb-8 md:w-1/3"><img class="rounded shadow-md" src={`https://source.unsplash.com/random/1280x720/?${term}`} alt={term}></div>
          {/if}
        {/each}
      </div>
    </section>

  </div>
</main>
