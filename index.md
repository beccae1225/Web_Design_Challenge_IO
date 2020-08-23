<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HMWK 11_Landing Page</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!---NAV BAR-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="Landing_page.html">Latitude HMWK 11</a>
      <button class="navbar-toggler ml-auto mr-1" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
    
      <div class="collapse navbar-collapse w-100 order-3 dual-collpase2" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="Comparisons.html">Comparisons <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Data.html">Data</a>
          </li>
          <div class="dropdown">  
            <a class="btn btn-secondary dropdown-toggle" href="#" role="button" id="dropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Plots
            </a>

            <div class="dropdown-menu dropdown-menu-right" aria-labelledby="dropdownMenuLink">
              <a class="dropdown-item" href="Viz_One.html">Visualization One</a>
              <a class="dropdown-item" href="Viz_Two.html">Visualization Two</a>
              <a class="dropdown-item" href="Viz_Three.html">Visualization Three</a>
              <a class="dropdown-item" href="Viz_Four.html">Visualization Four</a>
            </div>
        </ul>
      </div>
  </nav>
        
  
    <!---END NAV-->

      <!---MAIN CONTAINER--->

      <div class = "container-fluid">
          <div class = "row"></div>
          <div class = "row"> 
            <div class="col-sm-12 col-md-8">
                <div class="jumbotron light blue">
                    <h1 class="display-4">Summary: Latitude vs. X</h1>
                    <p class="lead">This project tasked us with the analyzation of weather changes the closer one gets to the equator.
                      The first step was to derive data from the OpenWeatherMap API to build our dataset of over 500 cities. </p>
                      <p class="lead"> </p>
                    <hr class="my-4">
                    <p class="lead"> The various comparisons of weather components vs. latitude were plotted wit Matplotlib. Weather components analyzed for 
                      the project include temperature, cloudiness, wind speed, and humidity. This website presents the data and accompanying visualiizations of 
                      analysis in addition to plot summaries and detected trends. 
                    </p>
                </div>
            </div>


            <div class="col-sm-12 col-md-4">
                <div class="card" style="width: 25rem">
                    <div class="card-body">
                        <h1 class="title">Plots</h1>
                    </div>
                    <div class="box">
                       <a href="Viz_one.html"><img src="../Visualizations/Fig1.png" alt="City Latitude vs. Max Temperature" height="160" width="160"></a>
                       <a href="Viz_Two.html"><img src="../Visualizations/Fig2.png" alt="City Latitude vs. Humidity" height="160" width="160"></a>
                       <a href="Viz_Three.html"><img src="../Visualizations/Fig3.png" alt="City Latitude vs. Cloudiness" height="160" width="160"></a>
                       <a href="Viz_Four.html"><img src="../Visualizations/Fig4.png" alt="City Latitude vs. Wind Speed" height="160" width="160"></a>
                    </div>
                </div>
            </div>
      </div>
    
</body>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</html>
