# Ex04 Places Around Me
## Date: 21/04/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE


~~
map.html

<html>
<head>
    <title>My hometown</title>
</head>
<body>

    <h1 align="center">
        <font color="red"><b>Panjampatti</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>Harshini.V (212224040109)</b></font>
    </h3>
    <center>
        <img src="map.png.png" usemap="#My hometown">
        <map name="MyCity">
            <area shape="rect" coords="391,99,427,114" title="Garden" href="garden.html">
            <area shape="rect" coords="839,275,881,315" title="Temple" href="temple.html">
            <area shape="rect" coords="277,150,316,185" title="Post office" href="post office.html">
            <area shape="rect" coords="77,324,120,358" title="Fishing Pond" href="fishing pond.html">
            <area shape="rect" coords="965,394,1011,434" title="Farm" href="village hall.html">
        </map>
    </center>
</body>
</html>

temple.html
<html>
    <head>
        <title>Temple</title>
    </head>
    <body>
        <h1 align="center">TEMPLE</h1>
        <div align="center">
            <img src="Amman kovil.jpg.png" alt="Temple" width="500">
        </div>
    
        <p>There is also an Amman Temple nearby my neighbourhood. Nestled amidst a cluster of trees and modest homes, the Amman temple stands as a vibrant and sacred space, radiating spiritual energy and local tradition. Its colorful gopuram, adorned with intricate carvings of deities and mythological figures, rises proudly against the sky, guiding devotees to its gates.
            
        </p>

            
    </body>
</html>  

post office.html

<html>
    <head>
        <title>Post office</title>
    </head>
    <body>
        <h1 align="center">POST OFFICE</h1>
        <div align="center">
            <img src="post office.jpg.png" alt="Post office" width="500">
        </div>
    
        <p>The old post office stands with weathered walls and faded paint, its wooden sign barely legible after years of sun and rain. Cracks trace the surface of its stone steps, and the creaky doors groan with each visitor’s arrival. Inside, the counters are chipped and the ceiling fans spin lazily, their hum mixing with the rustle of paper and the steady clack of a timeworn typewriter.he clerks, familiar with every face and letter, move with practiced ease, sorting and stamping with care. Stacks of parcels come and go, and the daily rhythm continues without fail, a quiet reminder that function often outlives form.
            
        </p>

            
    </body>
</html>  

fishing pond.html

<html>
    <head>
        <title>Fishing Pond</title>
    </head>
    <body>
        <h1 align="center">FISHING POND</h1>
        <div align="center">
            <img src="fish pond.jpg.png" alt="Fishing pond" width="500">
        </div>
    
        <p> Tucked away at the edge of a quiet village, the little fishing pond rests like a hidden gem amid swaying grass and tall, whispering trees. Its calm waters reflect the sky above, occasionally rippling with the gentle splash of a fish or the dip of a dragonfly. Weathered wooden posts mark the spots where locals often sit, casting their lines with unhurried ease, sometimes more for peace than for the catch.
            
        </p>

            
    </body>
</html>  

garden.html

<html>
    <head>
        <title>Garden</title>
    </head>
    <body>
        <h1 align="center">GARDEN</h1>
        <div align="center">
            <img src="magardens.jpg.png" alt="Garden" width="500">
        </div>
    
        <p>
            The fruit garden is a vibrant, living space where nature flourishes in organized harmony. It thrives with carefully tended plants that change with the seasons, offering bursts of color, delicate blossoms, and the gentle hum of bees and butterflies. The air is often filled with a fresh, earthy scent, mingled with the soft rustle of leaves in the breeze. Carefully laid paths wind through rows of greenery, inviting quiet walks and peaceful reflection. With a balance of sunlight and shade, and the rhythmic routine of watering and pruning, the garden becomes a serene retreat—an ever-changing testament to patience, care, and the beauty of growth.
        </p>

            
    </body>
</html>  

village.html

<html>
    <head>
        <title>Village hall</title>
    </head>
    <body>
        <h1 align="center">VILLAGE HALL</h1>
        <div align="center">
            <img src="village hall.jpg.png" alt="Village hall" width="500">
        </div>
    
        <p>The small village hall stands at the heart of the community, modest in size but rich in purpose. Its whitewashed walls and sloping tiled roof hold decades of laughter, decisions, and celebrations. Inside, wooden benches line the room, and faded curtains flutter slightly in the breeze from open windows. Though humble, the hall is always alive—with weekend gatherings, festive dances, and the quiet hum of meetings that shape the village’s future. It’s a place where voices echo, memories are made, and the spirit of the village truly comes together. 
            
        </p>

            
    </body>
</html>  

~~~


## OUTPUT


![alt text](<Screenshot (115)-1.png>)

![alt text](<Screenshot (112).png>)

![alt text](<Screenshot (110).png>)

![alt text](<Screenshot (113).png>)

![alt text](<Screenshot (114).png>)

![alt text](<Screenshot (111).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
