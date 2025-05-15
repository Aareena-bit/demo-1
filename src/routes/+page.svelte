<script>

    import Footer from "$lib/Footer.svelte";
  import UserDisplay from "$lib/UserDisplay.svelte";
    import Card from "$lib/Card.svelte";
    import Quote from "$lib/Quote.svelte";
    import Info from "";

    
      let quote = [{
    quoteText: "Words can be like X-rays.",
    author: "Aldous Huxley", 
    publication: "Brave new world",
    citeUrl: "https://www.huxley.net/bnw/four.html",
      },
      {
      quoteText: "Happy",
      author: "Riley Manson",
      },

    ];

    const colors = ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet'];
let selected = $state(colors[0]);


    
</script>



<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
{#each quote as quotes}
<Quote {quotes} />
{/each}

<div>
{#each colors as color}
<button 
style="background-color: red;"
aria-label="red"
aria-current={selected === 'red'}
onclick={() => selected = 'red'}>

</button>
{/each}

</div>

<Card />

<Card />

<UserDisplay />


<Footer />
