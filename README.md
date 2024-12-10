# Ex04 Places Around Me
## Date: 17/11/2024

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
```
map.html
<html>
<head>
<tilte>My City</tilte>    
</head>    
<body>
<h1 align="center">
<font color="red"><b>Gingee</b></font>    
</h1>    
<h3 align="center">
<font color="blue"><b>Srisha M (24901268)</b></font>    
</h3>
<center>
<img src="Screenshot 2024-11-17 184128.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">  
<area shape="circle" coords="570,230,45" href="temple.html" title="Balamurugan Temple">
<area shape="circle" coords="640,200,30" href="lake.html" title="Anathur Lake">
<area shape="circle" coords="1120,360,25" href="garden.html" title="RR Garden">
<area shape="circle" coords="950,120,1100,140" href="stone.html" title="Virpattu Big stone">  
</map>  
</center>
</body>
</html>

home.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Gingee</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Anathur - My Home Town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia"size="5">
Anathur village is located in Gingee taluka of viluppuram district in Tamil Nadu,these
are the district & sub-district headquarters of Anathur village respectively.As there is also
a gram panchayat. The total geograpical area of village is 457.97 hectare of the 852 peoples
out of which male population is 436 while female population is 410 is 70.42% out of which
78.21% males and 62.26% females are literate. There are about the pincode of anathur village 
locality is 604202.Gingee in nearest town to anuthur village that which ic approximately 7km away.</font>
</p>
</body>
</html>

garden.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Gingee</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>RR Garden - The O<sub>2</sub>Way</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
A Garden is the best place in the house. As it is only place where a person can relax.
Moreover,having a garden in the house welcomes many health benefits.For instance ,
more than 310 tree species have been planted in the 25-acre arboretum
5,500 species in the forest, and a TDEF plant nursery has been created ,
capable of producing 50,000 seeds of indigenous flora of the region.</font>
</p>
</body>
</html>

lake.html
<head>
<title>My Home Town</title>    
</head>
<body bgcolor="purple">
<h1 align="center">
<font color="cyan"><b>Gingee</b></font>    
</h1>    
<h3 align="center">
<font color="lime"><b>Virpattu Big Stone - The Tourists Attraction</b></font>    
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5" color="white">
    Lakes are generally formed as a consequence of the tectonic or glacial activities.
    Lakes are also formed due to the meandering river or even by human activity.
    For civilization,there are abundant reasons to point them out, this owes to the resources
    of water,and water is a definite source to continue life on this planet. This lake is also
    facing numerous problems such as pollution, siltation,and climatic change. The 
    government and varoius organizations are taking steps by investing in research to understand 
    the ecological balance, developing sustiable local community for their conservation.
</font>    
</p>
</body>
</body>    
</html>

stone.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Gingee</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Virapattu Big Stone - The Tourists Attraction</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The granitic rocks in the area were formed towards the end of the Archean Era of the 1500-2500 million
years ago due to magmatic action,leading to the melting of the older gneissic rocks and intrusion of 
younger granitic complexes varying from 5 to 25 km. virpattu village is located in Gingee 
Taluk in Tamil Nadu,India.Viluppuram and gingee are the district and sub-district headquarters,
respectively.Gingee is the nearest town  to Virpattu for all major economic activities ,
which is approximately 12 km away.</font>
</p>
</body>
</html>

temple.html
<html>
<head>
<title>My Home Town</title>
</head>    
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Gingee</b></font>    
</h1>    
<h3 align="center">
<font color="blue"><b>Shri Balamurugan Temple</b></font>    
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Temple's main  deity is Lord murugan, who is worshipped as the god of war and a handsome young man riding a peacock
with six faces and twelve arms.The idol is made with gold and diamonds.The temple architecture is a fine example of the 
dravidian style, with a tall gopuram (gateway tower) at the entrance, adorned with intricates carvings of gods.
It has a mandapam (hall) with beautifully carved pillars,which houses the main shirne       
</p>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-17 184128.png>)
![alt text](<Screenshot 2024-11-17 211138.png>)
![alt text](<Screenshot 2024-11-17 211332.png>)
![alt text](<Screenshot 2024-11-17 211442.png>)
![alt text](<Screenshot 2024-11-17 211519.png>)
![alt text](<Screenshot 2024-11-17 211538.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
