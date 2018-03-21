<?php 


    $weather = "";
    $error = "";

    if ($_GET['city']){
        
            
            $urlContents = 
       file_get_contents("http://api.openweathermap.org/data/2.5/weather?q=".$_GET['city']."&appid=cd7abd63e8c28a10b1c49ac67f04419d");
        
        $weatherArray= json_decode($urlContents, true);
        
        if($weatherArray['cod'] == 200){
        
        $weather = "The weather in ".$_GET['city']." is currently ".$weatherArray['weather'][0]['main']." or, ya know,  ".$weatherArray['weather'][0]['description']."... Dude, if this is where you are, get inside!";
        
        $tempInCelcius = round($weatherArray['main']['temp'] - 273);
        $tempInFar = round($tempInCelcius * 1.8 + 32);
        $wind = round($weatherArray['wind']['speed'] * 2.2369);
        
        $weather .= " The temperature is ".$tempInCelcius."&deg; C! That's like ".$tempInFar."&deg; F in american! Not only that, the wind speed is ".$wind."MPH!";
        
    } else {
         $error = "Uhh, where did you look for? Maybe try the next town over..";
    }
    }
?>

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <link href="https://fonts.googleapis.com/css?family=Bungee+Inline|Josefin+Sans" rel="stylesheet">
      
    <title>Weather Scraper</title>
      
      <style type="text/css">
      
          html{
              background: url("https://images.pexels.com/photos/417122/pexels-photo-417122.jpeg?w=1260&h=750&auto=compress&cs=tinysrgb")no-repeat center center fixed;
              -webkit-background-size: cover;
              -moz-background-size: cover;
              background-size: cover;    
          }
          
          Body{
              background:none;
          }
          
          input{
              margin: 20px 0 20px 0;
          }
          
          .container{
              text-align: center;
              margin-top: 100px;
              max-width: 550px;
          }
          
          .title{
              color: beige;
              font-family: 'Bungee Inline', cursive;

          }
      </style>
            
      
  </head>
  <body>
      
    <div class="container">
        <h1 class="title">What's the weather?</h1>
        
        
        <form>
          <div class="form-group">
            <label for="city" class="title">Enter the name of a city</label>
            <input type="text" class="form-control" id="city" name= "city" placeholder="Eg. Boston" value="<?php 
                                                                                                           
                    if (array_key_exists('city', $_GET)){                                                                                                                                        
                    echo $_GET['city'];
            
          }  
          ?> ">    
          </div>
            
          <div id="weather"><?php 
               
              if ($weather){
                  echo '<div class="alert alert-secondary" role="alert">'.$weather.'</div>';
                
              } else if ($error) {
                  
                  echo '<div class="alert alert-danger" role="alert">'.$error.'</div>';
              }
              ?>
              </div>    
          <button type="submit" class="btn btn-info btn-lg">Submit</button>
        </form>
        
    </div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
