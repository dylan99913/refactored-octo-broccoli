<script>
	import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    let myInfo = {
        title: "Info",
        item1: "Dylan",
        item2: 16,
        item3: "not telling",
    }
</script>
 
<Header title = "My Biography">
    
</Header>

<Section {...myInfo} />
    
