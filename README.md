# Ex04 Places Around Me
# Date:29-04-2025

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

# PROGRAM

```
home.html

<html>
<head>
  <title>My City</title>
</head>
<body>
  <h1 align="center">
    <font color="red"><b>Tambaram</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Ajmal ALi (212224100003)</b></font>
  </h3>
<center>
    <img src="map.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
      <area shape="rect" coords="700,250,850,400" href="home.html" title="Home">
      <area shape="circle" coords="570,230,45" href="road.html" title="Muduchur road">
      <area shape="circle" coords="640,200,30" href="lake.html" title="Tambaram Lake">
      <area shape="circle" coords="1120,360,25" href="garden.html" title="GG Garden">
      <area shape="rect" coords="950,120,1100,140" href="stop.html" title="Pallikarani">
    </map>
  </center>
</body>
</html>

```

```
garden.html

<html>
<head>
  <title>Garden</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>
  <h3 align="center">
    <font color="lime"><b>GG Garden</b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5" color="white">
        GG Garden in Tambaram is a peaceful residential area known for its calm surroundings.
        It offers easy access to schools, shops, and transport facilities, making life convenient.
        The neighborhood features clean streets, friendly communities, and a green environment.
        Ideal for families, GG Garden combines suburban charm with city connectivity. 
  </p>
</body>
</html>

```

```

lake.html

<html>
<head>
  <title>Lake</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>
  <h3 align="center">
    <font color="lime"><b>Tambaram lake</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
      Lakes are generally formed as a consequence of the tectonic or glacial activity. 
      Lakes are also formed due to the meandering river or even by human activity. 
      For civilization, there are abundant reasons to point them out, this owes to the 
      resource of water, and water is a definite source to continue life on this planet. 
      This lake is also facing numerous problems such as pollution, siltation, and 
      climate change. 
  </p>
</body>
</html>

```

```

road.html

<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="green">
  <h1 align="center">
    <font color="gray"><b>Tambaram</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>MUDUCHUR ROAD </b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
      These Roads construction started at 2017 and successfully ended on 2023.
      These Roads are constructed by L&T . These Roads are know for it's pot holes and 
      number of accidents occuring.
    </font>
  </p>
</body>
</html>

```

```

stop.html

<html>
<head>
  <title>Pallikarani</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>
<h3 align="center">
<font color="lime"><b>Pallikarani</b></font>
<hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Pallikaranai is a neighborhood and a residential area in south Chennai, Tamil Nadu, India. Located in proximity to the IT industry in Old Mahabalipuram Road
    </font>
  </p>
</body>
</html>

```
# OUTPUT

![Screenshot 2025-04-29 110257](https://github.com/user-attachments/assets/73309130-31c4-4d81-87ce-af9c1e9925f5)
![Screenshot 2025-04-29 105959](https://github.com/user-attachments/assets/b5cd4d18-e1cf-485c-b05a-b90f383136cc)
![Screenshot 2025-04-29 104810](https://github.com/user-attachments/assets/754efe42-4c58-4f41-bd9d-d462dad3b1be)
![Screenshot 2025-04-29 104929](https://github.com/user-attachments/assets/88fe2b38-84f4-403c-abac-e90275ef7930)
![Screenshot 2025-04-29 110430](https://github.com/user-attachments/assets/848fd3a4-d6c6-4c1d-af2a-8863efdf7f4b)

# RESULT
The program for implementing image maps using HTML is executed successfully.
