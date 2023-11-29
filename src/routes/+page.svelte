<script>

  import BlogBorder from "$lib/atoms/blogBorder.svelte";
  import BlogButton from "$lib/atoms/blogButton.svelte";
  import BlogHex from "$lib/atoms/blogHex.svelte";
  import Header from "$lib/molecules/header.svelte";
  import Tekenmethodes from "$lib/organisms/tekenmethodes.svelte";
  import Footer from "$lib/molecules/footer.svelte";
    export let data;
</script>

<BlogBorder />
<BlogButton />
<BlogHex />

<Header />
<Tekenmethodes data={data}/>
<Footer />

