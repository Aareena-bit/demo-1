<script>
let quote = {
    quoteText: "Words can be like X-rays.",
    author: "Aldous Huxley", 
    publication: "Brave new world",
    citeUrl: "https://www.huxley.net/bnw/four.html",
}
</script>


<div>
    <blockquote cite={quote.citeUrl}> 
<p>
{quote.quoteText}    
</p>
</blockquote>
<p>-{quote.author}, <cite>{quote.publication}</cite></p>
</div>
<style>

</style>