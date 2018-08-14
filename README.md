# xavierthi.github.io-Weather_Website<!doctype html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <link rel="stylesheet" type="text/css" href="styles.css">


</head>

<body>
  <nav class="navbar navbar-expand-md navbar-light border border-bottom" style="padding-top: 0px; padding-bottom: 0px;">
    <a class="navbar-brand" href="index.html"><h3>Lattitude</h3></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Plots
        </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="temperature.html">Temperature</a>
            <a class="dropdown-item" href="humidity.html">Humidity</a>
            <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
            <a class="dropdown-item" href="windspeed.html">Wind Speed</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="comparison.html">Comparison</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="data.html">Data</a>
        </li>
      </ul>
    </div>
  </nav>
  <br>

  <!--  Start page content  -->

  <div class="container">
      <div class="col-md-12">
          <div class="sigline">
              <p>
                  Thiago Xavier: University of Denver| Data Analytics Boot Camp
              </p>
          </div>
      </div>
  </div>
      

  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <div class="card">
          <h5 class="card-header">Summary: Latitude vs X</h5>
          <div class="card-body">
            <img src='Resources/assets/images/Fig1.png' class='float-left' width='40%'>
            <p class="card-text">The purpose of this project was to analyze how weather changes as you get closer to the equator. To accomplish this analysis, we first pulled data from the OpenWeatherMap API to assemble a dataset on over 500 cities.</p>
            <p class="card-text">After Assembling the dataset, we used Matplotlib to plot various aspects of the weather vs latitude. Factors we looked at included: temperature, cloudiness, wind speed and humidity. This site provides the source data and visualizations created
              as part of the analysis, as well as explanations and descriptions of any trends and correlations witnessed.</p>
          </div>
        </div>
      </div>
      <div class="col-md-5">
        <div class="card">
          <h5 class="card-header">Visualizations</h5>
          <div class="card-body" align='center'>
            <a href='temperature.html'>
            <img src='Resources/assets/images/Fig1.png' width='40%'>
          </a>
            <a href='humidity.html'>
            <img src='Resources/assets/images/Fig2.png' width='40%'>
            </a>
            <a href='cloudiness.html'>
            <img src='Resources/assets/images/Fig3.png' width='40%'>
            </a>
            <a href='windspeed.html'>
            <img src='Resources/assets/images/Fig4.png' width='40%'>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>

  <nav class="navbar fixed-bottom border border-top" styles='border-top: 2px solid teal; border: 2px'>
    <div class="mx-auto">
      &copy; Copyright Thiago Xavier
    </div>
  </nav>

  <!-- JavaScript -->
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>

</html>
