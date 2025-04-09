# Ex04 Places Around Me
# Date:09-04-2025
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
<html>
<head>
<title>MyCity</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="Red">HARISELVAN S (212224040103)</font>
</h3>
<center>
<img src="Map.png" usemap="#MyCity" hright="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="300,100,500,500"  href="home.html" title="My Home Town">
<area shape="rect" coords="600,600,300,300" href="temple.html" title="Golden Temple">
<area  shape="rect" coords="900,900,200,200" href="river.html" title="palaru">
<area  shape="rect" coords="1000,1000,100,100" href="fort.html" title="vellore Fort">
<!-- <area  shape="rect" coords="100,100,900,900" href="home.html" title="My Home Town"> -->
</map>
</center>
</body>
</html>


# home.html
<html>
    <head>
        <style>
            .co{
                color:red;
            }
            .para{
                color:white;
                font-family:"Robot";
            }
        </style>
    </head>
 <body bgcolor="blue" text-color:"red">
<h1 class="co">MY HOME TOWN</h1>
 <p class="para">Vellore is a historic city located in the southern Indian state of Tamil Nadu. Known for its rich cultural heritage and historical significance, Vellore is home to the majestic Vellore Fort, a 16th-century fort built by the Vijayanagara rulers, which stands as a symbol of the city's glorious past. The city is also an important educational and medical hub, housing renowned institutions like the Christian Medical College (CMC) and Vellore Institute of Technology (VIT), which attract students and patients from all over the country and abroad. Nestled along the Palar River, Vellore experiences a hot and dry climate, and its landscape is dotted with temples, churches, and mosques, reflecting its diverse cultural fabric. With a blend of tradition and modernity, Vellore continues to grow as a prominent city in Tamil Nadu.</p>
 </font>
 </body>
 </html>


# fort.html

<html>
    <head>
        <style>
            .co{
                color:red;
            }
            .para{
                color:white;
                font-family:"Robot";
            }
        </style>
    </head>
 <body bgcolor="blue" text-color:"red">
<h1 class="co">VELLORE FORT</h1>
 <p class="para">The Vellore Fort is a magnificent historical structure located in the heart of Vellore, Tamil Nadu. Built in the 16th century by the Vijayanagara kings, this fort is known for its grand granite walls, wide moat, and robust military architecture. It has witnessed several key historical events, including the Vellore Sepoy Mutiny of 1806, which was one of the earliest uprisings against British rule in India. The fort has been under the control of various dynasties, such as the Bijapur Sultans, Marathas, the Carnatic Nawabs, and eventually the British. One of the unique features of the Vellore Fort is that it houses a Hindu temple (Jalakanteswarar Temple), a church, and a mosque within its premises, showcasing religious harmony. The Jalakanteswarar Temple inside the fort is particularly famous for its exquisite carvings and Dravidian-style architecture. Today, the Vellore Fort is maintained by the Archaeological Survey of India and stands as a symbol of the city's rich cultural and historical heritage, attracting tourists and history enthusiasts from all over.</p>
 </font>
 </body>
 </html>

# temple.html

<html>
    <head>
        <style>
            .co{
                color:red;
            }
            .para{
                color:white;
                font-family:"Robot";
            }
        </style>
    </head>
 <body bgcolor="blue" text-color:"red">
<h1 class="co">GOLDEN TEMPLE</h1>
 <p class="para">The Golden Temple, also known as the Sripuram Golden Temple, is a spiritual park located in Thirumalaikodi, near Vellore in Tamil Nadu. It is dedicated to Goddess Lakshmi Narayani and is managed by the Sri Narayani Peedam led by Sri Sakthi Amma, a spiritual leader. The temple is renowned for its stunning architecture and intricate design, with the temple's Vimanam (tower) and Ardha Mandapam covered in pure gold foil, making it a unique and visually striking landmark. Spread across 100 acres of lush green land, the temple is not just a place of worship but also promotes values like peace, spirituality, and environmental consciousness. Pilgrims walk along a star-shaped path that stretches for over 1.8 kilometers to reach the sanctum, allowing for spiritual reflection. The Golden Temple has become a major tourist attraction and pilgrimage site, drawing thousands of visitors every day from across India and abroad..</p>
 </font>
 </body>
 </html>

# river.html

<html>
    <head>
        <style>
            .co{
                color:red;
            }
            .para{
                color:white;
                font-family:"Robot";
            }
        </style>
    </head>
 <body bgcolor="blue" text-color:"red">
<h1 class="co">PALARU RIVER</h1>
 <p class="para">The Palar River, originating from the Nandi Hills in Karnataka's Chikkaballapura district, traverses through Karnataka, Andhra Pradesh, and Tamil Nadu before emptying into the Bay of Bengal near Vayalur, south of Chennai. Covering a total length of approximately 357 kilometers, it flows for about 222 kilometers through Tamil Nadu, significantly impacting regions like Vellore. ​
    Encyclopedia Britannica
    +4
    Prepp
    +4
    Wikipedia
    +4
    Wikipedia – Die freie Enzyklopädie
    
    In the Vellore district, the Palar River has historically been a vital water source for agriculture and drinking purposes. However, in recent years, the river has faced challenges due to erratic water flow and environmental concerns. Notably, industrial activities, particularly from tanneries in Vellore, have led to significant pollution. The Supreme Court of India acknowledged in February 2025 that these tanneries caused "irreversible damage" to the water bodies, groundwater, and agricultural lands by discharging untreated or partially treated effluents into the Palar River. The court directed the Tamil Nadu government to compensate those affected and recover the costs from the polluting units. ​
    The Indian Express
    
    Efforts are underway to address these issues and restore the river's health. The Tamil Nadu Water Resources Department has planned the construction of six check dams across the Palar River, each estimated to cost ₹30 crore. These structures aim to improve water management and support the river's ecosystem. ​
    Wikipedia
    +2
    Aptinfo.in
    +2
    The Indian Express
    +2
    Encyclopedia Britannica
    +1
    Wikipedia, la enciclopedia libre
    +1
    
    Despite these challenges, the Palar River remains an integral part of Vellore's geography and history, influencing the region's development and sustaining its communities.</p>
 </font>
 </body>
 </html>

```
# OUTPUT
![alt text](<img 1.png>)
![alt text](<img 2.png>)
![alt text](<img 3.png>)
![alt text](<img 4.png>)
![alt text](<img 5.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
