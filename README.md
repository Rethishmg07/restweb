# Ex.06 Restaurant Website
## Date:22-12-2025

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
Publish the website in the given URL.

## PROGRAM:
```
Index.html
<html>
    <head>  
        <title>index Page</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <i><h1 class="homehead">The Hungry Haven</h1></i>
        <i><h2 style="text-align: center;font-size: 50px;color: aliceblue;">One Bite, Full Delight...</h2></i>
        <div class="img">
            <img src="shop1.jpeg" class="restbg1">
            <img src="shop2.jpeg" class="restbg2">
            <img src="shop3.jpeg" class="restbg3">
        </div>
        <nav class="nav2">
            <ul>
                <li><a href="index.html" style="color: white;">index</a></li>
                <li><a href="menue.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 style="text-align: center;" class="footer2">&copy; M.G Rethish [25012569]</h2>
    </body>
</html>
```

```
Menu.html
<html>
    <head>
        <title>Menu</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <h1 class="menuhead">Menu</h1>
        <input type="search" class="search" ><button class="button">Search</button><br>
        <div class="mainbox">
            <div class="box1">
            <img src="1.jpeg" class="food1">
            <h3 style="text-align: center;">italian dish</h3>
            <h4>RS : 149</h4>
        </div>
        <div class="box2">
            <img src="3.jpeg" class="food2">
            <h3 style="text-align: center;">amarican grill</h3>
            <h4>RS : 299</h4>
        </div>
        <div class="box3">
            <img src="1.jpeg" class="food3">
            <h3 style="text-align: center;">japanish soup</h3>
            <h4>RS : 99</h4>
        </div>
        <div class="box4">
            <img src="4.jpeg" class="food4">
            <h3 style="text-align: center;">KFC Chicken</h3>
            <h4>RS : 299</h4>
        </div>
        <div class="box5">
            <img src="5.jpeg" class="food5">
            <h3 style="text-align: center;">Showerma</h3>
            <h4>RS : 49</h4>
        </div>
        </div>
        <nav class="nav3">
            <ul>
                <li><a href="index.html" style="color: white;">index</a></li>
                <li><a href="menue.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 class="footer3">&copy; M.G Rethish [25012569]</h2>
    </body>
</html>
```
```
admin.html
<html>
    <head>
        <title>Admin Site</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <h1 class="adminhead">Administration Team</h1>
        <div class="adminbox">
            <div class="admin1">
                <img src="ph1.jpeg" class="one">
                <h3>M.Vetrivel</h3>
                <h3>CEO</h3>
            </div>
            <div class="admin2">
                <img src="ph2.jpeg" class="two">
                <h3>MRP</h3>
                <h3>Head of Marketing</h3>
            </div>
            <div class="admin3">
                <img src="ph3.jpeg" class="three">
                <h3>Sanji</h3>
                <h3>Chief Cook</h3>
            </div>
            <div class="admin4">
                <img src="ph4.jpeg" class="four">
                <h3>Kira</h3>
                <h3>Operation Manager</h3>
            </div>
            <div class="admin5">
                <img src="ph5.jpeg" class="five">
                <h3>Tony</h3>
                <h3>HR Manager</h3>
            </div>
            <div class="admin6">
                <img src="ph6.jpeg" class="six">
                <h3>Punisher</h3>
                <h3>Security</h3>
            </div>
        </div><br><br>
        <nav class="nav4">
            <ul>
                <li><a href="index.html" style="color: white;">index</a></li>
                <li><a href="menue.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 class="footer4">&copy; M.G Rethish [25012569]</h2>
    </body>
</html>
```
```
Contact.html
<html>
    <head>
        <title>My Restaurant</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
            <h1 style="font-size: 100px;" class="Contact">Contact</h1>
            <div class="tablestyle">
            <table class="table">
                <tr>
                    <td><h1>Visit us at</h1></td>
                </tr>
                <tr>
                    <td><h3>220, Anna Nagar 2nd Avenue, Block Y</h3></td>
                </tr>
                <tr>
                    <td><h1>Phone Number</h1></td>
                </tr>
                <tr>
                    <td><h3>8903356233</h3></td>
                </tr>
                <tr>
                    <td><h1>Email ID:</h1></td>
                </tr>
                <tr>
                    <td><h3>foodcafe@gmail.com</h3></td>
                </tr>
            </table>
        </div>
        <nav class="nav">
            <ul>
                <li><a href="index.html" style="color: white;">index</a></li>
                <li><a href="menue.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 class="footer">&copy; M.G Rethish [25012569]</h2>
    </body>
</html>
```

## OUTPUT:

![alt text](<Screenshot (31).png>)
![alt text](<Screenshot (32).png>)
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
