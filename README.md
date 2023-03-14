# email
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Email</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"  integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link href="style.css" rel="stylesheet">
</head>
<body>
    <div class="container">
        <div class="row w-100">
         <!--1st column-->
            <div class="col-sm-12 col-md-4 col-lg-3">
                
                <button type="button" class="btn btn-info">Compose</button>
                <!--list buttons-->
                <ul class="list-group list-group-flush">
                    <li class="list-group-item active" >Inbox</li>
                    <li class="list-group-item active">Sent</li>
                    <li class="list-group-item active">Draft</li>
                    <li class="list-group-item active">Junk</li>
                </ul>
                
            </div>
        
         <!--2nd column-->
            <div class="col-sm-12 col-md-8 col-lg-3">
           
                <!--search bar-->
            <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
              </form>
              <!--1st email-->
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title">edX Team</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Integrate optimized AI skills into....</h6>
                  <p class="card-text">Advance in your tech career. Push the boundaries.......</p>
                </div>
              </div>
              <!--2nd email-->
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title">Ray-Ban</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Cut to spring</h6>
                  <p class="card-text">Fresh styles trending now</p>
                </div>
              </div>
              <!--3rd email-->
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title">Uber Eats</h5>
                  <h6 class="card-subtitle mb-2 text-muted">See inside to grab your savings</h6>
                  <p class="card-text">Restaurants offers too good to miss. servings Fresh deals for you to spend $30, save $5........</p>
                </div>
              </div>
            
            </div>
           
         <!--3rd column-->
            <div class="col-sm-12 col-md-12 col-lg-6">
                <h1><strong>edX Team</strong> </h1>
                <h2>To: Shezah Jhendar</h2>
                <h3><strong>Integrate optimized AI skills into your resume</strong></h3>
                <p>Explore high-caliber courses and programs design to enhance your skills in dynamics tech industries across the globe. leverage technical expertise to fuel your career in the competitive job market. </p>
                
                <!--reply box-->
                <div class="form-floating">
                    <textarea class="form-control" placeholder="Leave a reply here" id="floatingTextarea2" style="height: 100px"></textarea>
                    <label for="floatingTextarea2">reply here ....</label>
                  </div>
                  <!--reply button-->
                  <button type="button" class="btn btn-primary">Reply</button>

      
      
            </div>
        </div>
    </div>
    <!-- Include the Bootstrap JavaScript file -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>
