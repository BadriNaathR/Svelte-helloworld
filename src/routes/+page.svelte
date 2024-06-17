<script>
    import {goto} from "$app/navigation";

    const handle = () =>{
        console.log("Placing order");
        goto('/products')
    }
</script>


<h1>Hello world</h1>


<a href="/products">Products</a>
<a href="/about">About</a>
<button on:click={handle}>Place Order</button>