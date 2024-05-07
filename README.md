# Project Responsive Web Design using Bootstrap
## Date:07-05-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PharmaCo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        a {
            color: red;
            padding: 10px;
            text-decoration: none;
            font-size: 20px;
            font-weight: 200;
        }

        a:hover {
            color: red;
            text-decoration: dotted red;
        }

        .navbar-nav .nav-item.dropdown:hover .dropdown-menu {
            display: block;
        }

        .dropdown:hover .dropdown-menu {
            display: block;
        }
    </style>
</head>
<body style="background-image: url('pharma_background.png');background-size: fill;">

<div class="container">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <a class="navbar-brand" href="#">PharmaCo</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                    <a class="nav-link" href="web.html">Home</a>
                </li>
                <li class="nav-item dropdown active">
                    <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button"
                       aria-haspopup="true" aria-expanded="false">
                        About
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                        <a class="dropdown-item" href="#vision">Vision</a>
                        <a class="dropdown-item" href="#mission">Mission</a>
                        <a class="dropdown-item" href="#values">Values</a>
                    </div>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="product.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <div style="width: 10%;">
        <img src="pharmaco_logo.png" style="width: 80%;">
    </div>

    <h1 style="color: red; font-size: 50px;">PharmaCo, Advancing Healthcare Together</h1>
    <h1 style="color: red; font-size: 20px;">PharmaCo is dedicated to revolutionizing healthcare through cutting-edge pharmaceuticals and innovative medical solutions.
        Our commitment lies in improving patient outcomes, enhancing quality of life, and addressing unmet medical needs globally.
    </h1>

    <div style="display: flex; text-align: center;align-items: flex;">
        <div class="card" style="width: 100%; margin: 30px;">
            <img src="drug1.webp" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">New Breakthrough Drug Approval</h5>
                <p class="card-text">PharmaCo announces FDA approval for its latest breakthrough drug, offering hope for patients with chronic conditions.
                    Learn more about how this innovative treatment is transforming lives.</p>
                <a href="#" class="btn btn-primary">READ MORE</a>
            </div>
        </div>
        <div style="display: flex; text-align: center;align-items: flex;">
            <div class="card" style="width: 100%; margin: 30px;">
                <img src="drug2.webp" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Revolutionary Cancer Treatment Unveiled</h5>
                    <p class="card-text">PharmaCo introduces a groundbreaking cancer treatment, leveraging advanced immunotherapy techniques to target malignant cells with unprecedented precision. Witness the future of oncology care.</p>
                    <a href="#" class="btn btn-primary">EXPLORE NOW</a>
                </div>
            </div>
        </div>
        <div style="display: flex; text-align: center;align-items: flex;">
            <div class="card" style="width: 100%; margin: 30px;">
                <img src="drug3.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Breakthrough Alzheimer's Research Breaks New Ground</h5>
                    <p class="card-text">PharmaCo's latest research initiative promises hope for millions affected by Alzheimer's disease. With promising early results, learn how we're tackling one of the most challenging medical mysteries of our time.</p>
                    <a href="#" class="btn btn-primary">EXPLORE NOW</a>
                </div>
            </div>
        </div>
        
    </div>

    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" data-interval="2" style="margin-top: 20px;">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="pharma_slider1.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="pharma_slider2.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="pharma_slider3.png" class="d-block w-100" alt="...">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
    <footer class="bg-dark text-light text-center py-3">
        <div class="container">
            <p>&#169 Sri Harish B [212223220110] 2024 PharmaCo. All rights reserved.</p>
        </div>
    </footer>
    <script>
        var carousels = document.querySelectorAll('.carousel');
        carousels.forEach(function(carousel) {
            new bootstrap.Carousel(carousel);
        });
    </script>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>

```
## OUTPUT:

![alt text](<Screenshot 2024-05-07 115138.png>)

![alt text](<Screenshot 2024-05-07 115144.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
