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

## CODE:

```
<html>
<head>
<title>MY CITY</title>  
<link rel="stylesheet" href="map.css"> 
</head>
<body style="background-color: beige;">
<h1 align="center">
<font style="color: black;"><b>Pondicherry</b></font>
</h1>
<h3 align="center">
<font color="black"><b>RAHUL VIJAY V(212223040164)</b></font>
</h3>
<center>
    <img src="./img/maps.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="INDIRA GANDHI COLLEGE" title="INDIRA GANDHI COLLEGE" href="college.html" coords="28,211,235,337" shape="rect">
    <area target="" alt="RAJIV GANDHI HOSPITAL" title="RAJIV GANDHI HOSPITAL" href="hospital.html" coords="761,493,960,564" shape="rect">
    <area target="" alt="GOVT SCHOOL" title="GOVT SCHOOL" href="school.html" coords="464,370,678,411" shape="rect">
    <area target="" alt="LE ROYAL PARK" title="LE ROYAL PARK" href="hotel.html" coords="1445,356,1645,445" shape="rect">
    <area target="" alt="REZIERE FARM" title="REZIERE FARM" href="farm.html" coords="1062,472,1203,513" shape="rect">
</map>
</map>
</center>
</body>
</html>


<html>
    <head>
        <title>INDIRA GANDHI COLLEGE</title>
    </head>
    <body bgcolor="blueviolet">
        <h1 align="center">
            <font color="blue"><b>PONDICHERRY</b></font>
        </h1>
        <h2 align="center">
            <font color="black"><b>INDIRA GANDHI COLLEGE</b></font>
        </h2>
        <hr size="3" color="blue">
        <p align="justify">
            <font face="Times New Roman" size="6" color="black">
                Indira Gandhi Medical College & Research Institute (IGMC&RI) in Pondicherry is a premier medical institution offering undergraduate and postgraduate medical education. Established in 2010, it is affiliated with Pondicherry University and recognized by the Medical Council of India. With state-of-the-art facilities and experienced faculty, IGMC&RI is committed to providing high-quality healthcare and medical research.
            </font>
        </p>
    </body>
</html>


<html>
    <head>
        <title>RAJIV GANDHI HOSPITAL</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="blue"><b>PONDICHERRY</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>RAJIV GANDHI HOSPITAL</b></font>
        </h2>
        <hr size="3" color=="plum">
        <p align="justify">
            <font face="Times New Roman" size="6" color="red">
                The Rajiv Gandhi Government Women and Children's Hospital in Pondicherry is a prominent healthcare institution dedicated to the well-being of women and children. It offers a range of medical services including maternity care, pediatric care, and gynecological services. The hospital is equipped with modern facilities and staffed by skilled healthcare professionals. It plays a vital role in providing quality healthcare to the community in Pondicherry and surrounding areas
            </font>
        </p>
    </body>
</html>

<html>
    <head>
        <title>GOVT SCHOOL</title>
    </head>
    <body bgcolor="skyblue">
        <h1 align="center">
            <font color="black"><b>PONDICHERRY</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>GOVT SCHOOL</b></font>
        </h2>
        <hr size="3" color=="cyan">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                The government school in Pondicherry is the Government Higher Secondary School located in middle of the Pondicherry. It serves as an educational institution for students from various socio-economic backgrounds. Offering education from primary to higher secondary levels, the school aims to provide quality education and opportunities for its students. With dedicated teachers, extracurricular activities, and government support, the school plays a vital role in shaping the future of young minds in the region.            
            </font>
        </p>
    </body>
</html>


<html>
    <head>
        <title>LE ROYAL PARK</title>
    </head>
    <body bgcolor="darkblue">
        <h1 align="center">
            <font style="color: rgba(64, 156, 3, 0.837);"><b>PONDICHERRY</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>LE ROYAL PARK</b></font>
        </h2>
        <hr size="3" color=="red">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                Le Royal Park is a luxury hotel located in Pondicherry, offering upscale accommodation and amenities to its guests. Situated in the heart of the city, it provides easy access to major attractions such as the Promenade Beach and Aurobindo Ashram. The hotel boasts well-appointed rooms, fine dining options, a rooftop swimming pool, and a spa for relaxation. With its elegant ambiance and attentive service, Le Royal Park is a popular choice for both leisure and business travelers visiting Pondicherry.
            </font>
        </p>
    </body>
</html>

<html>
    <head>
        <title>REZIERE FARM</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="yellow"><b>PONDICHERRY</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>REZIERE FARM</b></font>
        </h2>
        <hr size="3" color=="plum">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                Reziere farm in Pondicherry lies a charming farm known for its organic produce and serene surroundings. Families often visit to pick fresh fruits and vegetables, enjoying a peaceful escape from city life. The farm offers educational tours, teaching visitors about sustainable farming practices. It's a delightful destination for both locals and tourists seeking a taste of rural life.
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-28 093629.png>)
![alt text](<Screenshot 2024-03-28 093313.png>)
![alt text](<Screenshot 2024-03-28 093333.png>)
![alt text](<Screenshot 2024-03-28 093324.png>)
![alt text](<Screenshot 2024-03-28 093353.png>)
![alt text](<Screenshot 2024-03-28 093344.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
