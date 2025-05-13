
<script>

    import Footer from "$lib/Footer.svelte";
  import UserDisplay from "$lib/UserDisplay.svelte";
    import Card from "$lib/Card.svelte";
    import Quote from "$lib/Quote.svelte";

    
      let quote = {
    quoteText: "Words can be like X-rays.",
    author: "Aldous Huxley", 
publication: "Brave new world",
citeUrl: "https://www.huxley.net/bnw/four.html",
    }

</script>



<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<Quote {quote}/>
<Card />

<Card />

<UserDisplay />


<Footer />
