# Ex.07 Software Product Company Website
## Date:31/10/2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
### sample.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
    <script src="scripts.js"></script>
</head>
<body>


    
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo" >Prism Pixel Innovations</h2>
            </div>
            <h2 style = " font-family: Garamond, sans-serif;float: right; color: rgb(255, 255, 255); padding: 20px;">login/signup</h2>
            <div class = "container">
                <nav>
                    <ul>
                        <li onclick="showContent('Home')">Home</li>
                        <li onclick="showContent('products')">products</li>
                        <li onclick="showContent('AboutUS')">AboutUS</li>
                        <li onclick="showContent('ContactUs')">ContactUs</li>
                    </ul>
                 </nav>
            </div>
        </div> 


        <section id="Home" class="active">
            <div class = "center"> 
                <div class ="white-box">
                    <div class = "line">
                        <img src = "software-development-specialist.jpg  " style="width: 600px; height: 300px; padding-top: 50px; padding-left: 20px;">
                        <h2 style ="font-size: 40 ; padding: 50px; padding-top: 130px;color :rgb(2, 64, 66)">"We Transform Visions into Seamless, Digital Realities."</h2>
                    </div>
                </div>
            </div>
        </section>

        


        <section id="products">
            <div class = "center">
                <div class = "white-box">
                    <img src = "360_F_444957056_Gz4m48tyh5j89hNyuc5CsLvPNyiMWNvy.jpg   " style="width: 1000px; height: 300px; padding-top: 50px; padding-left: 30px;">
                </div>
            </div>
        </section>


        <section id="AboutUS">
            <div class = "center">
                <h1 style ="font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif, Cochin, Georgia, Times, 'Times New Roman', serif;color: rgb(30, 2, 57);">we are a team of dedicated and experienced software developers committed to delivering
                    high-quality solutions.</h1>
                <h1 style ="font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif, Cochin, Georgia, Times, 'Times New Roman', serif;color: rgb(30, 2, 57);">We focus on leveraging cutting-edge technologies to create innovative and scalable software solutions for
                    our clients. Our team is passionate about turning ideas into reality and providing exceptional value to
                    businesses of all sizes.</h1>
                <div class = "white-box">
                    <div class = "line">
                        <img src = " WhatsApp Image 2023-11-15 at 21.34.13_554c48bf.jpg " alt="Avatar" style="width: 140px; height: 160px;padding: 40px;border-radius: 50%;">
                        <img src = "Adobe Scan Sep 01, 2023_1 (1).jpg "  alt="Avatar" style="width: 140px; height: 160px; padding: 40px;border-radius: 50%;">
                        <img src = "IMG_0335.JPEG  " alt="Avatar" style="width: 140px; height: 160px;padding: 40px;border-radius: 50%;">
                        <img src = "WhatsApp Image 2023-11-15 at 21.32.17_80d71b1d.jpg" alt="Avatar" style="width: 140px; height: 160px;padding: 40px;border-radius: 50%;">
                        <img src = "WhatsApp Image 2023-11-15 at 21.35.59_30ce34b3.jpg " alt="Avatar" style="width: 140px; height: 160px;padding: 40px;border-radius: 50%;">
                        <img src = "WhatsApp Image 2023-11-15 at 21.34.45_bf646d5c.jpg " alt="Avatar" style="width: 140px; height: 160px;padding: 40px;border-radius: 50%;">


                    </div>
                    <div class = "line">
                        <h4 style ="font-family: Times New Roman; padding-left: 25px;color: rgb(0, 0, 0);">SRIMATHI (COO)</h4>
                        <h4 style ="font-family: Times New Roman; padding-left: 100px;color: rgb(0, 0, 0);">PREETHI (CEO)</h4>
                        <h4 style ="font-family: Times New Roman; padding-left: 100px;color: rgb(0, 0, 0);">SATHYA (MD) </h4>
                        <h4 style ="font-family: Times New Roman; padding-left: 75px;color: rgb(0, 0, 0);">JAYALAKSHMI (MD)</h4>
                        <h4 style ="font-family: Times New Roman; padding-left: 90px;color: rgb(0, 0, 0);">SWETHA (CFO)</h4>
                        <h4 style ="font-family: Times New Roman; padding-left: 90px;color: rgb(0, 0, 0);">POOJA (CFO)</h4>

                    </div>
                </div>
            </div>
        </section>


        <section id="ContactUs">
            <div class = "center">
                <div class = "white-box">
                    `<div class="contact-form">
                        <h1>Contact Us</h1>
                        <form action="submit_form.php" method="POST">
                            <div class="form-group">
                                <input type="text" id="name" name="name" placeholder="Your Name" required>
                            </div>
                            <div class="form-group">
                                <input type="email" id="email" name="email" placeholder="Your Email" required>
                            </div>
                            <div class="form-group">
                                <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                            </div>
                            <button type="submit">Submit</button>
                        </form>
                    </div>  
                </div>
            </div>
        </section>
    </div>

    <footer class="bg-light text-center py-3">
        <p>&copy; Srimathi K</p>
      </footer>
    
</body>
</html>
```

### style.css
```
style.css
*{
    margin: 0;
    padding: 0;
}

.main
{
    width: 100%;
    background: linear-gradient(to top, rgb(144, 13, 164)0%,rgb(30, 128, 153)30%);
    background-position: center;
    background-size: cover;
    height: 100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color: #ffffff;
    font-size: 35px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    padding-left: 20px;
    float: center;
    padding-top: 10px;
    margin-top: 5px
}

.menu{
    width: 400px;
    float: right;
    height: 70px;
}
nav
{
  padding: 30px 300px;
}
nav ul li
{
  list-style: none;   
  display: inline-table;
  padding: 0px 23px;
  margin: 3px;
  font-size: 18px;
  font-weight: 500;
  color: #073646;
  cursor: pointer;
  position: relative;
  z-index: 2;
  transition: color 0.5s;
}
nav ul li::after{
  content: '';
  background: #154e6c;
  width: 100%;
  height: 100%;
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translate(-50% ,-50%);
  z-index: -1;
  opacity: 0;
  transform: top 0.5s ,opacity 0.5s;
}
nav ul li:hover
{
  color:#fff;   
}
nav ul li:hover::after
{
  top : 50%;
  opacity: 1;
}
.center
{
  padding-left: 100px;
  padding-top: 100px;
}
.white-box
{
  width: 1300px;
  height: 400px;
  background-color: white;
  border: 1px solid #68bcc6;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section {
  display: none;
}

section.active {
  display: block;
}
.line
{
  display: flex;
}
.contact-form, .contact-info {
  padding: 20px;
  flex: 1;
}
.contact-form {
  text-align: left;
}
.form-group {
  margin: 10px 0;
}
input[type="text"],
input[type="email"],
textarea {
    width: 50%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

```

### scripts.js

```
function showContent(option) 
{
    const plantsContentDiv = document.getElementById('Home');
    const seedsContentDiv = document.getElementById('products');
    const planterContentDiv = document.getElementById('AboutUS');
    const soilContentDiv = document.getElementById('ContactUs');

    if (option === 'Home') {
        plantsContentDiv.style.display = 'block';
        seedsContentDiv.style.display = 'none';
        planterContentDiv.style.display = 'none';
        soilContentDiv.style.display = 'none';
        
    }
    else if (option === 'products') {
        plantsContentDiv.style.display = 'none';
        seedsContentDiv.style.display = 'block';
        planterContentDiv.style.display = 'none';
        soilContentDiv.style.display = 'none';
    }
    else if (option === 'AboutUS') {
        plantsContentDiv.style.display = 'none';
        seedsContentDiv.style.display = 'none';
        planterContentDiv.style.display = 'block';
        soilContentDiv.style.display = 'none';
    }
    else if (option === 'ContactUs') {
        plantsContentDiv.style.display = 'none';
        seedsContentDiv.style.display = 'none';
        planterContentDiv.style.display = 'none';
        soilContentDiv.style.display = 'block';
    }
}

```
## OUTPUT:
![Alt text](web7.PNG)
![Alt text](we71.PNG)
![Alt text](web72.PNG)
![Alt text](web73.PNG)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
