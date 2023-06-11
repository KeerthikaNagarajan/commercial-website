# Ex-02:
## Create a commercial website using HTML & CSS
### AIM:
The aim of this code is to create a commercial website for a car tuning service.
### ALGORITHM:
1. Create an HTML document with the necessary structure, including the doctype declaration, opening and closing HTML tags, and head and body sections.
2. Within the head section, include the title of the webpage and link the CSS file.
3. Create a container div to hold the main content of the webpage.
4. Inside the container, include an image of a car as the main visual element using the img tag.
5. Create another container div for additional content.
6. Inside this container, include an image aligned to the right and paragraphs to explain the concept of tuning and its benefits.
7. Add icons and descriptive text for key features of tuning.
8. Add a stylized text section with two values and descriptions related to performance improvements.
9. Finally, include a footer with links for home, projects, team, and contacts, along with copyright information and social media icons.
### PROGRAM:
#### car.html
```
<!DOCTYPE html>
<html>
<head>
  <title>CAR</title>
  <link rel="stylesheet" href="carweb.css">
  
</head>
<body>
  <nav>
    <a style="color: rgb(211, 71, 6); font-family: Verdana, Geneva, Tahoma, sans-serif; padding-right: 80px;"><b>BEST TUNING</b></a>
    <a href="#">home</a>
    <a href="#">projects</a>
    <a href="#">team</a>
    <a href="#">contacts</a>
    <a class="button" href="#">Book an Appointment</a>
  </nav>
  <div class="container">
  <img class="front" src="Frontt.jpg"/>
  <div class="bottom-left">
    <p class="firstp" style="font-size: medium; padding-right: 130px;">TUNING&ensp;PERFECTION</p>
    <p class="firstp">Tuning&ensp;is&ensp;an&ensp;upgrade<br>
    that&ensp;unloacks&ensp;hidden<br>
    potential&ensp;of&ensp;your&ensp;car</p></div>
  </div>

    <div class="container">
        <p class="explore">&#8595 Explore</p>
<br><br>
        <div class="secondp">
        <img class="speed" src="speeding.jpeg" align="right"/>
        <p style="font-size: medium;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">WHY DO YOU WANT IT?</p>
        <p>What is Tuning and<br>Why do You Want it?</p>
        <p style="font-size: medium;">Tuning is an upgrade to the software in the vehicle's computer.<br>Custom software is installed that changes many parameters<br>
            that control the way the engine operates. With proper tuning,<br>you can increase both power and fuel economy.</p></div>
        <img class="icon" src="clock.png" >
        <img class="icon" src="pet.png" style="padding-left: 150px;">
        <br>
        <p class="ficon">A comprehensive tool&emsp;&emsp;&emsp;&emsp;With proper tuning,<br>for high horsepower &emsp;&emsp;&emsp;&emsp;&ensp;you can increase fuel<br>builds.&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;economy.</p>
    </div>

    <br><br>
    <div class="container">
        <div class="carlogop">
        <img class="lastcar" src="carlogofront.jpg" align="left"/>
        <p style="font-size: medium;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">ADVANTAGES</p>
            <p>What can I Expect<br>
            from Tuning?</p>
            <p style="font-size: medium;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">What can I Expect from Tuning?<br>
            Through proper modification, it is possible to greatly increase<br>
            the power output of the vehicle, while at the same time<br>
            Improving safety and longevity of the engine, drivability, and<br>
            smoothness.</p>
            <div><span class="text-with-line">20-35 hp</span>&emsp;&emsp;&emsp;
                <span class="text-with-line">35-50 hp</span></div>
              <p style="font-size: medium; padding-top: 19px;">roughly increase from&emsp;&emsp;&emsp;roughly increase from<br>a stage 1 tune&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;a stage 2 tune</p>
        </div>
    </div>
<br><br><br><br><br><br><br><br>
    <nav>
        <a style="color: rgb(211, 71, 6); font-family: Verdana, Geneva, Tahoma, sans-serif; padding-right: 120px;"><b>BEST TUNING</b></a>
        <a href="#">home</a>
        <a href="#">projects</a>
        <a href="#">team</a>
        <a href="#">contacts</a>
        <a>&#169;2019 Best Tuning. All rights concerned</a>
        <a href="#"><img src="face.png" width="30"/></a>
        <a href="#"><img src="linked.png" width="35"/></a>
      </nav>
</body>
</html>
```
#### carweb.css
```
body {
    background-color: rgba(0, 0, 0, 0.982);
    height: 125vh;  
    margin-top: 18px;  
    background-size: cover; 
    margin-right: 80px;
  }  
  nav{
    padding-left: 80px;
  }
    nav a {
      float: left;
      color: #ffffff;
      text-align: center;
      padding: 16px 18px;
      text-decoration: none;
      font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-size: medium;
    }
    nav a.button {
      float: right;
      background-color: rgb(211, 71, 6);
      color: white;
      padding: 15px 20px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 14px;
      margin: 10px;
      cursor: pointer;
      border-radius: 12px;
      font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .container {
        position: relative;
        color: white;
        
      }
      .bottom-left {
        position: absolute;
        bottom: 8px;
        left: 16px;
      }
      .firstp{
        padding-left: 40px;
        font:bolder;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size:xx-large;
      }
      .secondp{
        padding-left: 60px;
        font:bolder;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size:xx-large;
      }
      .explore{
        padding-left: 60px;
      }
    .front{
        padding-right: 40px;
        padding-left: 40px;
        width: 100%;
    }
    .speed{
      width: 60%;
      vertical-align: middle;
  }
    .lastcar{
        padding-right: 70px;
        width: 55%;
    }
    .icon{
        padding-left: 60px;
        width: 50px;
    }
    .ficon{
        padding-left: 60px;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size:medium;
    }
    .carlogop{
        font:bolder;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size:xx-large;
    }
    .text-with-line {
        position: relative;
        display: inline-block;
        font-size: 24px;
      }
      
      .text-with-line::after {
        content: "";
        position: absolute;
        left: 0;
        bottom: -20px;
        width: 30%;
        height: 6px;
        background-color:  rgb(211, 71, 6);;
      }
```
### OUTPUT:
![Web capture_6-6-2023_1770_](https://github.com/KeerthikaNagarajan/commercial-website-using-HTML-CSS/assets/93427089/d26af262-7ecf-47f1-90e0-c6caf260c8ab)

### RESULT:
The code will generate a commercial website with a navigation bar, visual elements, descriptive paragraphs, and relevant images to showcase the car tuning service. The website will have a professional and visually appealing design to attract potential customers and provide them with information about the benefits of tuning their cars.
