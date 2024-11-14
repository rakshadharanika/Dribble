# Project Responsive Web Design using Bootstrap
### Name   : V Raksha dharanika
### Reg no: 212223230167

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```py


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>


<nav class="navbar navbar-expand-lg navbar-light bg-light shadow-light">
  <div class="container">
    <a class="navbar-brand text-primary" href="#"><strong>Dribbble Clone</strong></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link text-dark active" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-dark" href="#">Shots</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-dark" href="#">Designers</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-dark" href="#">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
</nav>


<section class="text-center text-white" style="background-image: linear-gradient(to bottom right, #5c67f5, #7091ff); padding: 100px 0;">
  <div class="container">
    <h1 style="font-weight: bold; font-size: 2.5rem;">Discover the World’s Top Designers & Creatives</h1>
    <p style="font-size: 1.1rem;">Join the Dribbble community to showcase your work, inspire others, and find design inspiration.</p>
    <a href="#" class="btn btn-primary btn-lg mt-3">Get Started</a>
  </div>
</section>


<section class="featured-section">
  <div class="container">
    <h2 class="text-center text-primary mb-5">Featured UI/UX Shots</h2>
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="C:\Users\A.sathish\Downloads\flat-design-geometric-pattern-mobile-design-template_23-2149939686.avif" class="card-img-top" alt="Shot 1">
          <div class="card-body">
            <h5 class="card-title text-primary">Creative App Interface</h5>
            <p class="card-text text-secondary">A brief description of the app interface design.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="C:\Users\A.sathish\Downloads\gradient-ui-ux-elements_23-2149057420.avif" class="card-img-top" alt="Shot 2">
          <div class="card-body">
            <h5 class="card-title text-info">Modern Dashboard UI</h5>
            <p class="card-text text-secondary">A sleek, modern dashboard design for data visualization.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="C:\Users\A.sathish\Downloads\online-shopping-landing-page_33099-1725.avif" class="card-img-top" alt="Shot 3">
          <div class="card-body">
            <h5 class="card-title text-success">E-commerce Web Design</h5>
            <p class="card-text text-secondary">An attractive e-commerce landing page for a smooth user experience.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>


<footer class="footer text-white" style="background-color: #333; padding: 30px 0; text-align: center;">
  <div class="container">
    <p>&copy; 2023 Dribbble Clone. All rights reserved.</p>
    <p>Created by Raksha Dharanika V</p>
    <p>
      <a href="#" style="color: #b5b5b5;">Privacy Policy</a> |
      <a href="#" style="color: #b5b5b5;">Terms of Service</a>
    </p>
  </div>
</footer>


<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/4f644ce2-f13a-47b4-a1dc-10e97e75d75a)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
