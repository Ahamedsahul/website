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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant</title>
    <link rel="icon" href="mini.jpg">
    <style>
         body{
            background-color: rgb(239, 239, 239);
            
         }
         .img1{
            width: 500px;
            position: relative;
            top:50px
         }
         .two{
            background-color: rgb(50, 50, 50);
            border: 1px;
            border-radius: 15px;
            width: 800px;
            height: 50px;
            position: relative;
            top: 50px;
         }
         .a{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            right: 25px;
         }
         .b{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            right: 5px;
         }
         .c{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            left: 15px;
         }
         .d{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            left: 30px;
         }
         .three{
            background-image: url(offer.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            width: 900px;;
            height: 150px;
            border: 1px;
            border-radius: 20px;
            position:relative;
            left: 307px;
            top: 50px;

         }
         .h1{
            color: rgb(255, 255, 255);
            position: relative;
            left: 300px;
        
         }
         .p1{
            color: aliceblue;
            position: relative;
            top: 5px;
         }
         .four{
            background-color: lightcoral;
            width:300px;
            height: 400px;
            border: 1px;
            border-radius: 15px;
            position: relative;
            top: 50px;
            left: 20%;
           
         }
         .img2{
            width: 250px;
            position: relative;
            top: 10px;
         }
         .q{
            font-family: 'Times New Roman', Times, serif;
            position: relative;
            top: 10px;
            left: 20px;
         }
         .z{
            position: relative;
            top: 5px;
            left:20px
         }
         .e{
            font-size: 18px;
            position: relative;
            left: 20px;
         }
         .five{
            background-color: lightcoral;
            width:300px;
            height: 400px;
            border: 1px;
            border-radius: 15px;
            position: relative;
            bottom: 370px;
            left: 42%;
         }
         .w{
            font-family: 'Times New Roman', Times, serif;
            position: relative;
            top: 10px;
            left: 20px;
        }
        .img3{
            width: 250px;
            position: relative;
            top: 10px;
        }
        .x{
            position: relative;
            top: 5px;
            left:20px
        }
        .f{
            font-size: 18px;
            position: relative;
            left: 20px;
        }
        .six{
            background-color: lightcoral;
            width:300px;
            height: 400px;
            border: 1px;
            border-radius: 15px;
            position: relative;
            bottom: 790px;
            left: 64%;
        }
        .r{
            font-family: 'Times New Roman', Times, serif;
            position: relative;
            top: 10px;
            left: 20px; 
        }
        .img4{
            width: 250px;
            position: relative;
            top: 10px;
        }
        .v{
            font-size: 15px;
            position: relative;
            top: 5px;
            left:20px
        }
        .g{
            font-size: 18px;
            position: relative;
            left: 20px
        }
        .seven{
            text-align: right;
            font-size: 50px;
            position: relative;
            bottom: 1800px;
        }
        .eight{
            text-align: right;
            font-size: 50px;
            position: relative;
            bottom: 800px;
        } 
        .nine{
            text-align: right;
            position: relative;
            bottom: 800px;
        }
        .img5{
            width: 100px;
            position: relative;
            bottom: 800px;
        }
    </style>
</head>
<body>
    <div class="one">
        <center>
        <img src="logo.png" alt="Restaurant Logo" class="img1"></center>
        <center>
        <div class="two">
            <a href="" class="a">Home</a> <a href="" class="b">Menu</a> <a href="" class="c">Book</a> <a href="" class="d">About</a></div>
        </div></center>
        <div class="three">
            <h1 class="h1">30% off This Weekend</h1>
            <p class="p1">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quaerat, at animi, autem molestiae qui blanditiis sit aperiam debitis, asperiores minima laudantium? Ratione a quia enim exercitationem tempora asperiores magni et.</p>
        </div>
        <div class="four">
            <h2 class="q">Our New Menu</h2>
            <center>
            <img src="dish.jpg" alt="dish Image" class="img2">
            </center>
            <p class="z">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ab exercitationem debitis fugiat, facere illo cum a quis doloremque quidem suscipit laborum eos ratione. Quae quas neque impedit inventore perferendis itaque?</p>
            <a href="" class="e">See Our New Menu</a>            
        </div>  
        <div class="five">
            <h2 class="w">Book a Table</h2>
            <center>
                <img src="table.jpg" alt="table Image" class="img3">
            </center>
            <p class="x">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatem sit libero commodi dolor aliquid eligendi, maxime asperiores iusto excepturi officiis rem non animi nam sunt ipsa id, ex exercitationem eius.</p>
            <a href="" class="f">Book Your Table Now</a>       
        </div>
        <div class="six">
            <h2 class="r">Opening Hours</h2>
            <center>
                <img src="work.jpg" alt="cooking Image" class="img4">
            </center>
            <p class="v">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo labore placeat explicabo assumenda perferendis magni doloribus odio atque sapiente suscipit animi magnam, laboriosam corrupti repellendus, deserunt at corporis, expedita quas!</p>
            <a href="" class="g">Click For Timings</a> 
        </div>
        <div class="eight">_________________________________</div>
        <div class="nine">Copyright Little Lemon</div>
        <img src="mini.jpg" alt="" class="img5">
        <div class="seven">______________________________________________________________</div>
    </div>
</body>
</html>
```
About.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <link rel="icon" href="mini.jpg">
    <style>
         body{
            background-color: rgb(239, 239, 239);
            
         }
         .img1{
            width: 500px;
            position: relative;
            top: -10px;
         }
         .two{
            background-color: rgb(50, 50, 50);
            border: 1px;
            border-radius: 15px;
            width: 800px;
            height: 50px;
            position: relative;
            top: -10px;
         }
         .a{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            right: 25px;
         }
         .b{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            right: 5px;
         }
         .c{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            left: 15px;
         }
         .d{
           color: aliceblue; 
            font-size: 20px;
            font-family: 'Times New Roman', Times, serif ;
            position: relative;
            top: 10px;
            left: 30px;
         }
        .image1{
            width: 250px;
            position: relative;
            top: 10px;
        }
        .image2{
            width: 250px;
            position: relative;
        }
        .seven{
            text-align: right;
            font-size: 50px;
            position: relative;
            top: -15px;
        }
        .about-container {
            text-align: center;
            margin: 50px auto;
            max-width: 800px;
            position: relative;
            top: -90px;
        }
    </style>
</head>
<body>
    <div class="seven">______________________________________________________________</div>
    <div class="one">
        <center>
        <img src="logo.png" alt="Restaurant Logo" class="img1"></center>
        <center>
        <div class="two">
            <a href="" class="a">Home</a> <a href="" class="b">Menu</a> <a href="" class="c">Contact</a> <a href="" class="d">About</a></div>
        </div></center>
        <br>
        <br>
        <br>
        <div class="about-container">
            <center><h1>About Us</h1></center>
            <p>Welcome to <strong>Little Lemon</strong>! Established in 2024, we pride ourselves on serving delicious and fresh Mediterranean cuisine. Our mission is to bring family and friends together over a great meal, prepared with the finest ingredients and love.</p>
        
            <p>At Little Lemon, we believe food is more than just nourishment—it's about creating unforgettable experiences. Whether you're here for a quick lunch or a special dinner, our cozy atmosphere and mouth-watering dishes will make you feel at home.</p>
        
            <div class="team-images">
                <Div class="CHEF"><h2>OUR CHEF</h2><img src="chef.webp" alt="Our Chef" class="image1"></Div>
                <div class="interior"><h2>OUR RESTAURANT INTERIOR</h2><img src="interiror.webp" alt="Restaurant Interior" class="image2"></div>
            </div>
        
            <p>Come visit us, meet our friendly team, and taste the difference. We look forward to serving you!</p>
        </div>
        
        <!-- Footer -->
        <footer>
            <p>&copy; 2024 Little Lemon. All Rights Reserved.</p>
        </footer>
       
    </div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2024-11-25 112902.png>)
![alt text](<Screenshot 2024-11-25 112920.png>)
![Screenshot 2024-12-16 223930](https://github.com/user-attachments/assets/daf1007e-1eb5-41c0-8e2c-eddb5a85bdcf)
![Screenshot 2024-12-16 223941](https://github.com/user-attachments/assets/865a246c-cee9-45ac-bc49-4d7bd3024320)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
