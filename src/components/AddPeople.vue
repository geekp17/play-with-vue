<template>
  <div class="column">
    <section class="panel">
      <p class="panel-heading">
        Form Details
      </p>
      <div class="panel-block">
        <label class="label">First Name</label>
        <p class="control">
          <input class="input" type="text" placeholder="Text input">
        </p>

        <label class="label">Last Name</label>
        <p class="control">
          <input class="input" type="text" placeholder="Text input">
        </p>

        <label class="label">Phone Number</label>
        <p class="control">
          <input class="input" type="text" placeholder="Text input">
        </p>

        <label class="label">Email</label>
        <p class="control">
          <input class="input" type="text" placeholder="Text input">
        </p>

        <p class="control">
          <button class="button is-primary">Submit</button>
        </p>

      </div>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'add-people'
  }
</script>
