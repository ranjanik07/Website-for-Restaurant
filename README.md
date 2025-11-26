# Ex.07 Restaurant Website
## Date:26-11-25
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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant</title>
  
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">Golden Spoon</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="index.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="menu.html">Menu</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="team.html">Our Team</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  
  <div class="container mt-5">
    <h1 class="text-center">Welcome to Golden Spoon</h1>
    <p class="text-center">Your destination for the most delicious meals in town!</p>

    
    <div class="text-center mb-4">
      <img src="C:\Users\admin\simplewebserver\restweb\name.jpg" class="img-fluid" alt="Restaurant Banner">
    </div>

    <h2 id="services" class="mt-4">What We Offer</h2>
    <div class="row">
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\dinn.jpg" class= "img-fluid mb-2" alt="Fine Dining">
        <h4>Fine Dining</h4>
        <p>Enjoy an exquisite dining experience with our gourmet dishes.</p>
      </div>
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\family.jpg" class="img-fluid mb-2" alt="Family Meals">
        <h4>Family Meals</h4>
        <p>Bring the whole family together with our family-friendly menus.</p>
      </div>
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\delivery.png" class="img-fluid mb-2" alt="Fast Delivery">
        <h4>Fast Delivery</h4>
        <p>Get your favorite meals delivered right to your door.</p>
      </div>
    </div>

    <h2 id="contact" class="mt-4">Get in Touch</h2>
    <p>Contact us to book a table or place an order.</p>

    
    <div class="text-center">
      <img src="C:\Users\admin\simplewebserver\restweb\con.webp" class="img-fluid" alt="Contact Us">
    </div>
  </div>

  
  <footer class="bg-dark text-white text-center py-3">
    <p>Designed and Developed by VIGNESH</p>
  </footer>

  
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - GoldenSpoon</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">Golden Spoon</a>
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
        <li class="nav-item active"><a class="nav-link" href="#">Menu</a></li>
        <li class="nav-item"><a class="nav-link" href="team.html">Our Team</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
      </ul>
    </div>
  </nav>
  <div class="container mt-5">
    <h1 class="text-center">Our Menu</h1>
    <div class="row">
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\Appetizers.jpg" class="img-fluid mb-2" alt="Appetizers">
        <h4>Appetizers</h4>
        <p>Start your meal with our delicious appetizers.</p>
      </div>
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\main course.jpg" class="img-fluid mb-2" alt="Main Courses">
        <h4>Main Courses</h4>
        <p>Savor the finest culinary delights.</p>
      </div>
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\desserts.webp" class="img-fluid mb-2" alt="Desserts">
        <h4>Desserts</h4>
        <p>End your meal on a sweet note.</p>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center py-3">
    <p>Designed and Developed by VIGNESH</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Golden Spoon</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">Golden Spoon</a>
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="menu.html">Menu</a></li>
        <li class="nav-item"><a class="nav-link" href="team.html">Our Team</a></li>
        <li class="nav-item active"><a class="nav-link" href="#">Contact</a></li>
      </ul>
    </div>
  </nav>
  <div class="container mt-5">
    <h1 class="text-center">Contact Information</h1>
    <p class="text-center">Reach out to us for reservations or inquiries:</p>
    <ul class="list-unstyled text-center">
      <li>Email: contact@GoldenSpoon.com</li>
      <li>Phone: (555) 123-4567</li>
      <li>Address: 456 Foodie Lane, Flavor Town, Country</li>
    </ul>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Team - Golden Spoon</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">Golden Spoon</a>
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="menu.html">Menu</a></li>
        <li class="nav-item active"><a class="nav-link" href="#">Our Team</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
      </ul>
    </div>
  </nav>
  <div class="container mt-5">
    <h1 class="text-center">Meet Our Team</h1>
    <div class="row">
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\john.webp" class="img-fluid mb-2 rounded-circle" alt="Chef">
        <h4>Chef John</h4>
        <p>Master Chef</p>
      </div>
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\mary smith.jpeg" class="img-fluid mb-2 rounded-circle" alt="Manager">
        <h4>Mary Smith</h4>
        <p>Restaurant Manager</p>
      </div>
      <div class="col-md-4 text-center">
        <img src="C:\Users\admin\simplewebserver\restweb\james.jpg" class="img-fluid mb-2 rounded-circle" alt="Staff">
        <h4>James Lee</h4>
        <p>Service Staff</p>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center py-3">
    <p>Designed and Developed by MAHA</p>
  </footer>
</body>
</html>

```

## OUTPUT:
![image1](https://github.com/user-attachments/assets/078e2ba8-2093-4285-a420-f00ebefc1483)
![image2](https://github.com/user-attachments/assets/cd0baad3-64ea-44c3-821a-88ece8c66ae4)
![image3](https://github.com/user-attachments/assets/79bbc588-dd16-4833-afe4-17cbe0a2f979)
![image4](https://github.com/user-attachments/assets/b4d352eb-bad6-49fe-8fc7-6c707f495a00)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
