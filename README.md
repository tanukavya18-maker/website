# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Tasty Table</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>The Tasty Table</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="home">      
        <h1>Official Page Of The Tasty Table</h1>
        <p>Made with love and a pinch of passion.</p>
    </section>
     <section id="story"class="story">
            <h2>Our Story</h2>
            <p>
               The Tasty Table is not merely a restaurant; it is a narrative of flavors and fellowship. Born from the idea that every great meal begins not in the kitchen but in the connection between people, it seeks to remind us that taste is more than sensation — it’s emotion, memory, and meaning combined. Chef Arin Vale’s vision is simple yet profound: to craft dishes where flavor tells a story of harmony — where sweet meets savory, texture meets tenderness, and every table becomes a stage for togetherness. The Tasty Table isn’t just about eating; it’s about rediscovering what it means to share taste itself.
            </p>
        </section>
    <footer>
        <p>&copy; 2025 The Tasty Table. All Rights Reserved.</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
    <h1>The Tasty Table</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="menu" class="story">
        <h2>Today's Special</h2>
        <div class="menu">
            <div class="items">
                <h3>Steak Dinner</h3>
                <img src="https://www.simplyrecipes.com/thmb/P9H1SrWMXvlywbZ9-69aO0mD0JU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/simply-recipes-easy-steak-au-poivre-lead-1-7ea7ee649fb64401be483e698fc8bbd5.jpg" alt="Steak Dinner" align="center">
                <p>a delicious, tender cut of beef, often grilled or pan-seared to perfection. Loved for its rich flavor and juicy texture.</p>
            </div>
            <div class="items">
                <h3>Sushi</h3>
                <img src="https://www.freshfarms.com/wp-content/uploads/2023/03/Exploring-the-Different-Types-of-Sushi-for-Flavorful-and-Unique-Experiences.jpg" alt="Sushi" align="center">
                <p>a Japanese dish of vinegared rice paired with fresh seafood or vegetables. Known for its artistry, balance, and freshness, it symbolizes Japan's precision and global culinary influence.</p>
            </div>
            <div class="items">
                <h3>Croissant</h3>
                <img src="https://delishglobe.com/wp-content/uploads/2024/11/Croissants-article.png" alt="Croissant" align="center">
                <p>a flaky, buttery French pastry known for its crescent shape and delicate layers. Often enjoyed at breakfast, it represents the elegance and mastery of traditional French baking.</p>
            </div>
            <div class="items">
                <h3>Dumplings</h3>
                <img src="https://food.fnr.sndimg.com/content/dam/images/food/fullset/2020/11/19/0/MW612_pork-dumplings_s4x3.jpg.rend.hgtvcom.1280.960.suffix/1605802271825.webp" alt="Dumplings" align="center">
                <p>soft dough parcels filled with meat, vegetables, or seafood. Steamed, boiled, or fried, they’re loved worldwide for their comforting taste and cultural variety, symbolizing togetherness and celebration.</p>
            </div>
            <div class="items">
                <h3>Plate Shawarma</h3>
                <img src="https://i.guim.co.uk/img/media/698fd183dc12485059346ec795d4b1325d5b25bc/310_2085_2819_1691/master/2819.jpg?width=1200&height=900&quality=85&auto=format&fit=crop&s=2d53d4b1104baa20304e4c1506f7cbb9" alt="Plate Shawarma" align="center">
                <p>a Middle Eastern dish featuring sliced, seasoned meat served on a plate with accompaniments like rice, salad, hummus, and garlic sauce. It offers bold flavors and hearty satisfaction.</p>
            </div>
            <div class="items">
                <h3>Butter Chicken</h3>
                <img src="https://www.licious.in/blog/wp-content/uploads/2020/10/butter-chicken--600x600.jpg" alt="Butter Chicken" align="center">
                <p>a rich Indian dish made with tender chicken simmered in a creamy tomato and butter-based sauce. Mildly spiced and flavorful, it's best enjoyed with naan or basmati rice.</p>
            </div>
            <div class="items">
                <h3>Extra Cheese Pizza</h3>
                <img src="https://t3.ftcdn.net/jpg/15/40/60/00/360_F_1540600035_Aou2AjQF95vrdL1M1i8Jd20XRuMELL6x.jpg" alt="Extra Cheese Pizza" align="center">
                <p>An extra cheese pizza is a classic favorite that takes the traditional pizza up a notch with a double (or even triple) layer of gooey, melted cheese.</p>
            </div>
            <div class="items">
                <h3>Fried Chicken</h3>
                <img src="https://vaya.in/recipes/wp-content/uploads/2018/05/Fried-Chicken.jpg" alt="Fried Chicken" align="center">
                <p>Juicy chicken pieces coated in a crispy, seasoned batter and deep-fried to perfection.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 The Tasty Table. All Rights Reserved.</p>
    </footer>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - The Tasty Table</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
       <h1>The Tasty Table</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>Staff Members</h2>
        <div class="menu">
            <div class="staff">
                <img src="https://images.stockcake.com/public/e/c/9/ec99397d-f907-4b71-b645-479318f7c71e_large/chef-serving-food-stockcake.jpg" alt="John Doe - Head Chef" style="width:200px;height:auto;">
                <h3>John Doe</h3>
            </div>
            <div class="staff">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTaVeKEbOxwd8ET5zBL2R1Uao5kR5i5xNAJTQ&s" alt="Jane Smith - Pastry Chef" style="width:200px;height:auto;">
                <h3>Jane Smith</h3>
            </div>
            <div class="staff">
                <img src="https://i.pinimg.com/474x/d2/35/47/d2354797cfb995122e8bf0248cb1fd76.jpg" alt="Mike Johnson - Restaurant Manager" style="width:200px;height:auto;">
                <h3>Mike Johnson</h3>
            </div>
            <div class="staff">
                 <img src="https://images.stockcake.com/public/c/1/c/c1c4ed49-3fdc-4ce5-a253-04bf41089b15_large/happy-professional-chef-stockcake.jpg" alt="Emily Davis - Sommelier" style="width:200px;height:auto;">           
                 <h3>Emily Davis</h3>
                </div>
            
        </div>
    </section>
    <footer>
        <p>&copy; 2025 The Tasty Table. All Rights Reserved.</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
     <header>
        <h1>The Tasty Table</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="contact" class="story">
             <h2>Visit Us or Make a Reservation Through Online</h2>
            <p>You'll find us at 88 Harvest Street, Royal Park District — where flavor meets elegance.</p>
            <p><strong>Phone:</strong> (889) 907-1547</p>
            <p><strong>Email:</strong> TheTastyTableishere@gmail.com</p>
            <br>
            <p><strong>Hours:</strong></p>
            <p>Monday - Saturday: 3:00 PM - 10:00 PM</p>
            <p>Sunday's Special Event: 12:00 PM - 11:00 PM</p>
    </section>
    <footer>
        <p>&copy; 2025 The Tasty Table. All Rights Reserved.</p>
    </footer>
</body>
</html>

styles.css

 body{
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #000000;
        }
        header{
            background-color: #f0d507;
            color: #000000;
            font-family: playfair display, serif;
            font-style: italic;
            font-size: 19px;
            padding: 1.6px 32px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            
        }
        nav ul{
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 32px;
        }
        nav a{
            color: #000000;
            text-decoration: none;
            font-size: 27.2px;
        }
        .home{
            background: url('https://t4.ftcdn.net/jpg/08/02/40/81/240_F_802408102_AcjKfmam8MXIpFpuPdm9wHZKYSJ1AIHf.jpg');
            height: 100vh;
            padding: 0.1em 0em;
            text-align: center;
            align-content: center;
            color:#ffffff;
            font-size: 2em;
            font-family:'Playfair Display'erif;
            font-style:italic;
            text-shadow: 2px 2px 6px #000;
        }
        section{
            text-align: center;
            font-size: 1.5em;
            font-family: 'Playfair Display', serif;
            font-style: bold;
            padding: 2em;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 2em;
        }
        .items {
            background-color: #f0d507;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.815);
            padding: 1em;
            width: 250px;
        }
        .items img{
            width: 100%;
            border-radius: 10px;
        }
        .story{
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
        }
        .staff{
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(12, 12, 12, 0.815);
            padding: 1em;
            width: 250px;
        }
        footer {
        background-color: #000000;
        color: #ffffff;
        text-align: center;
        padding: 0.5em;
        }
```
# OUTPUT:
<img width="1044" height="607" alt="image" src="https://github.com/user-attachments/assets/2264a0e7-bfe6-4ed5-aa11-05ce63007160" />

<img width="1034" height="588" alt="image" src="https://github.com/user-attachments/assets/b7e816d1-5567-4f0b-aac5-6ed4eb80ae70" />

<img width="1038" height="593" alt="image" src="https://github.com/user-attachments/assets/21012fa3-e367-4197-97b4-464db5bcffdd" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
