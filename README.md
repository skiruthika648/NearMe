# Ex04 Places Around Me
## Date :5/11/23
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
<img src="avadiimage.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Jaya engineering college" title="Jaya engineering college" href="jaya.html" coords="413,140,566,279" shape="rect">
    <area target="_blank" alt="Velammal engineering college" title="Velammal engineering college" href="velamal.html" coords="1442,150,1289,90" shape="rect">
    <area target="_blank" alt="Prathusha engineering college" title="Prathusha engineering college" href="prath.html" coords="268,612,112,488" shape="rect">
    <area target="_blank" alt="karumari Amman temple" title="karumari Amman temple" href="karu.html" coords="1089,628,925,453" shape="rect">
    <area target="_blank" alt="Chennai Rail museum" title="Chennai Rail museum" href="rail.html" coords="1709,466,1423,357" shape="rect"> 
</map>
```
## jaya.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Jaya Engineering College</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Jaya Engineering College</h1>
        <p>Your Path to Excellence in Engineering</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#admissions">Admissions</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Jaya Engineering College is a renowned institution dedicated to providing top-notch education in the field of engineering and technology. We are committed to shaping the future of engineering professionals and leaders.</p>
    </section>
    
    <section id="courses">
        <h2>Our Courses</h2>
        <ul>
            <li>Computer Science Engineering</li>
            <li>Electrical Engineering</li>
            <li>Mechanical Engineering</li>
            <li>Civil Engineering</li>
        </ul>
    </section>
    
    <section id="admissions">
        <h2>Admissions</h2>
        <p>If you are interested in joining our college, please visit the <a href="admissions.html">Admissions</a> page for more information.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <address>
            Jaya Engineering College<br>
            Address: 789 Oak Lane, City, Country<br>
            Phone: (123) 456-7890<br>
            Email: info@jayaengineeringcollege.edu
        </address>
    </section>
    
    <footer>
        <p>&copy; 2023 Jaya Engineering College. All rights reserved.</p>
    </footer>
</body>
</html>
```
## karu.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Arulmigu Karumariyamman Temple</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #FFD700;
            color: #000;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Arulmigu Karumariyamman Temple</h1>
        <p>Your Spiritual Oasis</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#events">Events</a></li>
            <li><a href="#pooja">Pooja Timings</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Us</h2>
        <p>The Arulmigu Karumariyamman Temple is a sacred place dedicated to the worship of the divine mother, Karumariyamman. It is a center of spirituality and devotion, drawing devotees from all around to seek blessings and find solace.</p>
    </section>
    
    <section id="events">
        <h2>Upcoming Events</h2>
        <p>Stay tuned for our upcoming events and festivals. Join us in celebrating the divine with devotion and enthusiasm.</p>
    </section>
    
    <section id="pooja">
        <h2>Pooja Timings</h2>
        <p>Our temple is open for devotees from early morning until late evening. Check our <a href="pooja_timings.html">Pooja Timings</a> for details on specific pooja schedules.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <address>
            Arulmigu Karumariyamman Temple<br>
            Address: 456 Temple Road, City, Country<br>
            Phone: (123) 456-7890<br>
            Email: info@karumariyammantemple.org
        </address>
    </section>
    
    <footer>
        <p>&copy; 2023 Arulmigu Karumariyamman Temple. All rights reserved.</p>
    </footer>
</body>
</html>
```
## velamal.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Velammal Engineering College</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Velammal Engineering College</h1>
        <p>Your Gateway to Quality Engineering Education</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#admissions">Admissions</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Velammal Engineering College is a prestigious institution committed to providing high-quality education in engineering and technology. Our mission is to nurture future leaders and innovators.</p>
    </section>
    
    <section id="courses">
        <h2>Our Courses</h2>
        <ul>
            <li>Computer Science Engineering</li>
            <li>Electrical Engineering</li>
            <li>Mechanical Engineering</li>
            <li>Civil Engineering</li>
        </ul>
    </section>
    
    <section id="admissions">
        <h2>Admissions</h2>
        <p>If you are interested in joining our college, please visit the <a href="admissions.html">Admissions</a> page for more information.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <address>
            Velammal Engineering College<br>
            Address: 123 Elm Street, City, Country<br>
            Phone: (123) 456-7890<br>
            Email: info@velammalengineeringcollege.edu
        </address>
    </section>
    
    <footer>
        <p>&copy; 2023 Velammal Engineering College. All rights reserved.</p>
    </footer>
</body>
</html>
```
## prath.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Prathyusha Engineering College</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Prathyusha Engineering College</h1>
        <p>Your Path to Excellence in Engineering</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#admissions">Admissions</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Prathyusha Engineering College is a renowned institution dedicated to providing top-notch education in the field of engineering and technology. Our mission is to nurture future leaders and innovators.</p>
    </section>
    
    <section id="courses">
        <h2>Our Courses</h2>
        <ul>
            <li>Computer Science Engineering</li>
            <li>Electrical Engineering</li>
            <li>Mechanical Engineering</li>
            <li>Civil Engineering</li>
        </ul>
    </section>
    
    <section id="admissions">
        <h2>Admissions</h2>
        <p>If you are interested in joining our college, please visit the <a href="admissions.html">Admissions</a> page for more information.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <address>
            Prathyusha Engineering College<br>
            Address: 123 Elm Street, City, Country<br>
            Phone: (123) 456-7890<br>
            Email: info@prathyushaengineeringcollege.edu
        </address>
    </section>
    
    <footer>
        <p>&copy; 2023 Prathyusha Engineering College. All rights reserved.</p>
    </footer>
</body>
</html>
```
## rail.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Chennai Rail Museum</title>
    <style>
        /* Your CSS styles here */
    </style>
</head>
<body>
    <header>
        <h1>Chennai Rail Museum</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#exhibits">Exhibits</a>
        <a href="#visit">Visit</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About the Chennai Rail Museum</h2>
            <p>The Chennai Rail Museum is a fascinating destination for railway enthusiasts and history lovers. It is located in Perambur, Chennai, and showcases the rich heritage of Indian Railways. The museum offers a unique glimpse into the evolution of the Indian railway system, from its early days to the modern era.</p>
        </section>
        <section id="exhibits">
            <h2>Exhibits</h2>
            <p>The museum boasts a diverse collection of exhibits, including vintage locomotives, carriages, and various railway artifacts. Some of the notable exhibits include:</p>
            <ul>
                <li>An impressive collection of steam locomotives that were once used on Indian railways.</li>
                <li>Rare photographs and documents depicting the history of Indian Railways.</li>
                <li>A model train section where visitors can witness miniature railway setups.</li>
            </ul>
        </section>
        <section id="visit">
            <h2>Visit Us</h2>
            <p>If you're planning to visit the Chennai Rail Museum, here's some essential information:</p>
            <ul>
                <li><strong>Location:</strong> The museum is situated at New Avadi Road, Perambur, Chennai, Tamil Nadu.</li>
                <li><strong>Opening Hours:</strong> The museum is typically open from 10:00 AM to 5:30 PM on all days except Mondays.</li>
                <li><strong>Admission:</strong> The entry fee for adults is Rs. 20, and for children (up to 12 years) it's Rs. 10.</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or need additional information, please don't hesitate to get in touch with us:</p>
            <p><strong>Phone:</strong> +91-1234567890</p>
            <p><strong>Email:</strong> info@chennairailmuseum.org</p>
        </section>
    </div>
</body>
</html>
```


## OUTPUT
![image](https://github.com/skiruthika648/NearMe/assets/128348968/3400992f-1858-4153-a4e4-c70ca6bc0326)
![image](https://github.com/skiruthika648/NearMe/assets/128348968/6c76af90-94b8-4865-99c1-24f0b7d210c3)
![image](https://github.com/skiruthika648/NearMe/assets/128348968/931c8609-81d9-4f39-a20e-65505928c576)
![image](https://github.com/skiruthika648/NearMe/assets/128348968/c0871995-6bd7-43d6-ade3-cdcf085a1a6f)
![image](https://github.com/skiruthika648/NearMe/assets/128348968/3906a924-5f40-487f-808c-9fa5c1b8adcd)


## RESULT
The program for implementing image maps using HTML is executed successfully.
