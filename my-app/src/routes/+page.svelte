<script>
    import Header from './Header.svelte';
    import Mom from './Mom.svelte';
    import Contact from './Contact.svelte';
    import NewClients from './NewClients.svelte';
    import RatesInsurance from './RatesInsurance.svelte';
</script>
<!--Mom is all of the section about Gina Kane
Contact includes the contact information and facebook/linkedin hyperlinks
NewClients includes all the info needed for said new client
RatesInsurance includes all that information



include another page with the link below to show
https://www.divorceprogramflorida.com/kane.html

-->


<section>
    <Header/>
    <h1>Welcome to SvelteKit</h1>
    <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
    
    <Mom />
    <Contact />
    <NewClients />
    <RatesInsurance />
</section>
