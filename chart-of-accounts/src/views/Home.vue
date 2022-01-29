<template>
  <div class="home">
    <div class="container">
      <h1>Chart of accounts</h1>
    <p>
      <button class="btn" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Assets
      </button>
      <button class="btn" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Liabilities & Credit Cards
      </button>
      <button class="btn" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Income
      </button>
      <button class="btn" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Expenses
      </button>
      <button class="btn" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Equity
      </button>
      
    </p>
      <div class="collapse" id="collapseExample">
        <div class="card card-body">
          Some placeholder content for the collapse component. This panel is hidden by default but revealed when the user activates the relevant trigger.
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {
    
  }
}
</script>
