# Weather-App
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="weather.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="card">
<div class="search">
    <input type="text" placeholder="Enter city name" spellcheck="false">
    <button><i class="fa-solid fa-magnifying-glass"></i></button>
</div>
<div class="weather">
  <img src="rain.png" class="weather-icon">
    <h1 class="temp">22°C</h1>
    <h2 class="city">New York</h2>
    <div class="details">
        <div class="col">
            <img src="humidity.png">
        <div class="in"> 
            <p class="humidity">50% </p>
            <p>Humidity</p>
        </div>
        </div>
        <div class="col">
            <img src="wind.png">
        <div class="in"> 
            <p class="wind">15 Km/Hr </p>
            <p>Wind</p>
        </div>
        </div>
    </div>
</div>
    </div>
    <script src="weather.js"></script>
</body>
</html>
