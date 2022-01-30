<template>
  <!-- Modal -->
  <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">Add an Account</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                  <form>
                      <label>Account Type</label>
                        <select class="form-select" aria-label="Default select example">
                          <option selected>Open this select menu</option>
                          <option value="1">One</option>
                          <option value="2">Two</option>
                          <option value="3">Three</option>
                      </select>
                      <label>Account Name</label>
                      <input type="text" class="form-control">
                      <label>Account ID</label>
                      <input type="number" class="form-control">
                      <label>Description</label>
                      <textarea class="form-control" cols="30" rows="5"></textarea>
                  </form>
                </div>
                <div class="modal-footer">
                  <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cancel</button>
                  <button type="button" class="btn btn-primary">Save</button>
                </div>
              </div>
            </div>
</template>

<script>
export default {

}
</script>

<style>

</style>