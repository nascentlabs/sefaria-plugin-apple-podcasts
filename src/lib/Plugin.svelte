<svelte:options customElement={{ tag: "sefaria-plugin", shadow: "none" }} />

<script>
  import ContentApplePodcasts from "./ContentApplePodcasts.svelte";
  let { sref } = $props();
</script>
<p>Apple Podcast for <strong>{sref}</strong></p>
<ContentApplePodcasts {sref}></ContentApplePodcasts>