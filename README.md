# Ex04 Places Around Me
## Date: 22.04.2025

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
imagemap.html
<html>
<head>image map</head>
<title>
image map
</title>
<body>
    <!-- Image Map Generated by http://www.image-map.net/ -->
<img src="Screenshot 2025-04-11 104705.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="SDC and ACS" title="SDC and ACS" href="Thiruverkadu.html" coords="1422,380,306" shape="circle">
    <area target="" alt="Panimalar" title="Panimalar" href="Panimalar Engineering College.html" coords="270,663,19,367" shape="rect">
    <area target="" alt="Bus Stand" title="Bus Stand" href="Poonamallee.html" coords="331,680,825,670,591,339" shape="poly">
</map>
</body>
</html>
panimalar.html
<html>
    <head>Panimalar Engineering College</head><body ng="cyan">
        <dl>
        <dt align="centre">Panimalar Engineering College</dt>
        <dd>
            Panimalar Engineering College (PEC), a Christian Minority Institution of Higher Education, is located near Poonamallee, Chennai, and is known for its quality engineering education. It's governed by JAISAKTHI Educational Trust and is well-connected to Chennai, Kancheepuram, and Thiruvallur districts.
        </dd>
        </dl>
    </body>
</html>
ponamalle.jtml
<html>
    <head>Poonamallee</head><body ng="cyan">
        <dl>
        <dt align="centre">Poonamallee</dt>
        <dd>
            Poonamallee is a western suburb of Chennai, India under the Chennai Metropolitan Area. It was historically called Pushpagirimangalam, later renamed in Tamil as Poovirundhavalli (Tamil: [puːʋiɾɯn̪daʋalli]), and now colloquially called as Poondhamalli. It is the headquarters of the Poonamallee taluk of the Tiruvallur district in the Indian state of Tamil Nadu. The nearest Railway station is at Avadi. It acts as the gateway to the city from its western side. It is a town with rich cultural heritage and also a fast-growing areas in the city. As of 2011, the town had a population of 60,607. There are plans to merge the areas under Poonamallee Municipality with Avadi Municipal Corporation.
        </dd>
        </dl>
    </body>
</html>
thiruverkadu.html
<html>
    <head>Thiruverkadu</head><body ng="cyan">
        <dl>
        <dt align="centre">Thiruverkadu</dt>
        <dd>
            Thiruverkadu (Tamil: [திருவேற்காடு]; literally 'a forest of holy herbs and roots') is a western suburb of Chennai, Tamil Nadu. It comes under Thiruvallur district administration. It is famous for its Devi Karumariamman Temple. There is also Vedapureeswarar Temple in Thiruverkadu, where Lord Shiva and Goddess Parvathi are seen in their wedding pose inside the sanctum sanctorum. As of 2011, the town had a population of 62,289. It is a town with rich cultural heritage and also a fast-growing areas in the city.
        </dd>
        </dl>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-04-11 104705.png>)
![alt text](<Screenshot 2025-04-22 143730.png>) 
![alt text](<Screenshot 2025-04-22 143701.png>)
 ![alt text](<Screenshot 2025-04-22 143715.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
