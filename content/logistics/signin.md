# Sign In Form





<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

<form name="contact" method="POST" data-netlify="true">

  <div class="form-group">
    <label >First Name </label>
 <input type="Name" class="form-control"  name="firstName" placeholder="Enter First Name">   
  </div>
  <div class="form-group">
    <label > Last Name </label>
 <input type="Name" class="form-control"   name= "LastName" placeholder="Enter  Last Name">   
  </div>

  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" name="Email"  placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  


 <div class="form-check">
      <input class="form-check-input" type="checkbox" value=""  name= "check" id="invalidCheck" required>
      <label class="form-check-label" for="invalidCheck">
        My camera is on.
      </label>
      <div class="invalid-feedback">
        You must turn on your camera.
      </div>
    </div>

  <button type="submit" class="btn btn-primary">Submit</button>
</form>