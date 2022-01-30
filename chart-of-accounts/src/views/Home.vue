<template>
  <div class="home">
    <div class="container my-5">
      <div class="row justify-content-between">
        <div class="col-md-4">
          <h1>Chart of accounts</h1>
        </div>
        <div class="col-md-4 ">
          <button class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#staticBackdrop">Add a New Account </button>
        </div>
        <!-- Modal -->
          <div class="modal fade" id="staticBackdrop" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
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
          </div>
      </div>
    <p>
      <button class="btn btn-colapse" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Assets <span class="span_style">10</span>
      </button>
      <button class="btn btn-colapse" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Liabilities & Credit Cards <span class="span_style">5</span>
      </button>
      <button class="btn btn-colapse" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Income <span class="span_style">3</span>
      </button>
      <button class="btn btn-colapse" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Expenses <span class="span_style">29</span>
      </button>
      <button class="btn btn-colapse" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Equity <span class="span_style">2</span>
      </button>
      
    </p>
    <hr>
      <div class="collapse in show" id="collapseExample">
        <div class="card card-body">
          <h4 class="text-dark nClass">
            Cash and Bank 
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-question-circle" viewBox="0 0 16 16">
              <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
              <path d="M5.255 5.786a.237.237 0 0 0 .241.247h.825c.138 0 .248-.113.266-.25.09-.656.54-1.134 1.342-1.134.686 0 1.314.343 1.314 1.168 0 .635-.374.927-.965 1.371-.673.489-1.206 1.06-1.168 1.987l.003.217a.25.25 0 0 0 .25.246h.811a.25.25 0 0 0 .25-.25v-.105c0-.718.273-.927 1.01-1.486.609-.463 1.244-.977 1.244-2.056 0-1.511-1.276-2.241-2.673-2.241-1.267 0-2.655.59-2.75 2.286zm1.557 5.763c0 .533.425.927 1.01.927.609 0 1.028-.394 1.028-.927 0-.552-.42-.94-1.029-.94-.584 0-1.009.388-1.009.94z"/>
            </svg>
          </h4>
         <table class="table table-hover">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">First</th>
            <th scope="col">Last</th>
            <th scope="col">Handle</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Mark</td>
            <td>Otto</td>
            <td>@mdo</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>Jacob</td>
            <td>Thornton</td>
            <td>@fat</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td colspan="2">Larry the Bird</td>
            <td>@twitter</td>
          </tr>
        </tbody>
</table>
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
<style scoped>
.span_style{
  background-color: #E0E7EB;
  padding: 7px;
  border-radius: 50px 50px 50px 50px;
}
.nClass{
  background-color: #E0E7EB;
}
.btn-colapse{
  padding-right: 30px;
  font-size: 20px;
}
.btn-colapse:hover{
  border-bottom: 5px solid #E0E7EB;
}
</style>
