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

Krishna hotel.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Vadalur</b></font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Krishna Bhavan Hotel (KBH)</b></font>
        </h2>
        <p align="center">
            <font>
                Krishna Bhavan Hotel is one of the most popular vegetarian restaurants in Vadalur. 
                Known for its clean environment, quick service, and authentic South Indian dishes, 
                it's a favorite among locals and travelers alike. Located in the heart of the town, 
                the hotel serves a variety of dosas, idlis, meals, and sweets at affordable prices.
            </font>
        </p>
    </body>
</html>


Hotel Merrytale.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Vadalur</b></font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Hotel Merrytale</b></font>
        </h2>
        <p align="center">
            <font>
                Hotel Merrytale is a cozy and modern lodging facility located in Vadalur. 
                It offers comfortable rooms with basic amenities, ideal for both business travelers 
                and families. The hotel is known for its friendly staff and its proximity to local 
                transport and landmarks. A small restaurant attached to the hotel serves quality food.
            </font>
        </p>
    </body>
</html>

Sudha Hospital.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Vadalur</b></font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Sudha Hospital</b></font>
        </h2>
        <p align="center">
            <font>
                Sudha Hospital is a multi-specialty healthcare center serving the residents of Vadalur 
                and nearby areas. It provides quality medical services with departments such as General Medicine, 
                Pediatrics, and Obstetrics. With experienced doctors and modern facilities, 
                Sudha Hospital ensures round-the-clock emergency care and patient support.
            </font>
        </p>
    </body>
</html>


Periyandavar Temple.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Kallukuzhi</b></font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Periyandavar Temple</b></font>
        </h2>
        <p align="center">
            <font>
                Periyandavar Temple, located in Kallukuzhi near Vadalur, is a revered place of worship 
                dedicated to the village deity, Periyandavar. This temple holds cultural significance 
                and hosts local festivals annually, attracting devotees from the surrounding villages. 
                It is a spiritual center for many and plays a vital role in preserving the local traditions.
            </font>
        </p>
    </body>
</html>

```

# OUTPUT
![alt text](<Screenshot 2025-10-07 223334.png>)
![alt text](<Screenshot 2025-10-07 223428.png>)
![alt text](<Screenshot 2025-10-07 223541.png>)
![alt text](<Screenshot 2025-10-07 223625.png>)
![alt text](<Screenshot 2025-10-07 222224.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
