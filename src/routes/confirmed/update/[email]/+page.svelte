<script>
  // @ts-nocheck
  /** @type {import('./$types').PageData} */
  export let data;
</script>

<div class="hero is-fullheight">
  <div class="hero-body is-flex is-flex-direction-column is-justify-content-center is-align-items-center">
    <!-- logo -->
    <div class="image is-96x96">
      <img class="is-rounded" src="/checkIcon2.png" alt="Hain.co logo">
    </div>

    <!-- title -->
    <div class="lobster is-size-1-desktop is-size-3-touch has-text-success has-text-centered">
      Email Updated!
    </div>

    <!-- subtitle -->
    <div class="mb-6 karla is-size-6-tablet is-size-7-mobile has-text-centered">
      Your new email is {data.email}
    </div>

    <div class="button is-rounded is-success has-text-white mt-6 is-large is-responsive karla">
      Download App
    </div>
  </div>
</div>