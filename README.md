# Ex03 Places Around Me
## Date:29/11/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
<head>
<title>My City</title>
</head>
<body>
    <h2 align="center" textcolor="blue">Tiruvannamalai-TVM City</h2>
    <br></br>
    <h4 align="center" textcolor="yellow">Anuranjan B (25003110)</h4>
    <br>
    <img src="Screenshot 2025-11-28 112640.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Annamalaiyar temple" title="Annamalaiyar temple" href="temple.html" coords="826,475,1018,531" shape="rect">
    <area target="" alt="RR Residency" title="RR Residency" href="residency.html" coords="1173,289,84" shape="circle">
    <area target="" alt="Annamalaiyar hill" title="Annamalaiyar hill" href="hill.html" coords="809,226,963,282,892,312,737,317,715,243" shape="poly">
    <area target="" alt="Ramraj Cotton" title="Ramraj Cotton" href="ramraj.html" coords="1106,470,72" shape="circle">
    <area target="" alt="Varuna lingam" title="Varuna lingam" href="lingam.html" coords="204,31,347,92,212,161,81,137,39,50,98,24,153,6,157,21" shape="poly">
</map>
</body>



</html>

<html>
<head>
<title>Annamalaiyar Temple</title>
</head>
<body bgcolor="red">
    <h2 align="center" textcolor="blue">Tiruvannamalai-TVM City</h2>
    <h4 align="center" textcolor="yellow">Annamalaiyar Temple</h4>
    <hr>
    <p>
        The Annamalaiyar Temple's speciality is its connection to the Pancha Bhoota Sthalas, representing the element of fire (Agni). It is located at the base of the sacred Arunachala hill, which is considered a physical manifestation of Shiva. Key features include its massive size, stunning Dravidian architecture with several gopurams, and the annual Karthigai Deepam festival, where a giant lamp is lit atop the hill.  
    </p>
    </body>
    </html

<html>
<head>
<title>RR Residency</title>
</head>
<body bgcolor="green">
    <h2 align="center" textcolor="blue">Tiruvannamalai-TVM City</h2>
    <h4 align="center" textcolor="yellow">RR Residency</h4>
    <hr>
    <p>Hotel RR Residency is a prominent luxury hotel in Tiruvannamalai, known for its exceptional services and modern facilities. With a focus on providing luxurious comfort, the hotel offers intuitive technology and personalized service to its guests.</p>
    </body>
    </html>

<html>
<head>
<title>Ramraj Cotton</title>
</head>
<body bgcolor="yellow">
    <h2 align="center" textcolor="blue">Tiruvannamalai-TVM City</h2>
    <h4 align="center" textcolor="yellow">Ramraj Cotton</h4>
    <hr>
    <p>
        Ramraj Cotton is an Indian ethnic wear brand founded in 1983 by K.R. Nagarajan in Tirupur, Tamil Nadu, that specializes in high-quality men's cotton and silk garments, particularly dhotis. The company is known for pioneering the branding of dhotis, introducing a wide range of varieties, and using innovative marketing strategies to popularize traditional Indian wear.
    </p>
</body>
</html>

<html>
<head>
<title>Varuna Lingam</title>
</head>
<body bgcolor="grey">
    <h2 align="center" textcolor="blue">Tiruvannamalai-TVM City</h2>
    <h4 align="center" textcolor="yellow">Varuna Lingam</h4>
    <hr>
    <p>
        The Varuna lingam is situated on the outer girivalam pathway about one kilometre before the village of Adi Annamalai and has the west as its direction. Varuna's vehicle is Makara (that lives both on land and water) and is an animal with the head and front legs of an antelope and the body and tail of a fish.
    </p>
    </body>
    </html>

<html>
<head>
<title>Annamalaiyar Hill</title>
</head>
<body bgcolor="blue">
    <h2 align="center" textcolor="blue">Tiruvannamalai-TVM City</h2>
    <h4 align="center" textcolor="yellow">Annamalaiyar Hill</h4>
    <br>
    <hr>
    <br>
    <p>
        Annamalaiyar hill, also known as Arunachala, is a sacred mountain in Tiruvannamalai, Tamil Nadu, considered a representation of Lord Shiva. It is one of the five main Shaivite holy places in South India and is famous for the Arunachaleswara Temple at its base.
    </p>
    </body>
    </html>


```

## OUTPUT
![alt text](<Screenshot 2025-11-29 104033.png>)
![alt text](<Screenshot 2025-11-29 104217.png>)
![alt text](<Screenshot 2025-11-29 105506.png>)
![alt text](<Screenshot 2025-11-29 104155.png>)
![alt text](<Screenshot 2025-11-29 104245.png>)
![alt text](<Screenshot 2025-11-29 104116.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
