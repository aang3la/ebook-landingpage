<script>
    import '../app.css';

    let {children} = $props();
</script>

{@render children()}

<!-- we can use it besides this, we can render the children like
<slot /> -->