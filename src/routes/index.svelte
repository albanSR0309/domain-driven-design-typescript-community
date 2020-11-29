<script>
    import Hero from "../components/home/Hero.svelte";
    import MetaData from "../components/commom/MetaData.svelte";

    const metadata = {
        title: 'Domain-Driven Design #typescript community',
        description: 'Discover the main contents, events and reasons to join the community. It"s free.',
        image: 'https://domain-driven-design-typescript/shared_image.jpg',
        imageAlt: 'Domain-Driven Design typescript community',
        url: 'domain-driven-design-typescript.com'
    }
</script>

<MetaData {metadata}/>
<Hero />