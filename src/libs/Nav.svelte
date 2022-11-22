<script>
  

    const adds=[
        {name:'home',link:'/'},
        {name:'html',link:'/html'},
        {name:'css',link:'/css'},
        {name:'js',link:'/js'},
    ]
</script>
<main>
    {#each adds as x}
    <a class="one" href="{x.link}">{x.name}</a>
        
    {/each}
    
</main>
<style>
    a{
        margin: 5px;
        padding: 5px;
        border-radius: 2px;
        text-decoration: none;
        color: blue;
        box-shadow: 0 0 10px 2px gainsboro;
        transition: all 1s;
        display: inline-block;

        
        
    }
    a:hover{
        background-color:rgb(97, 93, 93);
        color: white;
        transform: translate(3px,3px);
        
        
       
    }
    
    
   

</style>