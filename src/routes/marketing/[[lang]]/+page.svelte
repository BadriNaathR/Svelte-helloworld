<script>
    import {page} from '$app/stores';
    const greeting = {
        en : "Hello" , 
        es : "Hoda" , 
        fr : "Bonjo"
    };
    const {lang = 'en'} = $page.params
    const greetings = greeting[lang];
</script>

<h1>{greetings}</h1>