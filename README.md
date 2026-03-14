# Ex.06 Restaurant Website
## Date:14.03.2026

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in Localhost.

## PROGRAM:
```
admin.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="admin.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="admin">
        <h1><b>ADMINISTRATION TEAM</b></h1>
      </div>
      <div class="admingrid">
        <div class="adminline">
          <img src="Screenshot 2026-03-10 141227.png" width="130" height="250" />
          <h1>hari</h1>
          <p class="post">CEO</p>
        </div>
        <div class="adminline">
          <img src="Dada.jpg" width="130" height="250" />
          <h1>Dhruv vikram</h1>
          <p class="post">Marketing Manager</p>
        </div>
        <div class="adminline">
          <img src="download (5).jpg" width="130" height="250" />
          <h1>Chiyan Vikram</h1>
          <p class="post">Customer Service Manager</p>
        </div>
        <div class="adminline">
          <img src="download (4).jpg" width="130" height="250" />
          <h1>Thalapathy</h1>
          <p class="post">HR Manager</p>
        </div>
        <div class="adminline">
          <img src="Ms Dhoni.jpg" width="130" height="250" />
          <h1>Ms dhoni</h1>
          <p class="post">Executive Chef</p>
        </div>
      </div>
      <footer class="copyrights">&copy; Hari prasath.M-(25018172)</footer>
    </div>
  </body>
</html>

admin.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image:url(BEACH.jpg) ;
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.admin {
    color: rgb(8, 7, 8);
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminline{
    background-color: rgb(216, 193, 149);
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminline img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminline h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.adminline p {
    color: black;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 30px;
    left: -20px;
    position: relative;
}

home.html
<html>
  <head>
    <title>Home Page</title>
    <link rel="stylesheet" href="home.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="restname">
        <h1><b>ROYAL SPICE RESTAURANT</b></h1>
      </div>
      <div class="line1">Delicious Food, Happy Mood.</div>
      <div class="line2">
        <i>"Where every dish tells a story."</i>
        <p>
        Experience the magic of taste at Royal Spice Restaurant.Where every bite feels royal and every moment is flavorful.Serving happiness,one plate at a time.
        </p>
      </div>
      <div class="img1">
        <img src="Belles Beach House Blends Breezy Hawaiian Resort With Izakaya-Style Fare.jpg" width="600" height="300" />
      </div>
      <div class="img2">
        <img src="download (2).jpg" width="600" height="300" />
      </div>
      <footer class="copyrights">&copy;M.Hari prasath - (25018172)</footer>
    </div>
  </body>
</html>

home.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.restname {
    color: rgb(5, 4, 5);
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.line1 {
    color: rgb(12, 12, 7);
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 250%;
    top: -120px;
    left: 10px;
}

.line2 {
    color: rgb(10, 8, 8);
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 130%;
    top: -100px;
}

.img1 {
    position: relative;
    top: -90px;
    left: 100px;
    background-size:contain;
}

.img2 {
    position: relative;
    top: -390px;
    left: 800px;
    background-size:contain;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: -330px;
    left: -20px;
    position: relative;
}

menu.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="menu.css" />
  </head>
  <body>
    <div class="background">
      <div class="content">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="menu">
        <h1><b>MENU</b></h1>
      </div>
      <div class="menugrid">
        <div class="menuitem">
          <img src="download (3).jpg" width="300" height="150" />
          <h1>Chicken Rice</h1>
          <p>Rs.250</p>
        </div>
        <div class="menuitem">
          <img src="Parotta Recipe _ Parotta - Step By Step Recipe _ South Indian Layered Bread - Hotel Style Parotta Recipe.jpg" width="300" height="150" />
          <h1>Parotta</h1>
          <p>Rs.200</p>
        </div>
        <div class="menuitem">
          <img src="Beef Briyani whit Basmati Rice and vergetable.jpg" width="300" height="150" />
          <h1>Beef Biriyani</h1>
          <p>Rs.150</p>
        </div>
      </div>
      <footer class="copyrights">&copy; M.hari prasath -(25018172)</footer>
    </div>
  </body>
</html>

menu.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(download.avif);
    background-size: cover;
}

.content {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: rgb(244, 248, 251);
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.menu {
    color: rgb(20, 17, 19);
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: rgb(232, 192, 234);
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
    border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: rgb(150, 135, 152);
    text-align: center;
    top: 100px;
    left: -20px;
    position: relative;
}
```

## OUTPUT:
c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2026-03-14 141353.png
c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2026-03-14 141431.png
c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2026-03-14 141500.png
c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2026-03-14 141518.png

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
