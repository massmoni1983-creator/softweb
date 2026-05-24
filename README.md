# Ex.06 Restuarant Website
## Date: 24-05-2026

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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

## Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siam Bistro</title>

    <link rel="stylesheet" href="stylesheet.css">
</head>

<body>

    <header>

        <div class="logo-section">
            <img src="logo.png" class="logo">
            <h1>SIGMA RESTAURENT</h1>
        </div>

        <nav>
            <a href="/">Home</a>
            <a href="/menu/">Menu</a>
            <a href="/adminpage/">Administration</a>
            <a href="/contact/">Contact Us</a>
        </nav>

    </header>

    <section class="home-container">

        <div class="card">

            <img src="biryani.png">

            <h2>SPECIAL MENU</h2>

            <p>
                OUR SPECIAL CHICKEN VARIETY FOR 
                SMASHING YOUR HUNGER
            </p>

            <button>MENU</button>

        </div>

        <div class="card">

            <img src="BOOKING.png">

            <h2>TABLE BOOKING</h2>

            <p>
                BOOKING A TABLE WILL BE CONVINIENT 
                FOR YOUR DINING AND SAVING YOUR TIME
            </p>

            <button>TABLE BOOKING</button>

        </div>

        <div class="card">

            <img src="timig.png">

            <h2>Opening Hours</h2>

            <p>
                Mon - Fri : 9am - 11pm <br>
                Weekend : 7am - 12pm
            </p>

        </div>

    </section>

    <footer>

        <img src="logo.png" class="footer-logo">

        <p>SIGMA RESTAURENT</p>

    </footer>

</body>
</html>
```
## Menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>

    <link rel="stylesheet" href="stylesheet.css">
</head>

<body>

    <header>

        <div class="logo-section">
            <img src="logo.png" class="logo">
            <h1>SIGMA RESTAURENT</h1>
        </div>

        <nav>
            <a href="/">Home</a>
            <a href="/menu/">Menu</a>
            <a href="/adminpage/">Administration</a>
            <a href="/contact/">Contact Us</a>
        </nav>

    </header>

    <section class="menu-section">

        <h1>Menu</h1>

        <div class="menu-container">

            <div class="menu-card">

                <img src="biryani.png">

                <h2>BIRYANI</h2>

            

                <h3>₹250</h3>

            </div>

            <div class="menu-card">

                <img src="grill.png">

                <h2>GRILLED CHICKEN</h2>

                

                <h3>₹400</h3>

            </div>

            <div class="menu-card">

                <img src="tandoori.png">

                <h2>THANDOORI CHICKEN</h2>

                

                <h3>₹450</h3>

            </div>

            <div class="menu-card">

                <img src="shawarma.png">

                <h2>CHICKEN SHAWARMA</h2>

                

                <h3>₹150</h3>

            </div>

        </div>

    </section>

    <footer>

        <img src="logo.png" class="footer-logo">

        <p>SIGMA RESTAURENT</p>

    </footer>

</body>
</html>
```
## Admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>

    <link rel="stylesheet" href="stylesheet.css">
</head>

<body>

    <header>

        <div class="logo-section">
            <img src="logo.png" class="logo">
            <h1>SIGMA RESTAURENT</h1>
        </div>

        <nav>
            <a href="/">Home</a>
            <a href="/menu/">Menu</a>
            <a href="/adminpage/">Administration</a>
            <a href="/contact/">Contact Us</a>
        </nav>

    </header>

    <section class="admin-section">

        <h1>Administration Team</h1>

        <div class="admin-container">

            <div class="admin-card">
                <img src="vijay -1.png">
                <h3>C. JOSEPH VIJAY</h3>
                <p>MASTER CHEF</p>
            </div>

            <div class="admin-card">
                <img src="cr7 -4.png">
                <h3>CRISTIANO RONALDO-7</h3>
                <p>RESTAURENT MANAGER</p>
            </div>

            <div class="admin-card">
                <img src="stalin -2.png">
                <h3>M.K.STALIN</h3>
                <p>ASSISTENT CHEF</p>
            </div>

            <div class="admin-card">
                <img src="dhoni -3.png">
                <h3>M.S.DHONI -7</h3>
                <p>IMPACT CHEF</p>
            </div>

            <div class="admin-card">
                <img src="ana -5.png">
                <h3>ANA DE ARMAS</h3>
                <p>BELLY DANCER</p>
            </div>

        </div>

    </section>

    <footer>

        <img src="logo.png" class="footer-logo">

       <p>SIGMA RESTAURENT</p>

    </footer>

</body>
</html>
```
## Contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>

    <link rel="stylesheet" href="stylesheet.css">
</head>

<body>

    <header>

        <div class="logo-section">
            <img src="logo.png" class="logo">
            <h1>SIGMA RESTAURENT</h1>
        </div>

        <nav>
            <a href="/">Home</a>
            <a href="/menu/">Menu</a>
            <a href="/adminpage/">Administration</a>
            <a href="/contact/">Contact Us</a>
        </nav>

    </header>

    <section class="contact-section">

        <div class="contact-box">

            <h1>Contact Us</h1>

            <form>

                <input type="text" placeholder="Enter Your Name">

                <input type="number" placeholder="Enter Your Phone Number">

                <textarea rows="6" placeholder="Any Message"></textarea>

                <button type="submit">Send Message</button>

            </form>

        </div>

    </section>

    <footer>

        <img src="logo.png" class="footer-logo">
        <p>SIGMA RESTAURENT</p>
        
    </footer>

</body>
</html>
```
## Stylesheet.css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#442020;
}


header{
    width:100%;
    background:#111;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 40px;
}

.logo-section{
    display:flex;
    align-items:center;
    gap:15px;
}

.logo{
    width:45px;
    height:45px;
}

.logo-section h1{
    color:white;
    font-size:35px;
}


nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    font-weight:bold;
    font-size:14px;
}

nav a:hover{
    color:orange;
}

.active{
    color:orange;
}


.home-container{
    width:90%;
    margin:60px auto;
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.card{
    width:300px;
    background:#f1f1f1;
    padding:20px;
    border-radius:8px;
    text-align:center;
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
    border-radius:5px;
}

.card h2{
    margin-top:20px;
    margin-bottom:15px;
}

.card p{
    color:#333;
    line-height:25px;
    margin-bottom:20px;
}

button{
    background:orange;
    color:white;
    border:none;
    padding:10px 18px;
    border-radius:5px;
    cursor:pointer;
    font-weight:bold;
}

button:hover{
    background:#cc8400;
}


.menu-section{
    width:90%;
    margin:60px auto;
    text-align:center;
}

.menu-section h1{
    margin-bottom:50px;
    font-size:40px;
}

.menu-container{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.menu-card{
    width:300px;
    background:#f1f1f1;
    padding:20px;
    border-radius:8px;
}

.menu-card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.menu-card h2{
    margin-top:15px;
    margin-bottom:15px;
}

.menu-card p{
    line-height:25px;
    margin-bottom:15px;
}

.menu-card h3{
    color:green;
}



.admin-section{
    width:90%;
    margin:60px auto;
    text-align:center;
}

.admin-section h1{
    margin-bottom:50px;
    font-size:40px;
}

.admin-container{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}

.admin-card{
    width:220px;
    background:#f1f1f1;
    padding:15px;
    border-radius:8px;
}

.admin-card img{
    width:100%;
    height:180px;
    object-fit:cover;
}

.admin-card h3{
    margin-top:15px;
    margin-bottom:10px;
}

.admin-card p{
    color:#555;
}


.contact-section{
    display:flex;
    justify-content:center;
    align-items:center;
    height:75vh;
}

.contact-box{
    width:500px;
    background:#f1f1f1;
    padding:40px;
    border-radius:8px;
}

.contact-box h1{
    text-align:center;
    margin-bottom:30px;
}

.contact-box input,
.contact-box textarea{
    width:100%;
    padding:12px;
    margin-bottom:20px;
    border:1px solid #ccc;
}

/* FOOTER */

footer{
    width:100%;
    background:#111;
    text-align:center;
    padding:25px;
    margin-top:50px;
}

.footer-logo{
    width:25px;
    margin-bottom:10px;
}

footer p{
    color:white;
}
```


## OUTPUT:
<img width="1919" height="1133" alt="Screenshot 2026-05-24 143820" src="https://github.com/user-attachments/assets/f461cf9d-f4f2-4dbc-a917-bde7747d0334" />

<img width="1919" height="1148" alt="Screenshot 2026-05-24 143849" src="https://github.com/user-attachments/assets/69b2bdad-a290-44c2-a33c-44428b6bb5ef" />

<img width="1919" height="1148" alt="Screenshot 2026-05-24 143926" src="https://github.com/user-attachments/assets/35c04cf8-52fa-4226-8590-b5dd59660282" />

<img width="1919" height="1144" alt="Screenshot 2026-05-24 144038" src="https://github.com/user-attachments/assets/d6c024e0-adf4-41d9-9203-7d94aefcd17f" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
