# Ex04 Places Around Me
# Date:07/10/2025
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
'''
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="magenta"><b>NEYVELI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>DHARUN DHANRAJ(25017737)</b></font>
</h3>
<center>
<map name="MyCity">
<img src="Screenshot 2025-10-06 092750.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="melappanapattu" title="melappanapattu" href="melp.html" coords="1034,520,1247,574" shape="rect">
    <area target="" alt="neyvli" title="neyvli" href="neyvli.html" coords="944,388,1074,446" shape="rect">
    <area target="" alt="melpathi" title="melpathi" href="melpathi.html" coords="1120,616,1227,668" shape="rect">
    <area target="" alt="periyakurichi" title="periyakurichi" href="periyakurichi.html" coords="1526,459,1702,506" shape="rect">
    <area target="" alt="nlc" title="nlc" href="nlc.html" coords="472,475,584,529" shape="rect">
</map>
</map>
</center>
</body>
</html>

melp.html

<html>
<head>
<title>melappanapattu</title>
</head>
<body bgcolor="yellow">
<h1 align ="centre">
<front colour="red"><b>MELAPPANAPATTU</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="melappanapattu" size="5">
    Melpappanapattu is a small village located in the Cuddalore district of Tamil Nadu. The village is known for its calm environment, green surroundings, and agriculture-based lifestyle. Most of the people here are involved in farming and related activities. It is a peaceful place where traditional culture and village unity are still maintained.


</font>
</p>
</body>
</html>

melpathi.html

<html>
<head>
<title>melpathi</title>
</head>
<body bgcolor="red">
<h1 align ="centre">
<front colour="red"><b>MELPATHI</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="melpathi" size="5">
    Melpathi is another village situated near Neyveli in Cuddalore district. It has a mix of rural beauty and growing development due to its closeness to Neyveli town. The people of Melpathi mainly depend on agriculture and small-scale jobs. The village has good road connectivity and a friendly community atmosphere.

</font>
</p>
</body>
</html>

neyvli.html

<html>
<head>
<title>neyvli</title>
</head>
<body bgcolor="blue">
<h1 align ="centre">
<front colour="red"><b>NEYVELI</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="neyvli" size="5">
    Neyveli is a well-known industrial township in Tamil Nadu. It is famous for the Neyveli Lignite Corporation (NLC India Limited), which is one of the largest mining and power generation companies in India. Neyveli has modern facilities, schools, hospitals, and residential colonies for employees. The town plays an important role in providing electricity to Tamil Nadu and other states.

</font>
</p>
</body>
</html>

nlc.html

<html>
<head>
<title>nlc mine</title>
</head>
<body bgcolor="skyblue">
<h1 align ="centre">
<front colour="green"><b>NLC MINE</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="nlc" size="5">
    The NLC mine, managed by Neyveli Lignite Corporation, is one of the largest open-cast lignite mines in India. It extracts lignite, a type of brown coal, which is used for power generation in Neyveli’s thermal power stations. The mine supports thousands of workers and contributes greatly to India’s energy needs. It is an important center for industrial growth and energy production in Tamil Nadu.
</font>
</p>
</body>
</html>

periyakurichi.html

<html>
<head>
<title>periyakurichi</title>
</head>
<body bgcolor="skyblue">
<h1 align ="centre">
<front colour="red"><b>PERIYAKURICHI</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="periyakurichi" size="5">
   Periyakurichi is a developing village located near Neyveli. Many residents work in or around the NLC mines, while others are engaged in agriculture. The village benefits from nearby industrial development, better roads, and educational institutions. It has a blend of rural culture and modern influence due to its proximity to Neyveli.
</font>
</p>
</body>
</html>

'''
# OUTPUT

![alt text](<Screenshot 2025-10-07 182039.png>) 
![alt text](<Screenshot 2025-10-07 182204.png>) 
![alt text](<Screenshot 2025-10-07 182151.png>) 
![alt text](<Screenshot 2025-10-07 182134.png>) 
![alt text](<Screenshot 2025-10-07 182123.png>) 
![alt text](<Screenshot 2025-10-07 182052.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
