<script>
  // @ts-nocheck
  /** @type {import('./$types').PageData} */
  export let data;
</script>

<svelte:head>
  <title>Hain.co | Email Verified</title>
</svelte:head>

<div class="hero is-fullheight">
  <div class="hero-body is-flex is-flex-direction-column is-justify-content-center is-align-items-center">
    <!-- logo -->
    <div class="image is-96x96">
      <img class="is-rounded" src="/checkIcon3.png" alt="Hain.co logo">
    </div>

    <!-- title -->
    <div class="titanone is-size-1-desktop is-size-3-touch has-text-link has-text-centered">
      Congratulations!
    </div>

    <!-- subtitle -->
    <div class="mb-6 mont is-size-6-tablet is-size-7-mobile has-text-centered">
      Your email {data.email} is now verified.
    </div>
  </div>
</div>