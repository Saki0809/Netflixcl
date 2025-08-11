<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
    <link rel="icon" href="Netflix.jpg" type="image/x-icon">

    <style>
        body {

            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url(https://dnm.nflximg.net/api/v6/BvVbc2Wxr2w6QuoANoSpJKEIWjQ/AAAAQdHbjrX0uL1mH7uUW7VZ-p5GJOSNNRko_9A_12Mlv5wVYQIDy4nuupxLHxkDj9V0e1OLBs_s8ZlxFkyhPlK5XkrlTK0c7yP42LLinQdYhz8lqfgUcOH68JAbEcY45jG02gCI1NyKVf1lqxsQFmcNN5szbv8.jpg?r=aee);
        }

        #movie {
            text-align: center;
            font-family: Arial, sans-serif;
            box-shadow: 0 2px 5px rgba(94, 78, 78, 0.1);
        }
    </style>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-LN+7fdVzj6u52u30Kp6M/trliBMCMKTyK833zpbD+pXdCLuTusPj697FH4R/5mcr" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ndDqU0Gzau9qJ1lfW4pNLlhNTkCfHzAVBReH9diLvGRem5+R9g2FzA8ZGN954O5Q"
        crossorigin="anonymous"></script>




</head>

<body>
    <header>
        <h1 style="color:red; display: inline-block;">Netflix</h1>

        <nav style="margin:20px ; display: inline-block; float: right; padding-left:50px; padding-bottom:50px">
            <a href="index.html"
                style="color: white; text-decoration: none;font-weight: bold; margin-right: 20px;">Home</a>
            <a href="about.html"
                style="color: white; text-decoration: none; font-weight: bold; margin-right: 20px;">About</a>
            <a href="contact.html" style="color: white; text-decoration: none;font-weight: bold; ">Contact</a>
        </nav>
    </header>


    <br>
    <div>
        <div style="text-align: center; margin-top: 20px; align-items: center;">
            <div class="content">
                <input type="search" placeholder="Search for movies or shows..."
                    style="padding: 10px; width: 300px; border-radius: 5px; border: none; background-color: #333; color:white;">
            </div>
        </div>
    </div>


    <h2 style="text-align: center; color: white; margin-top: 20px;">Welcome to Netflix</h2>
    <div>
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://m.media-amazon.com/images/M/MV5BMDczOWE3N2QtMmE1Ni00Yjk4LWI4Y2YtM2YwMmY0YTczY2M0XkEyXkFqcGc@._V1_.jpg"
                        class="d-block w-100" alt="kingdom" style="width:auto; height:500px">
                </div>
                <div class="carousel-item">
                    <img src="https://m.media-amazon.com/images/M/MV5BOGMwZGJiM2EtMzEwZC00YTYzLWIxNzYtMmJmZWNlZjgxZTMwXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg"
                        class="d-block w-100" alt="superman" style="width:auto; height:500px">
                </div>
                <div class="carousel-item">
                    <img src="https://m.media-amazon.com/images/M/MV5BOGM5MzA3MDAtYmEwMi00ZDNiLTg4MDgtMTZjOTc0ZGMyNTIwXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg"
                        class="d-block w-100" alt="Fantastic Four" style="width:auto; height:500px">
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </div>



    <h2 style="color: white; text-align: center; margin-top: 40px;">Fan Favorites</h2>
    <div class="d-flex flex-row justify-content-center" style="margin-top: 20px;">
        <div id="movie" style="display: flex; flex-wrap: wrap; justify-content: center;margin: 20px">
            <img src="https://m.media-amazon.com/images/M/MV5BMDczOWE3N2QtMmE1Ni00Yjk4LWI4Y2YtM2YwMmY0YTczY2M0XkEyXkFqcGc@._V1_.jpg"
                alt="Kingdom" style="width: 200px; height: 300px; object-fit: cover; margin: 15px; border-radius: 5px;">
            <img src="https://m.media-amazon.com/images/M/MV5BOGMwZGJiM2EtMzEwZC00YTYzLWIxNzYtMmJmZWNlZjgxZTMwXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg"
                alt="Superman"
                style="width: 200px; height: 300px; object-fit: cover; margin: 15px; border-radius: 5px;">
            <img src="https://m.media-amazon.com/images/M/MV5BOWMzODc4ZjktNzZmZS00Nzg0LWIyMDUtM2ZkOTZkODk5NTRiXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg"
                alt="Coolie" style="width: 200px; height: 300px; object-fit: cover; margin: 15px; border-radius: 5px;">
            <img src="https://m.media-amazon.com/images/M/MV5BOWRiOThkM2YtYzI4NS00OWViLTk0ODMtMjNlNDYyZWQ3MzNjXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg"
                alt="F1" style="width: 200px; height: 300px; object-fit: cover; margin: 15px; border-radius: 5px;">
            <img src="https://m.media-amazon.com/images/M/MV5BNjY5OTg4NTYtZjVkZS00YTZmLWIwNDEtM2Y0ODQyMzM2NTJiXkEyXkFqcGc@._V1_.jpg"
                alt="War 2" style="width: 200px; height: 300px; object-fit: cover; margin: 15px; border-radius: 5px;">
            <img src="https://m.media-amazon.com/images/M/MV5BOGM5MzA3MDAtYmEwMi00ZDNiLTg4MDgtMTZjOTc0ZGMyNTIwXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg"
                alt="Fantastic Four"
                style="width: 200px; height: 300px; object-fit: cover; margin:15px; border-radius: 5px;">
        </div>

    </div>







</body>

</html>
