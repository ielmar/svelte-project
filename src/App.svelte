<script>
import "./app.css";
  export let name;
</script>

<main>
  <div class="container px-4 mx-auto border border-indigo-500">    
    <h1 class="text-5xl font-bold">Photo Gallery. Hello, {name}</h1> 

    <section class="px-4 py-8">
      <div class="flex flex-wrap mx-4">
        <div class="px-4 mb-8 md:w-1/2 md:mb-0"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
        <div class="px-4 mb-8 md:w-1/2 md:mb-0"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
      </div>
    </section>

    <section class="px-4 pt-8">
      <div class="flex flex-wrap mx-4">
        <div class="px-4 mb-8 md:w-1/3"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
        <div class="px-4 mb-8 md:w-1/3"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
        <div class="px-4 mb-8 md:w-1/3"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
        <div class="px-4 mb-8 md:w-1/3"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
        <div class="px-4 mb-8 md:w-1/3"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
        <div class="px-4 mb-8 md:w-1/3"><img class="rounded shadow-md" src="https://source.unsplash.com/random/1280x720" alt=""></div>
      </div>
    </section>

  </div>
</main>
