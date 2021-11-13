<script context="module">
    export async function load({page}) {
        const customerId = page.params.id;
        return {
            props: { customerId }
        }
    }
    
</script>
<script>
    export let customerId;
</script>

<p>Customer ID: {customerId}</p>