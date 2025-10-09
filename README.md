# Ex04 Places Around Me
# Date:10.07.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
``` 
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Vadalur</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>NITHIN KAVI A R (25016374)</b></font>
        </h3>
        <center>
            <img src="city.png" usemap="#mycity" alt="map" height="610" width="1450">
            
            <map name="mycity">
                
                <area shape="rect" coords="1150,520,1190,550" href="krishnabhavan.html" title="Krishna Bhavan Hotel (KBH), Vadalur">

                
                <area shape="rect" coords="850,450,890,480" href="merrytale.html" title="Hotel Merrytale, Vadalur">

                
                <area shape="rect" coords="780,550,820,580" href="sudha.html" title="Sudha Hospital, Vadalur">

                <area shape="rect" coords="300,360,340,390" href="periyandavar.html" title="Periyandavar Temple, Kallukuzhi">
            </map>
        </center>
    </body>
</html>

krishna hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vadalur - Krishna Bhavan Hotel</title>
   
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
    <style>
    
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background: linear-gradient(to right, #bee6f8, #d0e1f9);
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 80px auto;
            padding: 40px;
            background-color: #b0faff;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .container:hover {
            transform: scale(1.01);
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3em;
            color: #fa05c5; 
            margin-bottom: 10px;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2em;
            color: #164902; 
            margin-bottom: 25px;
        }

        p {
            font-size: 1.15em;
            color: #000000;
            max-width: 750px;
            margin: 0 auto;
            text-align: justify;
        }

        @media (max-width: 600px) {
            .container {
                margin: 40px 20px;
                padding: 25px;
            }

            h1 {
                font-size: 2.2em;
            }

            h2 {
                font-size: 1.6em;
            }

            p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Vadalur</h1>
        <h2>Krishna Bhavan Hotel (KBH)</h2>
        <p>
            Krishna Bhavan Hotel is one of the most popular vegetarian restaurants in Vadalur. 
            Known for its clean environment, quick service, and authentic South Indian dishes, 
            it's a favorite among locals and travelers alike. Located in the heart of the town, 
            the hotel serves a variety of dosas, idlis, meals, and sweets at affordable prices. 
            With its warm hospitality and consistent taste, Krishna Bhavan continues to uphold 
            its reputation as a go-to destination for delicious vegetarian food.
        </p>
    </div>
</body>
</html>

Merrytale.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vadalur - Krishna Bhavan Hotel</title>
   
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
    <style>
    
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background: linear-gradient(to right, #bee6f8, #d0e1f9);
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 80px auto;
            padding: 40px;
            background-color: #b0faff;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .container:hover {
            transform: scale(1.01);
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3em;
            color: #fa05c5; 
            margin-bottom: 10px;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2em;
            color: #164902; 
            margin-bottom: 25px;
        }

        p {
            font-size: 1.15em;
            color: #000000;
            max-width: 750px;
            margin: 0 auto;
            text-align: justify;
        }

        @media (max-width: 600px) {
            .container {
                margin: 40px 20px;
                padding: 25px;
            }

            h1 {
                font-size: 2.2em;
            }

            h2 {
                font-size: 1.6em;
            }

            p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Vadalur</h1>
        <h2>Hotel Merrytale</h2>
        <p>
            Hotel Merrytale is a cozy and modern lodging facility located in Vadalur. 
                It offers comfortable rooms with basic amenities, ideal for both business travelers 
                and families. The hotel is known for its friendly staff and its proximity to local 
                transport and landmarks. A small restaurant attached to the hotel serves quality food.
    </div>
</body>
</html>

Sudha Hospital.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vadalur - Krishna Bhavan Hotel</title>
   
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
    <style>
    
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background: linear-gradient(to right, #bee6f8, #d0e1f9);
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 80px auto;
            padding: 40px;
            background-color: #b0faff;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .container:hover {
            transform: scale(1.01);
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3em;
            color: #fa05c5; 
            margin-bottom: 10px;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2em;
            color: #164902; 
            margin-bottom: 25px;
        }

        p {
            font-size: 1.15em;
            color: #000000;
            max-width: 750px;
            margin: 0 auto;
            text-align: justify;
        }

        @media (max-width: 600px) {
            .container {
                margin: 40px 20px;
                padding: 25px;
            }

            h1 {
                font-size: 2.2em;
            }

            h2 {
                font-size: 1.6em;
            }

            p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Vadalur</h1>
        <h2>Sudha Hospital</h2>
        <p>
            Sudha Hospital is a multi-specialty healthcare center serving the residents of Vadalur 
                and nearby areas. It provides quality medical services with departments such as General Medicine, 
                Pediatrics, and Obstetrics. With experienced doctors and modern facilities, 
                Sudha Hospital ensures round-the-clock emergency care and patient support.
    </div>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vadalur - Krishna Bhavan Hotel</title>
   
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
    <style>
    
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background: linear-gradient(to right, #bee6f8, #d0e1f9);
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 80px auto;
            padding: 40px;
            background-color: #b0faff;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .container:hover {
            transform: scale(1.01);
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3em;
            color: #fa05c5; 
            margin-bottom: 10px;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2em;
            color: #164902; 
            margin-bottom: 25px;
        }

        p {
            font-size: 1.15em;
            color: #000000;
            max-width: 750px;
            margin: 0 auto;
            text-align: justify;
        }

        @media (max-width: 600px) {
            .container {
                margin: 40px 20px;
                padding: 25px;
            }

            h1 {
                font-size: 2.2em;
            }

            h2 {
                font-size: 1.6em;
            }

            p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Vadalur</h1>
        <h2>Periyandavar Temple</h2>
        <p>
             Periyandavar Temple, located in Kallukuzhi near Vadalur, is a revered place of worship 
                dedicated to the village deity, Periyandavar. This temple holds cultural significance 
                and hosts local festivals annually, attracting devotees from the surrounding villages. 
                It is a spiritual center for many and plays a vital role in preserving the local traditions.
    </div>
</body>
</html>

```
# OUTPUT
![alt text](<Screenshot 2025-10-09 095750.png>)
![alt text](<Screenshot 2025-10-09 102316.png>)
![alt text](<Screenshot 2025-10-09 102705.png>)
![alt text](<Screenshot 2025-10-09 102754.png>)
![alt text](<Screenshot 2025-10-09 102918.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
