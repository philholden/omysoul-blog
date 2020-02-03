<script>
  import Nav from "../components/Nav.svelte";

  export let segment;
</script>

<style>
  main {
    position: relative;
    max-width: 56em;
    background-color: white;
    padding: 2em;
    margin: 0 auto;
    box-sizing: border-box;
  }
</style>

<Nav {segment} />

<main>
  <slot />
  <hr style="margin: 32px 0" />
  <iframe
    width="540"
    height="960"
    src="https://8958425c.sibforms.com/serve/MUIEAMKAHraziho8bSNnrHK8FdhYSq0XMeXtpLQ0s8MSSKU8U0Y4KkOFXU40q14cmzFumK23xvL2yRm47L8yObKoJEeGy-9dOLmXLbkCXmDukgIPnSBsqirj-RP7_1USwpBJhAARVK7-kawixBNK6cTur2Zmbn1gF_xUzkVa8iFuHmMKjSvRLIdrcFwD5fgRYcrHrYdVR-affTFz"
    frameborder="0"
    scrolling="auto"
    allowfullscreen
    style="display: block;margin-left: auto;margin-right: auto;max-width: 100%;" />
</main>
