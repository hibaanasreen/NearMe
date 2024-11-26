# Ex04 Places Around Me
## Date: 26/11/2024

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
mapm.html
<html>

<head>

<title>My City</title>

</head>

<body>

<h1 align="center">

<font color="orange"><b>Tindivanam</b></font>

</h1>

<h3 align="center">

<font color="green"><b>Hiba Nasreen M (24900188)</b></font>

</h3>

<center>

   
    <img src="tindivanam map.png" usemap="#image-map">
    
    <map name="image-map">
        <area target="" alt="swastik rohini cinemas" title="swastik rohini cinemas" href="Swastik Rohini Cinemas.html" coords="826,258,128" shape="circle">
        <area target="" alt="jvs shakthi mahal" title="jvs shakthi mahal" href="jvsshakthimahal.html" coords="910,699,104" shape="circle">
        <area target="" alt="heera residency" title="heera residency" href="heera residency.html" coords="1160,566,87" shape="circle">
        <area target="" alt="kannaiya theatre" title="kannaiya theatre" href="kannaiyatheatre.html" coords="1302,722,105" shape="circle">
        <area target="" alt="om thinthirineesvarar kovil" title="om thinthirineesvarar kovil" href="omthinthirineesvaran kovil.html" coords="1029,382,105" shape="circle">
    </map>
</map>
</center>
</body>

</html>
```
```
heera residency.html
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heera Residency</title>

</head>
<body bgcolor="pink">
    <h1 style="font-family: cursive; color: rgb(189, 3, 96);">Heera Residency</h1>
    <h2 style="font-family: serif;">It provides accommodations with a garden and free WiFi as well as free private parking for guests who drive. 
        This 2-star hotel offers room service and a 24-hour front desk. 
</body>
</html>
```
```
jvsshakthimahal.html
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JVS Shakthi Mahal</title>

</head>
<body bgcolor="orange">
    <h1 style="font-family: cursive; color: rgb(189, 71, 3);">JVS Shakthi Mahal</h1>
    <h2 style="font-family: serif;">Spacious marriage hall with ample rooms for guest stay and parking area,
        Good air conditioning in the hall,
        Attractive mahal with ornamental lighting and nicely designed plants.
    </h2>
    
</body>
</html>
```
```
kannaiyatheatre.html
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kannaiya Theatre</title>

</head>
<body bgcolor="sky blue">
    <h1 style="font-family: cursive; color: rgb(3, 29, 177);">kannaiaya Theatre</h1>
    <h2 style="font-family: serif;">Kannaiya theater is one of the best theater.
        It has good interior structure.
         
    </h2>
    
</body>
</html>
```
```
omthinthirineesvaran kovil.html
<<html lang="en"> 
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Kannaiya Theatre</title>
    
    </head>
    <body bgcolor="sky blue">
        <h1 style="font-family: cursive; color: rgb(3, 29, 177);">kannaiaya Theatre</h1>
        <h2 style="font-family: serif;">Kannaiya theater is one of the best theater.
            It has good interior structure.
             
        </h2>
        
    </body>
    </html>
    ```
    ```
    Swastik Rohini Cinemas.html
    <html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swastik Rohinini Cinemas</title>

</head>
<body bgcolor="yellow">
    <h1 style="font-family: cursive; color: rgb(189, 164, 3);">Swastik Rohini Cinemas</h1>
    <h2 style="font-family: serif;"> It has good projection quality and clarity,
       It has Nice sound effects.
    </h2>
    
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-26 143836-1.png>)
![alt text](<Screenshot 2024-11-26 112521-2.png>)
![alt text](<Screenshot 2024-11-26 112414.png>) 
![alt text](<Screenshot 2024-11-26 112437.png>)
![alt text](<Screenshot 2024-11-26 112343.png>)
![alt text](<Screenshot 2024-11-26 112326.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
