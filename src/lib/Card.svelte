<script>
let {cardData} = $props();
let user = cardData.user;
let info = cardData.info;
</script>

<div>
    <h2>
        {cardData.title}
    </h2>

    <section class="card-info">
        <img src={cardData.image} alt="Coming soon">
        <p> {cardData.info} </p>
        
    </section>
    
</div>

<style>
div{
    border: 1px solid grey;
    max-width: 300px;
    border-radius: 3px;
    background-color: bisque;
    box-shadow: 5px 5px grey;
    margin: 0 1em 1em 0;
    padding: 0%;
    
    
}
section{
    display: flex;
}
img{

    height: 50px;
    width: 50px;
}

</style>

