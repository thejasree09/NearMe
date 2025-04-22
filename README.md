# Ex04 Places Around Me
## Date: 22/4/25

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
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Gingee</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Bakkiyalakshmi E (23016303)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="570,230,45" href="temple.html" title="Balamurugan Temple">
<area shape="circle" coords="640,200,30" href="lake.html" title="Anathur Lake">
<area shape="circle" coords="1120,360,25" href="garden.html" title="RR Garden">
<area shape="rect" coords="950,120,1100,140" href="stone.html" title="Virpattu Big Stone">
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
<font face="Georgia" size="5">
Anathur village is located in Gingee taluka of Viluppuram district in Tamil Nadu, India. Viluppuram and Gingee 
are the district & sub-district headquarters of Anathur village respectively. As per 2009 stats, Anathur village 
is also a gram panchayat. The total geographical area of village is 457.97 hectares. Anathur has a total population 
of 852 peoples, out of which male population is 436 while female population is 416. Literacy rate of anathur village 
is 70.42% out of which 78.21% males and 62.26% females are literate. There are about 205 houses in anathur village. 
Pincode of anathur village locality is 604202. Gingee is nearest town to anathur for all major economic activities, 
which is approximately 7km away.</font>
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
<font color="blue"><b>RR Garden - The O<sub>2</sub> Way</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
A Garden is the best place in the house. As it is the only place where a person can get relief from a busy life. 
Moreover having a garden in the house welcomes many health benefits. For instance, a garden has many plants that give oxygen.
More than 310 tree species have been planted in the 25-acre arboretum, 5,500 specimens have been planted in the 10-acre conservation 
forest, and a TDEF plant nursery has been created, capable of producing 50,000 seedlings per year to promote the re-introduction of the
 indigenous flora of the region.</font>
</p>
</body>
</html>

lake.html

<html>
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
    Lakes are generally formed as a consequence of the tectonic or glacial activity in a typical region. 
    Lakes are also formed due to the meandering river or even by human activity. Lakes are quite important 
    for civilization, there are abundant reasons to point them out, this owes to the reason as lakes are a 
    resource of water, and water is a definite source to continue life on this planet earth.
    This lake is also facing numerous problems such as pollution, siltation, and encroachment due to urbanization 
    and climate change. The government and various organizations are taking steps to preserve these natural resources 
    by investing in research to understand the ecological balance, developing sustainable tourism, and educating the 
    local community for their conservation.
</font>
</p>
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
<font color="blue"><b>Virpattu Big Stone - The Tourists Attraction</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The granitic rocks in the area were formed towards the end of the Archean Era of the geological time scale, 
due to magmatic action leading to the melting of the older gneissic rocks and intrusion. The thickness of this 
younger granitic complex varies from 5 to 25 km. Virpattu village is located in Gingee taluka of Viluppuram district 
in Tamil Nadu, India. Viluppuram and Gingee are the district & sub-district headquarters of Virpattu village respectively. 
Gingee is nearest town to virpattu for all major economic activities, which is approximately 5km away.</font>
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
<font color="blue"><b>Shri Balamurugan Temple - Devotional Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The temple's main deity is Lord Murugan, who is worshipped as the god of war and victory. The deity is depicted as a 
handsome young man riding a peacock with six faces and twelve arms. The idol is made of precious stones and is adorned 
with gold and diamonds. The temple architecture is a fine example of the Dravidian style of architecture. The temple has 
a tall gopuram (gateway tower) at the entrance, adorned with intricate carvings of various Hindu deities. The temple also 
has a mandapam (hall) with beautifully carved pillars, which houses the main shrine of Lord Murugan.</font>
</p>
</body>
</html>
```

## OUTPUT
![Alt text](1.png)
![Alt text](2.png)
![Alt text](3.png)
![Alt text](4.png)
![Alt text](5.png)
![Alt text](6.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
