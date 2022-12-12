<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>SANDOM WEBSITE</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <!-- <link rel= "stylesheet" href="style.css"> -->
    
  </head>
  <body>
    <style>
      body {
        background-image: url('https://getwallpapers.com/wallpaper/full/e/7/3/104252.jpg');
      }
      </style>
      <link href='https://fonts.googleapis.com/css?family=Josefin+Sans' rel='stylesheet' type='text/css'>
    <h1>
      <em>S</em>
      <em class="planet left">A</em>
      <em>N</em>
      <em>D</em>
      <em>O</em>
      <em>M</em>
      <em class="planet right">A</em>
    </h1>
    </h1>

    <nav class="navbar navbar-expand-lg bg-light">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Weather Forecasting Website</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a> <!--href="#" is used when we want the user to return to the same page-->
              </li>
              

            </ul>
            <form class="d-flex" role="search">
              <input id ="city" class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit" id = "submit">Search for city</button>
            </form>
          </div>
        </div>
      </nav>
      <div class="container">
        <h1 class = "my-4 text-center " style="color:Floralwhite">
          Weather Forecast for <span id="cityName"></span></h1>
        <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
            <div class="col">
              <div class="card mb-4 rounded-3 shadow-sm">
                <div class="card-header py-3">
                  <h4 class="my-0 fw-normal">Temprature</h4>
                </div>
                <div class="card-body">
                  <h1 class="card-title pricing-card-title"><span id ="temp2"></span><small class="text-muted fw-light"><span>&#8451;</span></small></h1>
                  <ul class="list-unstyled mt-3 mb-4">
                    <li>Temprature is <span id = "temp"></span></li>
                    <li>Min Temprature is <span id ="min_temp"></span></li>
                    <li>Max Temprature is <span id ="max_temp"></span></li>
                    
                  </ul>
                  
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card mb-4 rounded-3 shadow-sm">
                <div class="card-header py-3">
                  <h4 class="my-0 fw-normal">Humidity Info </h4>
                </div>
                <div class="card-body">
                  <h1 class="card-title pricing-card-title"><span id ="humidity2"></span><small class="text-muted fw-light"> %</small></h1>
                  <ul class="list-unstyled mt-3 mb-4">
                    <li>Cloud PCT <span id="cloud_pct"></span></li>
                    <li>Feels Like <span id="feels_like"></span></li>
                  <li>Humidity <span id="humidity"></span></li>
                  </ul>
                  <button type="button" class="w-100 btn btn-lg btn-primary">Get started</button>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card mb-4 rounded-3 shadow-sm border-primary">
                <div class="card-header py-3 text-bg-primary border-primary">
                  <h4 class="my-0 fw-normal">WIND AND SUN CONDITIONS</h4>
                </div>
                <div class="card-body">
                  <h1 class="card-title pricing-card-title"><span id="wind_speed2"></span><small class="text-muted fw-light"> Km/hr</small></h1>
                  <ul class="list-unstyled mt-3 mb-4">
                    <li>Wind Degrees <span id="wind_degrees"></span></li>
                    <li>Wind Speed <span id="wind_speed"></span></li>
                    <li>Sunrise Timing <span id="sunrise"></span></li>
                    <li>Sunset Timing <span id="sunset"></span></li>
                  </ul>
                  <button type="button" class="w-100 btn btn-lg btn-primary">Contact us</button>
                </div>
              </div>
            </div>
          </div>
      </div>
      <!-- <div class="container">
      <h2 class="display-6 text-center mb-4">Some Common Cities Weather</h2>
      <div class="table-responsive">
        <table class="table text-center">
          <thead>
            <tr>
              <th style="width: 34%;"></th>
              <th style="width: 22%;">Cloud_pct    </th>
              <th style="width: 22%;">Feels_like   </th>
              <th style="width: 22%;">Humidity     </th>
              <th style="width: 22%;">Max_temp     </th>
              <th style="width: 22%;">Min_temp     </th>
              <th style="width: 22%;">Sunrise      </th>
              <th style="width: 22%;">Sunset       </th>
              <th style="width: 22%;">Temp         </th>
              <th style="width: 22%;">Wind_degrees </th>
              <th style="width: 22%;">Wind_speed   </th>
              
              
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row" class="text-start">Delhi</th>
              <td>1</td>
              <td>2</td>
              <td>3</td>
              <td>4</td>
              <td>5</td>
              <td>6</td>
              <td>7</td>
              <td>8</td>
              <td>9</td>
              <td>10</td>
            </tr>
            <tr>
              <th scope="row" class="text-start">Private</th>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              
            </tr>
          </tbody>
  
          <tbody>
            <tr>
              <th scope="row" class="text-start">Permissions</th>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
            </tr>
            <tr>
              <th scope="row" class="text-start">Sharing</th>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
            </tr>
            <tr>
              <th scope="row" class="text-start">Unlimited members</th>
             
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
            </tr>
            <tr>
              <th scope="row" class="text-start">Extra security</th>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
            </tr>
          </tbody>
        </table>
      </div>

      </div> -->

      
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
    <script src="script.js"></script>
  </body>
</html>
