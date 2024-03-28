# Ex04 Places Around Me
## Date: 

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
<!DOCTYPE html>
<html>
<head>
<title>MY CITY</title>
</head>
<body>
<h1 align="center">
<font color=""><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="green"><b>S V SHADHANASHREE (23013434)</b></font>
</h3>
<hr size="3" color="red">
<center>
    <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="AMBATTUR" title="AMBATTUR" href="ambattur.html" coords="929,339,832,295" shape="rect">
    <area target="" alt="AVADI" title="AVADI" href="avadi.html" coords="808,371,772,279,688,364" shape="poly">
    <area target="" alt="T. NAGAR" title="T. NAGAR" href="tnagar.html" coords="1024,456,48" shape="circle">
    <area target="" alt="GUINDY" title="GUINDY" href="guindy.html" coords="1042,515,965,508,965,569,1017,574" shape="poly">
    <area target="" alt="PORUR" title="PORUR" href="porur.html" coords="837,454,923,498" shape="rect">
</map>
</center>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="cyan">
    <h1 align="center">
        <font color=""><b>CHENNAI</b></font>
        </h1>
<h1 align="center">
<font color="black"><b>AMBATTUR</b></font>
</h1>
<h3 align="center">
    <font color="blue"></font>
 </h3>
<hr size="3" color="violet">

<p align="justify">
<font face="Georgia" size="5">
Ambattur is a bustling city located in the Northwestern part of Chennai, India. It is one of the fastest-growing suburbs in the region and is known for its industrial and residential developments. With a rich history and vibrant cultural heritage, Ambattur has become a significant hub for commerce, manufacturing, and urban living.

</font>
</p>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="yellow">
    <h1 align="center">
        <font color=""><b>CHENNAI</b></font>
        </h1>
<h1 align="center">
<font color="black"><b>AVADI</b></font>
</h1>
<h3 align="center">
    <font color="grey"></font>
</h3>
<hr size="3" color="pink">

<p align="justify">
<font face="Georgia" size="5">
    The Avadi Tank Factory is a major manufacturing unit for tanks and armored vehicles and plays a significant role in strengthening the country’s defense forces.
    The city is known for its festivals, traditional music and dance forms, showcasing the vibrant cultural fabric of Tamil Nadu.
    With multiple industrial estates and manufacturing units, Avadi contributes significantly to the state’s economy through its industries.
</font>
</p>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="pink">
    <h1 align="center">
        <font color=""><b>CHENNAI</b></font>
        </h1>
<h1 align="center">
<font color="black"><b>T. NAGAR</b></font>
</h1>
<h3 align="center">
    <font color="red"></font>
</h3>
<hr size="3" color="blue">

<p align="justify">
<font face="Georgia" size="5">
 Thyagaraya Nagar, commonly known as T. Nagar, is a neighbourhood located in Chennai, Tamil Nadu, India. It is known for its commercial and shopping areas, many clothing and jewellery stores, restaurants, and cafes. The neighbourhood is also home to several temples, parks, and educational institutions. T. Nagar is considered one of the busiest areas in Chennai and a popular destination for locals and tourists alike.
</font>
</p>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="orange">
    <h1 align="center">
        <font color=""><b>CHENNAI</b></font>
        </h1>
<h1 align="center">
<font color="black"><b>GUINDY</b></font>
</h1>
<h3 align="center">
    <font color="green"></font>
</h3>
<hr size="3" color="lavender">
<p align="justify">
<font face="Georgia" size="5">
    Guindy is one of the prestigious localities in Chennai. The area of Guindy is known as The Gateway of Chennai. The residential area of Guindy is located in the South of Chennai and has Guindy National Park. The area of Guindy is just 10 KM from Chennai International Airport. The area of Guindy has both independent houses and multi storey homes. In addition, there are several educational institutes and hospitals near the Guindy area.
</font>
</p>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="green">
    <h1 align="center">
        <font color=""><b>CHENNAI</b></font>
        </h1>
<h1 align="center">
<font color="black"><b>PORUR</b></font>
</h1>
<h3 align="center">
    <font color="grey"></font>
</h3>
<hr size="3" color="lavender">
<p align="justify">
<font face="Georgia" size="5">
    Sprawling and residential, Porur is known for the expansive lake of the same name and the small, waterside Porur Lake Shiva Temple. Nearby, the centuries-old Sri Ramanaadheswarar Temple has an ornately carved gopura gateway tower. Clothing and appliances stores, Indian restaurants, and the N.S.N. produce and fish markets cluster at the busy junction of Kundrathur Main Road and Mount Poonamalle High Road.
</font>
</p>
</body>
</html>
```





## OUTPUT
 ![alt text](<Screenshot 2024-03-28 045703.png>)
![alt text](<Screenshot 2024-03-28 045642.png>)
![alt text](<Screenshot 2024-03-28 045439.png>) 
![alt text](<Screenshot 2024-03-28 045457.png>) 
![alt text](<Screenshot 2024-03-28 045510.png>) 
![alt text](<Screenshot 2024-03-28 045534.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
