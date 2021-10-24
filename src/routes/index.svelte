<script>
	import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    import Footer from '$lib/Footer.svelte';
    let myInfo = {
        title: "Info",
        item1: "Dylan",
        item2: 16,
        item3: "not telling",
    }
    let myHobby = {
        title: "Hobby",
        item1: "playing games",
        item2: "watching shows",
        item3: "nothing",
    }
    let myPosonality = {
        title: "Posonality",
        item1: "calm",
        item2: "patient",
        item3: "hard working",
    }


</script>
 
<Header title = "My Biography"/>

<Section {...myInfo} />

<Section {...myHobby} />

<Section {...myPosonality} />
    
<Footer gitHub ="https://github.com/dylan99913/refactored-octo-broccoli" />