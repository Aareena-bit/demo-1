<script>
let cardData = {
    title: "My Card",
    image: "https://picsum.photos/id/237/200/300",
    info:"This is the card information.",
};
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
image{

    height: 50px;
    width: 50px;
}

</style>

